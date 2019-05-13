# [Storj Gateway](https://github.com/jschiarizzi/storj-ipfs-gateway)
An entrance IPFS storage with a [Storj](http://storj.io) implementation as a backend. This allows for easily viewing files stored in the Storj network directly in a web browser.

# Accessing this [Live Gateway](https://live.storjgateway.com) 

## Downloads / Views
We have 2 buckets that we made when we deployed our gateway, and some files stored in each one. The buckets and files exist within the Storj Network. You can access them

**myBucket**

| file | path |
| ----------- | ----------- |
| cat.png | https://live.storjgateway.com/ipfs/myBucket/cat.png |
<br>

**other-bucket**

| file | path |
| ----------- | ----------- |
| cat.png | https://live.storjgateway.com/ipfs/myBucket/cat.png |

### Uploads
You can add files to our buckets. This is just for testing and will be reset often. Please keep file sizes small.

Send a `POST` to `TBD` with your file to upload it. Then check that it is now in Storj with `Another thing`.

## Attribution
This experimental ipfs plugin combines code from and is heavily inspired by [RTrade's storj ipfs plugin](https://github.com/RTradeLtd/storj-ipfs-ds-plugin). It also uses code from https://github.com/ipfs/go-ds-s3 and https://github.com/storj/storj.

Special thanks to [RTrade](https://www.rtradetechnologies.com/) for supporting this project and inspiring the development direction it has taken so far.

## Usage of a Storj Gateway
Storj gives us the decentralized cloud storage, compatible with S3 buckets, through their service [Tardigrade](https://tardigrade.io/). This gateway acts as a web-based explorer for the files that are stored in Storj services like Tardigrade. The purpose of keeping this gateway running is to demonstrate how fast and easy storage is on IPFS systems like Storj.  We also provide instructions on using this project to setup your own gateway.

### Example Uses
After setting up your own gateway you could use it to create an online ebook store, with ebook files stored with Tardigrade. Or you could use a gateway like this to run a social art platform with persistent storage. A similar Storj Gateway is perfect for any online app where having especially fast downloads of large files and persistent storage is beneficial.  

## Development 
We're always building and working on this gateway! Check out our progress here: [https://github.com/jschiarizzi/storj-ipfs-gateway](https://github.com/jschiarizzi/storj-ipfs-gateway). Pull Requests and feature ideas welcome.


<br><br><br>
While development has been supported by Storj, this site is independently run and not a direct subsidiary of Storj. MIT Liscense on all its content. Please do not use our upload example in production, it will be reset. 
