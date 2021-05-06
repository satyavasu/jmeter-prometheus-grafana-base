# jmeter-prometheus-grafana-base

Prometheus &amp; Grafana setup ready for JMeter

## Start the both services.

```docker-compose up -d```

```docker ps```

```docker stop prometheus```

## Kill the containers

```docker-compose down```

## Check Prometheus

http://localhost:9270/metrics

![Alt text](docs/img_4.png)

http://localhost:9090/graph

![Alt text](docs/img_5.png)


## Check Grafana dashboard

http://localhost:3000/

_username/password_: "admin / admin"

![Alt text](docs/img.png)  
![Alt text](docs/img_1.png)
![Alt text](docs/img_2.png)
![Alt text](docs/img_3.png)

## Other repo

[jmeter-prometheus-example](https://github.com/beemi/jmeter-prometheus-example)

## :postbox: Contacts

Owner: [beemi.raja@gmail.com](beemi.raja@gmail.com)
