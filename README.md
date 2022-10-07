# bubblew_view_setup

## Initial Process
- Clone the repository locally
- Download the images mentioned in the "Readme.txt" file inside /img folder

## To run locally
- Install any server of your choice and run the server locally
- Actually developed using npm's "http-serve"


## Server installation
- Use the following command to install the server globally ( Assuminng that you already installed node.js)
```
npm install --global http-server
```
To start the index.html file on server use

```
http-server
```

- Refer [Original documentation](https://www.npmjs.com/package/http-server) for more info

## Task tutorial
- A progressbar with number of images left for processing
- Start by clicking the image 
* You can click any number of times
* A minimum of 15 clicks is required to move on to the next image

## Logging
- Each click, currentImage and Click count is recorded
- For now, they are stored in the console and can be downloaded after the completion of each tasks
- In future, an ajax approach is needed to update and store the log files

