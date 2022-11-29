# Python_chat_app

setup redis
```
curl -fsSL https://packages.redis.io/gpg | sudo gpg --dearmor -o /usr/share/keyrings/redis-archive-keyring.gpg  
echo "deb [signed-by=/usr/share/keyrings/redis-archive-keyring.gpg] https://packages.redis.io/deb $(lsb_release -cs) main" | sudo tee /etc/apt/sources.list.d/redis.list  
sudo apt-get update  
sudo apt-get install redis  
```   
test redis
```
redis-cli ping 
```
should respond as pong

To run
```
systemctl start/stop/status redis-server
```
