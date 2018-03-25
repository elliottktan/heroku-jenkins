# heroku-jenkins
Jenkins CI Server deployed to Heroku

## Update process
1. `docker build jenkins/jenkins .`
2. `docker rmi registry.heroku.com/morning-beach-65424/web`
3. `docker tag jenkins/jenkins:latest registry.heroku.com/morning-beach-65424/web`
4. `docker push registry.heroku.com/morning-beach-65424/web`

