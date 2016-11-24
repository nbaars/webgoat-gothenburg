# WebGoat workshop

## Download links for workshop:

[WebGoat 7.1](https://github.com/WebGoat/WebGoat/releases/download/7.1/webgoat-container-7.1-exec.jar)

[WebGoat 8.0-SNAPSHOT](https://github.com/nbaars/webgoat-gothenburg/releases/download/1.0/webgoat-container-8.0-SNAPSHOT.war)

[ZAP](https://github.com/zaproxy/zaproxy/wiki/Downloads)

## Start

### WebGoat 7.1
```
java -jar webgoat-container-7.1-exec.jar -httpPort 7777
```

In the browser use the following URL: <http://localhost:7777/WebGoat>

### WebGoat 8.0

```
java -jar webgoat-container-8.0-SNAPSHOT.war
```

In the browser use the following URL: <http://localhost:8080/WebGoat>


## Exercises

### Http Basics

Use the following URL <http://localhost:8080/WebGoat/start.mvc#lesson/HttpBasics.lesson>

### SQL Injection

For WebGoat 8 first use the following link: http://localhost:8080/WebGoat/start.mvc#lesson/SqlInjection.lesson

| WebGoat 8     | WebGoat 7        
| --- |---
|[String SQL Injection](http://localhost:8080/WebGoat/start.mvc#lesson/SqlInjection.lesson/6)|[String SQL Injection](http://localhost:7777/WebGoat/start.mvc#attack/538385464/1100)
|[Data from other tables](http://localhost:8080/WebGoat/start.mvc#lesson/SqlInjection.lesson/9) | [Blind numeric SQL injection](http://localhost:7777/WebGoat/start.mvc#attack/586116895/1100)
| | [Blind String SQL injection](http://localhost:7777/WebGoat/start.mvc#attack/1315528047/1100)
| | [LAB: SQL Injection](http://localhost:7777/WebGoat/start.mvc#attack/1537271095/1100)

### XXE

First go to <http://localhost:8080/WebGoat/start.mvc#lesson/XXE.lesson> then use links below

| WebGoat 8 
| ---
| [Simple XXE](http://localhost:8080/WebGoat/start.mvc#lesson/XXE.lesson/2)
| [Modern REST frameworks](http://localhost:8080/WebGoat/start.mvc#lesson/XXE.lesson/3)
| [Blind XXE](http://localhost:8080/WebGoat/start.mvc#lesson/XXE.lesson/6)

### XSS

| WebGoat 7
| ---
| [Reflected XSS attack](http://localhost:7777/WebGoat/start.mvc#attack/1406352188/900)
| [Stored XSS](http://localhost:7777/WebGoat/start.mvc#attack/598569451/900)
| [Phishing with XSS](http://localhost:8080/WebGoat/start.mvc?#attack/1382523204/900)
| [LAB: Cross Site Scripting](http://localhost:7777/WebGoat/start.mvc#attack/611366032/900)
| [Dangerous Use of Eval](http://localhost:7777/WebGoat/start.mvc#attack/136634854/400)

### Client side filtering

WebGoat 8, <http://localhost:8080/WebGoat/ClientSideFiltering.lesson>

### Up for a challenge?

Go to <http://localhost:7777/WebGoat/start.mvc#attack/162777743/3000>

### Defend?
Try to fix the lessons and see if it fixes the vulnerability.

### Create new lessons

#### Extend SQL injection with order by injection
#### Encryption lessons, ECB, CBC with fixed IV etc.
#### Java deserialization vulnerabilities
#### JavaMail SMTP Header Injection via method
#### JWT Tokens (bugs in libraries for changing the algorithm, adjusting the token etc etc)
#### etc.






