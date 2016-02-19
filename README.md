#SelfSSL
selfssl.sh is a shell one-liner to generate self-signed SSL certificate. The sole purpose of this is to forget the openssl syntax.

##Usage
Just grab the file anywhere and run it:
```
git clone https://github.com/bobac/selfssl.git
./selfssl.sh
```
...and fill in the certificate values. You will find the cert.pem and key.pem files in the current directory.

##Dependecies
Needs the openssl installed.
