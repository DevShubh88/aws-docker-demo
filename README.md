### aws-docker-demo
sudo apt update
git -v
git --version
git clone aws-docker-demo
ls
cd aws-docker-demo
sudo apt install docker.io
docker -v
ps -> no of processess running
sudo docker build -t amazonsales .
sudo docker ps -> find no of container running,also get container id no. 
sudo docker images -> check images uploaded or not and get images id no.
sudo docker run -d -p 8000:8000 amazonsales


