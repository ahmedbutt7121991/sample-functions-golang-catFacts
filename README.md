# sample-functions-golang-catFacts
Random catFacts using DigitalOcean Cloud Functions

## Steps to Deploy in DO functions
* Fork the Repo
* doctl with serverless extension should be insatlled on the server: see the tutorial in the link below
* [How to install DOCTL](https://docs.digitalocean.com/reference/doctl/how-to/install/)
* Commands: 
```
doctl serverless connect
```
```
doctl serverless deploy . --remote-build
```
```
doctl serverless functions invoke ninja/catFacts
```
```
doctl serverless functions get ninja/catFacts --url
```
