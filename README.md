
sudo apt update
sudo apt install docker.io

sudo su - 
usermod -aG docker jenkins
usermod -aG docker ubuntu
systemctl restart docker

executed this commands : ssh -i ~/Downloads/mykp.pem ubuntu@174.129.67.83

chmod 600 ~/Downloads/mykp.pem

ssh -i ~/Downloads/mykp.pem ubuntu@174.129.67.83
