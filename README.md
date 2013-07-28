Maps urls to simplified strings usable as filenames
==
[![Build Status](https://travis-ci.org/ogt/slugify-url.png)](https://travis-ci.org/ogt/slugify-url)

## Synopsis

slugify-url maps urls to a sanitized string that can be used as a filename and serves as a good mnemonic of the original url even though it is not reversible


#Description

 - It skips the protocol and user/password if provided part from the URL (http:// or https:// or <protocol>://<user>:<password>@ )
 - It maps slashes to !
 - It truncates the URL to 100 chars
 - It includes an optional options argument that allows the user to override the behavior
   + slashchar char used to replace slashes - default !
   + maxlength default 100
   + skipprotocol default true
   + skipuserpass default true


## Installation 

```
npm install slugify-url
```
