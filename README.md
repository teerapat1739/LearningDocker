## Install
```
  yarn
```

## Run with node
```
  node server.js
  # [localhost:3000](localhost:3000).
```

## Run with Docker
```
  * docker build -t sample-nodejs-app .
  * docker images
  # copy image that you want to run
  * docker run -p 80:3000 {image-id}
  # [localhost](localhost).
```