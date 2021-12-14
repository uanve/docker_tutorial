# this is a docker tutorial

this is a docker tutorial

CMD
change directory C to G
cd /d G:\My Drive\code\docker_tutorial

docker build -t docker_tutorial
docker image ls
docker run docker_tutorial

docker run -it ubuntu
#ubuntu is not local but is in docker database

apt update
apt install nano
nano
pwd #print working directory
cd .. #go back
mkdir docker #create directory
ls -1 #list
ls -l #detailed list
touch file1.txt file2.txt
rm file* #remove all files starting by file
mv file1.txt docker.txt #change file name
cd ..
rm -r docker #remove directory