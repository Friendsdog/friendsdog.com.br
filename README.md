# [friendsdog.com.br](http://friendsdog.com.br)

## Quickstart

[Download](https://github.com/Friendsdog/friendsdog.com.br/archive/master.zip) or clone this repository and build:

```shell
git clone git@github.com:Friendsdog/friendsdog.com.br
cd friendsdog.com.br
npm i -g gulp
npm install
gulp serve
```

And finally, navigate to [http://localhost:3000](http://localhost:3000)

## Commands
#### Watch For Changes & Automatically Refresh Across Devices
```sh
gulp serve
# or
gulp serve:dist
```

This outputs an IP address you can use to locally test and another that can be used on devices connected to your network.

#### Build & Optimize
```sh
gulp
```
Build and optimize the current project, ready for deployment.

Publish the `dist` folder onto your production server.
