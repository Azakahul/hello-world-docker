# Hello-World-Docker 

This is a project to learn how to use desktop docker to enable containerized future solutions.

## To Start:

1. Run: ```docker run -d -p 4000:80 friendlyhello```
    1. This will run the container detached from the command window and allow for other commands to be run.  to run without detaching the app just remove the -d flag.

## To Check:

1. App Should run on ```http://localhost:4000```
1. You can see if the container is active by: ```docker container ls```

## To Stop:

1. Run: ```docker container stop <container name OR id>```