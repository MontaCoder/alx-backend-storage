# :book: alx-backend-storage.

## :page_with_curl: Topics Covered.
1. MySQL advanced.
2. MongoDB NoSQL database.
3. Redis basic.


# :computer: Projects
## [0x00. MySQL advanced](0x00-MySQL_Advanced)

### :wrench: Project setup.
```bash
## Install MySQL 5.7 in ubuntu
# Create signature key

-----END PGP PUBLIC KEY BLOCK-----" >> signature.key

# Add key to server
sudo apt-key add signature.key

# Add apt repo
sudo sh -c 'echo "deb http://repo.mysql.com/apt/ubuntu bionic mysql-5.7" >> /etc/apt/sources.list.d/mysql.list'

sudo apt-get update

# Check mysql available versions
sudo apt-cache policy mysql-server

# Install mysql 5.7
sudo apt install -f mysql-client=5.7* mysql-community-server=5.7* mysql-server=5.7*

# Check if installed
mysql --version

# Create project directory and readme.
mkdir ./alx-backend-storage/
touch ./alx-backend-storage/README.md

cd alx-backend-storage

# Create git repository.
git init
git add .
git commit -m 'first commit'
git remote add origin <REMOTE_URL>
git push
```

```bash
# Create project directory and readme.
mkdir ./0x00-MySQL_Advanced/
touch ./0x00-MySQL_Advanced/README.md
cd 0x00-MySQL_Advanced
```

> [:point_right: Go to project](0x00-MySQL_Advanced)

## [0x01. NoSQL](0x01-NoSQL)

### :wrench: Project setup.
```bash
## Install MongoDB 4.2 in Ubuntu
wget -qO - https://www.mongodb.org/static/pgp/server-4.2.asc | apt-key add -
echo "deb [ arch=amd64,arm64 ] https://repo.mongodb.org/apt/ubuntu bionic/mongodb-org/4.2 multiverse" > /etc/apt/sources.list.d/mongodb-org-4.2.list
sudo apt-get update
sudo apt-get install -y mongodb-org
...
 sudo service mongod status
mongod start/running, process 3627
mongo --version
MongoDB shell version v4.2.8
git version: 43d25964249164d76d5e04dd6cf38f6111e21f5f
OpenSSL version: OpenSSL 1.1.1  11 Sep 2018
allocator: tcmalloc
modules: none
build environment:
    distmod: ubuntu1804
    distarch: x86_64
    target_arch: x86_64
 
pip3 install pymongo
python3
>>> import pymongo
>>> pymongo.__version__
'3.10.1'
```

```bash
# Create project directory and readme.
mkdir ./0x01-NoSQL/
touch ./0x01-NoSQL/README.md
cd 0x01-NoSQL
```

> [:point_right: Go to project](0x01-NoSQL)


## [0x02. Redis basic](0x02-redis_basic)
![Chnage my mind](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/1/40eab4627f1bea7dfe5e.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230118%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230118T122540Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=164275e7da0191ee3dc55f54aa8b546bd7ba59203ee71a281058a7e4e56c64c3)
### :wrench: Project setup.
```bash
## Install Redis on Ubuntu 18.04
$ sudo apt-get -y install redis-server
$ pip3 install redis
$ sed -i "s/bind .*/bind 127.0.0.1/g" /etc/redis/redis.conf
```

```bash
# Create project directory and readme.
mkdir ./0x02-redis_basic/
touch ./0x02-redis_basic/README.md
cd 0x02-redis_basic
```

> [:point_right: Go to project](0x02-redis_basic)
