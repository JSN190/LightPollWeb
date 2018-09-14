# LightPoll Web
![Repository Size](https://img.shields.io/github/repo-size/JSN190/LightPollWeb.svg?t&style=flat-square)
![License](https://img.shields.io/github/license/JSN190/LightPollWeb.svg?&style=flat-square)
![Top Language](https://img.shields.io/github/languages/top/JSN190/LightPollWeb.svg?&style=flat-square)
![Website Uptime](https://img.shields.io/website-up-down-green-red/http/www.lightpoll.org.svg?label=lightpoll.org&style=flat-square)

LightPoll Web is the canonical frontend for the LightPoll web application which facilites rapid creation and distribution of online web polls.

It is written using the Vue.js framework, with JavaScript, SCSS, and Webpack being its main driving forces. Currently, LightPoll is a work in progress but the API is more or less near completion and the frontend is rapidly being developed.

![Create poll](https://i.imgur.com/0qZlqLj.png)

## Configuration

Before building the static files, ensure that you have all the required dependencies installed by running `npm init`. 

### Environment Variables

- `LPW_API`: The URL pointing to where your instance of the backend is installed.
- `LPW_URL` The URL pointing to where you will host LightPoll Web.
- `LPW_HIST`: Whether to enable (`1`) or disable (`0`) Vue Router history mode.

This project leverages [`vue init webpack`](https://github.com/vuejs-templates/webpack) for its Webpack configuration. To build using the `npm run build` script or to set parameters for development, use the `*.env.js` files in `/config`.

### Output

Webpack will build your static assets to the directory `/dist`. Everything needed to deploy to a production server will be available there.

## License

Released under the MIT License. Refer to [LICENSE.md](LICENSE.md) for more information.


