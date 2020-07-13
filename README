# Unload: A Static IPFS File Uploader

## Introduction

> Unload is a InterPlanetary File System (IPFS) hosted file uploader which uploads directly to an IPFS node of your choice.


## Installation

> Replace 'NODE' and 'PORT' to the values of your node. i.e.: <a href="https://infura.io" target="blank">Infura's node</a>. 

```javascript
   function upload() {
	       document.getElementById("loading").innerHTML = `<p>Uploading...<\/p>`
	     const reader = new FileReader();
	     reader.onloadend = function() {
	       const ipfs = window.IpfsApi('NODE', PORT) // Connect to IPFS
	       const buf = buffer.Buffer(reader.result) // Convert data into buffer
	       ipfs.files.add(buf, (err, result) => { // Upload buffer to IPFS
	          if(err) {
	           console.error(err)
	           return
	         } 
```
