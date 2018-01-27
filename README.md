<!---Copyright 2017 Nirmal Kumar--->

<!---This file is part of LibreRead.--->

<!---LibreRead is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.--->

<!---LibreRead is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.--->

<!---You should have received a copy of the GNU Affero General Public License
along with LibreRead.  If not, see <http://www.gnu.org/licenses/>.--->

# LibreRead  [![Build Status](https://api.travis-ci.org/LibreRead/server.svg?branch=master)](https://travis-ci.org/LibreRead/server) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com) [![Chat](https://img.shields.io/badge/chat-Rocket.Chat-red.svg)](https://chat.libreread.org) [![PayPal Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.me/paynirmal) [![Become a Patron](https://img.shields.io/badge/Patron-Patreon-red.svg)](https://www.patreon.com/mysticmode) [![Backers on Open Collective](https://opencollective.com/libreread/backers/badge.svg)](#backers) [![Sponsors on Open Collective](https://opencollective.com/libreread/sponsors/badge.svg)](#sponsors)

Self-hosted Free(Libre) Ebook Reader. https://libreread.org

![Alt text](/static/img/screenshot.png?raw=true "Home Page")

### Features
 - Easy installation
 - Built using Golang
 - Browser-based
 - Responsive design
 - Full-text search
 - Highlight & Annotate
 - Supports PDF & EPUB
 
### Production setup
Please check [this guide](https://github.com/LibreRead/server/blob/master/docs/INSTALL.md)

### Development setup
Install go 1.9, redis 4 (default settings on port 6379) and optionally elasticsearch 5 (default settings on port 9200). If you want to use elasticsearch, do `export LIBREREAD_ELASTICSEARCH=1` and run the following commands.
 - `go get -d github.com/LibreRead/server/cmd/libreread`
 - `cd $GOPATH/src/github.com/LibreRead/server`
 - `go run ./cmd/libreread/main.go`
 
 This will run the app on `localhost:8080`

### Supported by
<img src="https://www.digitalocean.com/assets/media/logos-badges/png/DO_Logo_Horizontal_Black-a93a7c21.png" height="40px" alt="Supported by Digital Ocean" />

If you find LibreRead useful, you could support our development by either making an [one-time donation](https://www.paypal.me/paynirmal) or by [becoming a patron](https://www.patreon.com/mysticmode). Thank you! 😍

#### Contributors

This project exists thanks to all the people who contribute. [[Contribute](CONTRIBUTING.md)].
<a href="graphs/contributors"><img src="https://opencollective.com/libreread/contributors.svg?width=890" /></a>


#### Backers

Thank you to all our backers! 🙏 [[Become a backer](https://opencollective.com/libreread#backer)]

<a href="https://opencollective.com/libreread#backers" target="_blank"><img src="https://opencollective.com/libreread/backers.svg?width=890"></a>


#### Sponsors

Support this project by becoming a sponsor. Your logo will show up here with a link to your website. [[Become a sponsor](https://opencollective.com/libreread#sponsor)]

<a href="https://opencollective.com/libreread/sponsor/0/website" target="_blank"><img src="https://opencollective.com/libreread/sponsor/0/avatar.svg"></a>
<a href="https://opencollective.com/libreread/sponsor/1/website" target="_blank"><img src="https://opencollective.com/libreread/sponsor/1/avatar.svg"></a>
<a href="https://opencollective.com/libreread/sponsor/2/website" target="_blank"><img src="https://opencollective.com/libreread/sponsor/2/avatar.svg"></a>
<a href="https://opencollective.com/libreread/sponsor/3/website" target="_blank"><img src="https://opencollective.com/libreread/sponsor/3/avatar.svg"></a>
<a href="https://opencollective.com/libreread/sponsor/4/website" target="_blank"><img src="https://opencollective.com/libreread/sponsor/4/avatar.svg"></a>
<a href="https://opencollective.com/libreread/sponsor/5/website" target="_blank"><img src="https://opencollective.com/libreread/sponsor/5/avatar.svg"></a>
<a href="https://opencollective.com/libreread/sponsor/6/website" target="_blank"><img src="https://opencollective.com/libreread/sponsor/6/avatar.svg"></a>
<a href="https://opencollective.com/libreread/sponsor/7/website" target="_blank"><img src="https://opencollective.com/libreread/sponsor/7/avatar.svg"></a>
<a href="https://opencollective.com/libreread/sponsor/8/website" target="_blank"><img src="https://opencollective.com/libreread/sponsor/8/avatar.svg"></a>
<a href="https://opencollective.com/libreread/sponsor/9/website" target="_blank"><img src="https://opencollective.com/libreread/sponsor/9/avatar.svg"></a>


