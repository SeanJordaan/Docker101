# Docker101
A docker step by step
Load up a spring application 
Create a simple REST API 
Anitate the spring project with @RestController and @GetMapping so that the path is shown with (“/welcome”)
Have it return a string “Docker Demo”;
Create a .jar file with Maven 
Create a Dockerfile withing the file that you are using 
Then you have to build the image using 
First cd to the file that you have the spring project in 
Docker build -t(T stands for the tag) then the files name: then the tack then a .( the . is to indicate that we are in the file that the jar is in)
After it runs then type docker images to see if the image has been created with the tag that you gave it. 
Then do a docker run -p(to show witch port you want to use normally its 8080:8080) then the name of your file. Not the tag that you gave.

 
