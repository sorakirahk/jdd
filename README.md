### Docker Installation
Install docker and create a container:
```
docker run -dit \
  -v /Host/:/root 
  --name jd \
  --restart unless-stopped \
  evinedeng/jd-base:latest
```
### Physical machine installation
`git wget curl nodejs npm`：
```
## debian/ubuntu：
apt install -y git wget curl nodejs npm
## CentOS/RedHat/Fedora:
yum install git wget curl nodejs npm
```
### Clone js script
```
cd /root
git clone https://github.com/sorakirahk/jdd
sh shell/first_run.sh
```

### Modify info
- docker
```
cd /root/shell
cp git_pull.sh.sample git_pull.sh 
chmod +x *.sh                     
nano git_pull.sh                  
```
- physical machine
```
cd /home/myid/jd/shell
cp git_pull.sh.sample git_pull.sh 
chmod +x *.sh                     
nano git_pull.sh                  
```




  
