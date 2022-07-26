# node-dockerapp
docker build .
docker scan

docker images - it will show all the  imgaes created 
after that select one image ID as per below command
docker run -p 3000:3000 46425da97d4b   
to remove one image :
docker rmi 46425da97d4b    
docker ps will show all the containers 
docker stop cranky_gagarin; 

 git remote add origin https://github.com/sreenivasvaluelabs/node-dockerapp.git
git remote -v  
git push -u origin master   


docker rm  $(docker ps -q -a)
the above will remove the stopped containers

atlast to see container stuff:
another terminal 
docker ps
docker ps - a
docker stop container id 

