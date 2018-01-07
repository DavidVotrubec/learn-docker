# Learning Docker by doing examples.

Starting with examples found in http://training.play-with-docker.com/

## First step:
### Hello world app - run command `docker container run hello-world`

workflow was like this:
- download image (by Docker Deamon)
- create container based on that image (by Docker Deamon)
- run executable in that image (run by whatever is in that container)
- display the output of execution in console (streamed by Docker Deamon, but captured and displayed by Docker Client)

## Basic commands
- docker image ls -list all images download to current file system
- docker image pull <name> - pulls image from registry
(Default registry is 'Docker Registry', Default tag is 'latest')
- [winpty] docker run -it <image-name> <command-name> - runs interactive terminal based on image name. Example 'docker run -it alpine apk'
winpty is optional, applies only for Windows environments
