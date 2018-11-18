# You can specify any image that is an 'official' image at hup.docker.com
# This uses a small one recommended at www.youtube.com/watch?v=hnxl-K10auY
#
# This will download a very basic alpine linux distribution
FROM alpine

CMD ["/bin/sh"] 
# or whatever the command to run is

# docker run --name test [imagename] 
# if this causes it to exit straight away, there are other things to run

# if when you run an image, it immediately exits, such as when you run ....
# docker run {imagename}      OR       docker run --name {nameIwantToCallMyContainer} {imageName}
# then run the following instead, this should keep it running in the container.
# docker run -t -d --name nameIWantToCallContainer imageName
#
# then if you want to connect to the container.
# sudo docker exec -it mytest /bin/sh 
#  this will run the execution /bin/sh (a shell container) on that container.
#  You can also use /bin/bash if this is something supported by the os that was pulled down. 
