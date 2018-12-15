# blockcert

## Install dependencies

Install dependencies by command **npm install** from root ditrectory of project

## Generate certificate
```
>node generate.js 
? Enter private key of issuier wallet==>  0x49043370f575051f4885823e58cd6605f2a0eed5ba751a1ebd351f7af78c6eee
Transaction hash, you need this to verify the certificate on blockchain::::0xd3e3afcc919d13d8e81bd4d1270af4567738ddffe5243a398d132e13423ab8b3
Certicate generated in Certicate folder

```
certificate is generated in folder **"certificate"**

In some cases Transaction hash, you need this to verify the certificate on blockchain::::undefined is show and error of ENOENT is given this is because node is not able to find the file in directory so add the file .

If it doesnt still work go ahead with verify certificate as ur certificate is already added so it will still show in the browser

## Verify certificate
```
node verify.js 
? Enter private key of issuier wallet==>  0xd3e3afcc919d13d8e81bd4d1270af4567738ddffe5243a398d132e13423ab8b3
```

It will open certificate on chrome
