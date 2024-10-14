https://github.com/web100Acress/100acressFront.git

https://github.com/web100Acress/backend.git

mongodb+srv://amit100acre:Amit123@cluster0.ffg8qyf.mongodb.net/?retryWrites=true&w=majority


sudo ./svc.sh install
sudo .svc.sh start    both cmd for ubuntu or docker start

sudo systemctl enable docker
sudo systemctl start/status docker    for docker run in ec2 



docker ps 
docker exec -it bc02e694fddf /bin/sh

to see all the folder 
cd /usr/share/nginx/html
ls -l
exit

to edit the config file 
docker ps
docker exec -it bc02e694fddf /bin/sh
vi /etc/nginx/nginx.conf  ? nano /etc/nginx/nginx.conf  error in docker case 


ls /etc/nginx/conf.d/
it will give default.conf
nano /etc/nginx/conf.d/default.conf

vi /etc/nginx/conf.d/default.conf
and for edit use vi
add this in editor file
try_files $uri $uri/ /index.html;



use esc to exit edit mode 
to save the file use :wq
hit enter

restart the docker container 
docker restart <container id >




