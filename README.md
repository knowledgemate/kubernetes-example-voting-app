kubectl apply -f postgres-service.yml

https://hub.docker.com/r/dockersamples/examplevotingapp_vote

![image](https://user-images.githubusercontent.com/97225776/214862757-2cc7a3a4-08d4-4cd2-8e6e-981e6fabfb57.png)


Architecture
Architecture diagram

A front-end web app in Python which lets you vote between two options
A Redis which collects new votes
A .NET worker which consumes votes and stores them in…
A Postgres database backed by a Docker volume
A Node.js web app which shows the results of the voting in real time
