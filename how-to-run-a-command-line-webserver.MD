# How to run a command line webserver

 

- [Python](#python)

- [NodeJS](#nodejs)

 

### Python

Minimum requirement: `Python 2`

 

In the directory you want to serve html from run this command in the terminal

 

**Python 2.7** - `python -m SimpleHTTPServer 8444`

 

**Python 3.3** - `python3 -m http.server`

 

Change `8444` to whatever port you want the server to run on

 

### NodeJS

 

Minimum requirement: `Node v0.11.1`

 

Install [http-server](https://www.npmjs.com/package/http-server) globally

 

`npm install http-server -g`

 

In the directory you want to serve html from run this command in the terminal

 

`http-server ./ 8444`

 

Change `8444` to whatever port you want the server to run on. More [options](https://github.com/indexzero/http-server#available-options) can be added to the command

 