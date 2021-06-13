# CI/CD for deployment Hello.txt application on Docker


# Preparing AWS IAM Credential


Get Access key ID,Secret access key for accessing AWS 

![](https://s2.im.ge/2021/06/13/QD5cJ.png)

Download .csv file and store on your safe storage.


# Preparing Environment Variable

![](https://s2.im.ge/2021/06/13/QDwCz.png)

List : 

- AWS_ECR_URL 

Input with your elastic container registry url.
 Example value :
```
898xxxxxxxxx.dkr.ecr.ap-southeast-1.amazonaws.com/testing
```

- AWS_ACCESS_KEY

Input with your aws access key id. Example value :
```
AKIA5CHGDFVXXXXXXX
```
- AWS_SECRET_ACCESS_KEY

Input with your aws secret access key.
Example value :
```
0bTzX6hOFuxxxxxxxxxxxxxxxxxxx
```
- SSH_PRIVATE_KEY_DEV and SSH_PRIVATE_KEY_PROD 

Input ssh private key of server each environment. Example value:
```
-----BEGIN OPENSSH PRIVATE KEY-----
xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
vw2Im9K/DvfmePKRIdWarB6IAidrm/YwQwWJ58t6xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
49CJXQN5DMLv+R2tRbT5qrmudUvHKt9TdtUCEvaFHsjxo2xZ4awNzxsWHiJfdQqPcJPXYo
xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
nnzhkR2xpJ1t0WcufCSnu91Jn45T3WyuoZWs7DaXxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
T9LRm8F92Kw0iKfBZ0m87aw1v08EVi1/veRvn4O1
xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
-----END OPENSSH PRIVATE KEY-----
```

- DEVELOPMENT_SERVER_USERNAME and PRODUCTION_SERVER_USERNAME

Input username of server each environment. Example value:
```
ubuntu
```
- DEVELOPMENT_SERVER_IP and PRODUCTION_SERVER_IP 
Input IP Address of server each environment. Example value:
```
52.52.52.52
```

- PORT 
Input with listen PORT. Example value:
```
80:80/tcp
```


