#Video Landing Page
This includes:
1. jQuery
2. Bootstrap
3. Font Awesome
4. Heroku Deployment Config

### Getting Started
------------------------
Clone the repo using the GUI or terminal. To do so in terminal, use the following:
```shell
git clone https://github.com/mqschwanda/video-landing-page.git
cd video-landing-page
```

From the `video-landing-page` directory, install the gems by running the following:
```shell
bundle install
```

To fire up the server while in the `video-landing-page` directory use this command:
```shell
middleman s
```

If you are having issues with livereload not working fire up the server using:
```shell
middleman s --force-polling --verbose
```

To kill the server use `ctrl+c`

### Deploying

Create a new app on heroku using heroku-cli. Pass in the following:
```shell
heroku create YOUR-APP-NAME
```

To deploy, commit all changes and pass in:
```shell
git push heroku master
```

To deploy a non-master branch use:
```shell
git push heroku MY-NEW-BRANCH:master
```
