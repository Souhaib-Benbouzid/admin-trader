# Strapi Backend API with personal settings

### 1 - clone the repo

### 2- install dependencies

```
 cd backend && yarn
```

### 3- setup cloudinary & postgress in heruko

```
heroku addons:create heroku-postgresql:hobby-dev

heruko login

heroku git:remote -a your-heroku-app-name

heroku addons:create heroku-postgresql:hobby-dev

heroku config

git add .

git commit -m "Update database config"

git push heroku master

heroku open

heroku config:set DATABASE_USERNAME=

heroku config:set DATABASE_PASSWORD=

heroku config:set DATABASE_HOST=

heroku config:set DATABASE_PORT=

heroku config:set DATABASE_NAME=

heroku config:set CLOUDINARY_NAME=

heroku config:set CLOUDINARY_KEY=

heroku config:set CLOUDINARY_SECRET=

```

Project updates:

```

yarn develop

```

edit your content types

```
git add .
git commit -am "Changes to my-project noted"
git push heroku master
heroku open

```

### 4- api endpoint
