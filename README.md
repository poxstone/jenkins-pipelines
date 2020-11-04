# jenkins-pipelines

- Tools for jenkins 2

## jenkins
```bash
java -jar "${HOME}/bin/jenkins/jenkins.war" --httpPort="9090" --httpListenAddress="0.0.0.0" --argumentsRealm.passwd.Administrator="MY_PASS" --prefix /proxy;
```

## ngrok
```bash
ngrok http 9090;
```

## localtunnel
```bash
npm install -g localtunnel;
lt --port 9090;
```

## Config webhook github
- 
- url: https://pink-ape-19.loca.lt/github-webhook/
- 
- Content-type: application/json