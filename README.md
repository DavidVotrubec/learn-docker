# Learning Docker by doing examples.

Starting with examples found in http://training.play-with-docker.com/

## First step:
### Hello world app - run command `docker container run hello-world`

workflow was like this:
- download image (by Docker Deamon)
- create container based on that image (by Docker Deamon)
- run executable in that image (run by whatever is in that container)
- display the output of execution in console (stread by Docker Deamon, but captured and displayed by Docker Client)