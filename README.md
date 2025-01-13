Redis demonstration via python using flask

to start the project run the following

in CMD or BASH

1. 
```bash
docker run -d --name redis-stack-server -p 6379:6379 redis/redis-stack-server:latest
```

FROM 
https://redis.io/docs/latest/operate/oss_and_stack/install/install-stack/docker/

2.
```bash
pip install -r requirements.txt
```

3.
```bash
python -m flask run
```


THEN GO TO http://localhost:5000
