# Now Playing

Handpicked Albums by the Glitch Family


## Project setup

### Install hugo
[Install Documentation](https://gohugo.io/getting-started/installing/)

### Launch dev server

```
hugo server
```

### Build for production

```
hugo --baseURL $URL
```

As it `$URL` is an env variable but you can harcode it in the build command.


## Use NetlifyCMS backoffice in local mode

This website use [NetlifyCMS](https://www.netlifycms.org/) backoffice to manage albums easily.
And it's possible to use it while working in local:

### Install JS dependencies

```
npm i
```
of if you don't want to impact the package-lock
```
npm ci
```

### Run local API

While running [developement hugo server](#launch-dev-server) launch this command in another terminal:
```
node server
```

### Admin your website in local

Go to you website's local url + `/admin` (by default it's `http://localhost:1313/admin`). Enjoy!


## Credits
  * [Higgcss](https://github.com/robinparisi/higgcss) - The minimal CSS framework use as skeleton
  * Wryk for the help and support 💜
