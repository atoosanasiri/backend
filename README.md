# backend
Setup instructions and guidelines for backened

## setup mongoDB and compass for administratiopn ##
Install MongoDB Community Edition on Linux in [here](https://docs.mongodb.com/manual/administration/install-on-linux/)
Some useful instruction to work with mongoDB from shell:

1. Start MongoDB.
```bash
sudo service mongod start
sudo service mongod stop
```
2. Verify that MongoDB has started successfully
```bash
tail -5 /var/log/mongodb/mongod.log
[initandlisten] waiting for connections on port 27017
```
3. Restart MongoDB.
```bash
sudo service mongod restart
```
4. Begin using MongoDB.
```bash
mongo --host 127.0.0.1:27017
```
5. Run MongoDB Shell.
```bash
cd /usr
./bin/mongo
```
Install robomongo on Ubuntu, find instructions in [here](https://askubuntu.com/questions/739297/how-to-install-robomongo-on-ubuntu/781793)
Install Compass in [here](https://docs.mongodb.com/compass/master/install/)
1. Start Compass.
```bash
sudo DEBUG=* mongodb-compass;
```
How To Install and Configure Elasticsearch on Ubuntu 16.04, finf instruction in [here](https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-elasticsearch-on-ubuntu-16-04)
