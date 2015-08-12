# hello-nodejs
Dockerize node.js application

Clone repository
  ```
  git clone https://github.com/MasashiTeruya/hello-nodejs.git && cd hello-nodejs
  ```

Build Docker Image
```
docker build -t hello-nodejs .
```

Run Node.js server
```
docker run -d -p=8080:1337 hello-nodejs
```

See http://localhost:8080/
