# Online Collaboration and Judge System

## Installation
1. Install NodeJs:
```
sudo apt-get update
curl -sL https://deb.nodesource.com/setup_7.x | sudo -E bash -
sudo apt-get install -y nodejs
```
 
2. Install Nodemon

```
npm install -g nodemon
```

3. Install git
```
sudo apt-get install git
```

4. Install angular/cli
```
    npm install -g @angular/cli
```

5. Install Redis
```
    wget http://download.redis.io/releases/redis-3.2.6.tar.gz
    tar xzf redis-3.2.6.tar.gz
    cd redis-3.2.6
    make
    sudo make install
    cd utils
    sudo ./install_server.sh
```

6. Install python 2.7  
This is installed already in Ubuntu

7. Install pip
```
    (sudo apt-get update)
    sudo apt install python-pip
    sudo pip install Flask
```

8. Install Docker: 
```
    curl -fsSL https://get.docker.com/ | sh
```

9. Setup docker permission: 
```
   sudo usermod -aG docker $(whoami)
   # need to logout and login again after set permission
   To start docker when the system boots: sudo systemctl enable docker
```

10. Install Nginx  
   For ubuntu 16.04) Add following two lines into /etc/apt/sources.list 
```
   deb http://nginx.org/packages/ubuntu/ xenial nginx 
   deb-src http://nginx.org/packages/ubuntu/ xenial nginx 
``` 
   Then run: 
```
   sudo apt-get update 
   sudo apt-get install nginx
```