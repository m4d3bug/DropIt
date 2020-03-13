# DropIt

<p align="center">
  <img width="150" height="150" src="https://github.com/ThalKod/DropIt/blob/master/public/img/logo.png"> </br>
  DropIt is a File Uploader built with nodejs
</p>

![alt text](https://github.com/ThalKod/DropIt/blob/master/public/img/Screen%20Shot%202018-06-08%20at%2010.36.39%20AM.png)

[Demo](http://dropit.thal.tech/)

# :floppy_disk: Installation

```bash
# clone the repo
$ git clone https://github.com/ThalKod/DropIt.git

# install the node modules...
$ npm install
```

## Usage
```bash
npm start
```

### Working with your own DB ? modify config.js :
```javascript
module.exports = {
    dbURL: process.env.DATABASEURL || "mongodb://localhost/dropit"
}
```

### :whale: Docker Usage

Preparation:

1. Rename `docker-compose.yml.example` to `docker-compose.yml`
2. Rename `.env.example` to `.env`
3. Fill in the missing details in `.env` file
4. Change the max upload in Droplt/public/js/main.js
5. Change the max upload display in Droplt/view/index.ejs

Boot:
```bash
docker-compose up -d
```
