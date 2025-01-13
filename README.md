Redis demonstration via python using flask

to start the project run the following

1. 
```
docker run -d --name redis-stack-server -p 6379:6379 redis/redis-stack-server:latest
```

FROM 
https://redis.io/docs/latest/operate/oss_and_stack/install/install-stack/docker/

2.
```
pip install -r requirements.txt
```

3.
```
python -m flask run
```


THEN GO TO http://localhost:5000
