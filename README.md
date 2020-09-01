# docker-cheatsheet
This repo for common docker commands to help me memorize it quickly 


* run docker container 
  * docker run -d --name container-name -p hostportnum:containerportnum -t imageName nginx -g 'daemon off;'
 
option | usage
----- | -------------
-d | run in detached mode (background)
-p | specify ports first one is the host port , second is the container port
-t | allocate tty
nginx -g 'daemon off;'| to start nginx service without issues 
