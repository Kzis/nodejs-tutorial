# nodejs-tutorial
for knowledge sharing

app <br />
│   index.js        # Entry point for application  <br />
└───config          # Application environment variables and secrets  <br />
└───controllers     # Express controllers for routes, respond to client requests, call services  <br />
└───loaders         # Handles all startup processes  <br />
└───middlewares     # Operations that check or maniuplate request prior to controller utilizing  <br />
└───models          # Database models  <br />
└───routes          # Express routes that define API structure  <br />
└───services        # Encapsulates all business logic  <br />
└───test            # Tests go here  <br />

 ```
    docker-compose build

    docker-compose up -d nsp_backend

    docker-compose up -d nsp_db

```
