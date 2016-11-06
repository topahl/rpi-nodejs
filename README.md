# rpi-nodejs
Raspberry Pi compatible Docker base image with Node.js

Current Version of Node.js installed in this image is 4.4.5
Use this Image for in you Dokckerfile with:

```Dockerfile
FROM topahl/rpi-nodejs
```

or build the images yourself from the Dockerfile with:
```sh
git clone https://github.com/topahl/rpi-nodejs.git
docker build -t topahl/rpi-nodejs ./rpi-nodejs
```

##Supported Tags
Currently there are 2 supported Tags for your build
* latest
* node445
