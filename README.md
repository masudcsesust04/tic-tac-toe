# Tictactoe docker environment deployment / run

Tic tac toe game 

## ExpressJS backend API application

Clone repository:
```
$ git clone git@github.com:masudcsesust04/tictactoe-backend.git
```

Navigate to the coloned directory then run following command to build backend API application docker images:
```
$ bash build.sh
```

## ReactJS frontend application

Clone repository:
```
$ git clone git@github.com:masudcsesust04/tictactoe-frontend.git
```

Navigate to the coloned directory then run following command to build frontend application docker images: 
```
$ bash build.sh
```

## Run through docker-compose:

1. Clone repository:
```
$ git clone git@github.com:masudcsesust04/tictactoe-docker.git
```

2. Environment variable set:
- Update PostgreSQL db configuration to the file ```.env.pg``` as you need.
- Update expresJS backend API app configuration to the file ```.env.backend``` as you need. 

FYI, Keep database configuration both ```.env.pg``` and ```.env.backend``` same.

3. Up and running docker containers (Navigate to the cloned directory then run following command):

```
$ docker-compose up //Log trails mode
Or
$ docker-compose up -d // Detach mode
```

Open browser and enter url:
```
http://localhost:3000
```

### Thank you!

