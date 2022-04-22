# Express Demo

This project is a demo blocklet bootstrapped with [Express Generator](https://expressjs.com/en/starter/generator.html)

## Launch on Blocklet Server

[![Launch on Blocklet Server](https://assets.arcblock.io/icons/launch_on_blocklet_server.svg)](https://install.arcblock.io/?action=blocklet-install&meta_url=https%3A%2F%2Fgithub.com%2Fblocklet%2Fexpress-demo%2Freleases%2Fdownload%2Fv1.0.4%2Fblocklet.json)

## Run and debug in the cloud with Gitpod

Click the "Open in Gitpod" button, Gitpod will start Blocklet Server and the blocklet.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/blocklet/express-demo)

## Run and debug locally

```shell
yarn global add @blocklet/cli
git clone git@github.com:blocklet/express-demo.git
cd express-demo
npm install
blocklet server init --mode debug
blocklet server start
blocklet dev
```

## License

The code is licensed under the MIT license found in the
[LICENSE](LICENSE) file.
