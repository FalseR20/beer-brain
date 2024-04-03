# BeerBrain 🍺🧠

This app will remind your drunken brain how much it owes.

You can even try it: [https://beerbrain.tech/](https://beerbrain.tech/)

## Installation

After cloning the repository update submodules:

```shell
git submodule update --init
```

Then make the copy of `.env` file:

```shell
cp example.env .env
```

It looks like:

```dotenv
# django
POSTGRES_HOST=postgres
POSTGRES_DB=beer_brain
POSTGRES_USER=beer_brain
POSTGRES_PASSWORD=!!!CHANGE_ME!!!

# vite
VITE_DJANGO_URL=http://0.0.0.0:8000/
```

Then you can run it all:

```shell
docker compose up -d --build
```

That's all!
Configure nginx yourself
<img src="roflan.png" style="width: 2rem;">

