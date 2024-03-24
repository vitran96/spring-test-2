# Spring test

## Generate project
```shell
sdk use java 11.0.11.amzn
sdk use springboot 2.5.0
sdk use maven 3.8.1

spring init -a springSpark -b 2.8.0.RELEASE --build maven -g com.example -j 1.8 -l java -n springSpark -p jar --package-name com.example.springSpark --description "Rest API" --format project -d "web,jpa,devtools,postgresql" temp.zip
```