I usually use 2 networks with all my docker's recipe
One for frontend and one for backend.

So, before to load any of my recipes, you have to change the name of networks or use mine.
I created my networks like this:

For backend:
```
sudo docker network create backend --internal
```

For frontend:
```
sudo docker network create frontend
```
