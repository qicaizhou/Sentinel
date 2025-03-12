# install json-server in Ubuntu 2404

# 1.Install Nodejs

```bash
sudo apt update
sudo curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
sudo apt install nodejs
```
Check nodejs version
```bash
node -v
```

# 2.Install NPM
```bash
sudo apt install npm
```
Check npm version
```bash
npm -v
```

# 3.Install JSON-Server
```bash
sudo npm install -g json-server

```
Check json-server version
```bash
json-server --version
```

Example
create a db.json file and type:

```json
{
  "users": [
    { "id": 1, "name": "John Doe" },
    { "id": 2, "name": "Jane Doe" }
  ],
  "posts": [
    { "id": 1, "title": "Hello World", "author": "John Doe" },
    { "id": 2, "title": "JSON Server Rocks", "author": "Jane Doe" }
  ]
}
```
start json-server
```bash
json-server --watch db.json
```



