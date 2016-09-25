# Docker Multi Apps on One Port

Demo showing set-up of Dockerized Web Application that has 2 components:

- static content: [/](http://localhost:8100/)
- app1: [/app1](http://localhost:8100/app1)
- app2: [/app2](http://localhost:8100/app2)

## Set-Up

### Pre-Requirements

[Docker](http://docker.com) installed


### How to run it locally

    docker-compose up


Open browser and navigate to: 

- `http://localhost:8100/` to access Static Content
- `http://localhost:8100/app1` to access App1 Dynamic Content
- `http://localhost:8100/app2` to access App2 Dynamic Content

## License

MIT
