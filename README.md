# Docker
```
docker-compose build
docker-compose up
docker exec -it react_develop_1 /bin/sh
```

# React
```
mkdir project
cd project
npx create-react-app . --template redux
npm start
```

# package

```
npm install axios
```

# tools
- ES7
- prettier Code format
- Redux DevTools

# 










```
sudo chown yuya:yuya /home/yuya/workspace/react-basic-drf/react-basic-drf -R
```

```
npm install axios
```

# Django

```
docker build -t django_image ./

docker run -it \
--rm \
--name django \
-v $HOME/workspace/react-basic-drf/:/usr/src/app/ \
-p 8000:8000 \
django_image \
/bin/bash

docker exec -it django /bin/bash

```

```
python manage.py runserver 0.0.0.0:8000
```
