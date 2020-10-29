# HTTP-Server
	
**********Description**********

This program takes the command line and create request and send it to the server.
The request include the flags- 	
    # '-r' (format: <n> name=value...) witch are the variables of the path.
		# '-p' (format: <text>) witch the program calculates it's length and take the text itself.

								
**********Functions**********

-void createRequest(Request *request);
-void errorFunc(Request *request);
-void freeAll(Request *request);
-int httpPrefix(const char *pre, const char *str);


**********Program Files**********

-client.c - the file contains the implimention of the functions.
-README.txt - the file contain an information about the file.


**********How to compile**********

Write in the terminal 'gcc -Wall -o client client.c'.


**********How to run**********

Write in the terminal: ./client [-p <text>] [-r n <pr1=value1 pr2=value2 …>] <URL>


**********Output**********

printing the request and the response that received from the request that sent to the server.

