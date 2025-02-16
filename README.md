<p align="center">
<img src=".github/woot-logo.svg" alt="Woo-logo" width="240">

<div align="center">Opensource alternative to Intercom, Zendesk, Drift, Crisp etc.</div>
</p>

___

![CircleCI Badge](https://img.shields.io/circleci/build/github/chatwoot/chatwoot)
![Dependencies](https://img.shields.io/david/chatwoot/chatwoot)
![Github Issues](https://img.shields.io/github/issues/chatwoot/chatwoot)
![License](https://img.shields.io/github/license/chatwoot/chatwoot)
[![Maintainability](https://api.codeclimate.com/v1/badges/80f9e1a7c72d186289ad/maintainability)](https://codeclimate.com/github/chatwoot/chatwoot/maintainability)
![Commits-per-month](https://img.shields.io/github/commit-activity/m/chatwoot/chatwoot)

![ChatUI progess](https://chatwoot.com/images/dashboard-screen.png)

## Quick Setup


### Install JS dependencies

``` bash
yarn install
```

### Install ImageMagik

```bash
brew install imagemagick
```

### Setup rails server

```bash
# install ruby dependencies
bundle

# copy config
cp shared/config/database.yml config/database.yml
cp shared/config/application.yml config/application.yml

# copy frontend env file
cp .env.sample .env

# run db migrations
bundle exec rake db:create
bundle exec rake db:reset

# fireup the server
foreman start -f Procfile.dev
```

### Login with credentials

```bash
http://localhost:3000
user name: larry@google.com
password: 123456
```

### Detailed documentation

Detailed documentation is available at [docs.chatwoot.com](https://docs.chatwoot.com) 

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
<table>
  <tr>
    <td align="center"><a href="http://nithindavid.me"><img src="https://avatars2.githubusercontent.com/u/1277421?v=4" width="100px;" alt="Nithin David Thomas"/><br /><sub><b>Nithin David Thomas</b></sub></a><br /><a href="https://github.com/chatwoot/chatwoot/issues?q=author%3Anithindavid" title="Bug reports">🐛</a> <a href="#blog-nithindavid" title="Blogposts">📝</a> <a href="https://github.com/chatwoot/chatwoot/commits?author=nithindavid" title="Code">💻</a> <a href="https://github.com/chatwoot/chatwoot/commits?author=nithindavid" title="Documentation">📖</a> <a href="#design-nithindavid" title="Design">🎨</a> <a href="#maintenance-nithindavid" title="Maintenance">🚧</a> <a href="#review-nithindavid" title="Reviewed Pull Requests">👀</a></td>
    <td align="center"><a href="https://github.com/pranavrajs"><img src="https://avatars3.githubusercontent.com/u/2246121?v=4" width="100px;" alt="Pranav Raj S"/><br /><sub><b>Pranav Raj S</b></sub></a><br /><a href="https://github.com/chatwoot/chatwoot/issues?q=author%3Apranavrajs" title="Bug reports">🐛</a> <a href="#blog-pranavrajs" title="Blogposts">📝</a> <a href="https://github.com/chatwoot/chatwoot/commits?author=pranavrajs" title="Code">💻</a> <a href="https://github.com/chatwoot/chatwoot/commits?author=pranavrajs" title="Documentation">📖</a> <a href="#design-pranavrajs" title="Design">🎨</a> <a href="#maintenance-pranavrajs" title="Maintenance">🚧</a> <a href="#review-pranavrajs" title="Reviewed Pull Requests">👀</a></td>
    <td align="center"><a href="http://www.linkedin.com/in/subintp"><img src="https://avatars1.githubusercontent.com/u/1742357?v=4" width="100px;" alt="Subin T P"/><br /><sub><b>Subin T P</b></sub></a><br /><a href="https://github.com/chatwoot/chatwoot/issues?q=author%3Asubintp" title="Bug reports">🐛</a> <a href="https://github.com/chatwoot/chatwoot/commits?author=subintp" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/manojmj92"><img src="https://avatars1.githubusercontent.com/u/4034241?v=4" width="100px;" alt="Manoj M J"/><br /><sub><b>Manoj M J</b></sub></a><br /><a href="https://github.com/chatwoot/chatwoot/issues?q=author%3Amanojmj92" title="Bug reports">🐛</a> <a href="https://github.com/chatwoot/chatwoot/commits?author=manojmj92" title="Code">💻</a> <a href="#review-manojmj92" title="Reviewed Pull Requests">👀</a></td>
    <td align="center"><a href="http://sojan.me"><img src="https://avatars1.githubusercontent.com/u/73185?v=4" width="100px;" alt="Sojan Jose"/><br /><sub><b>Sojan Jose</b></sub></a><br /><a href="https://github.com/chatwoot/chatwoot/issues?q=author%3Asojan-official" title="Bug reports">🐛</a> <a href="#blog-sojan-official" title="Blogposts">📝</a> <a href="https://github.com/chatwoot/chatwoot/commits?author=sojan-official" title="Code">💻</a> <a href="https://github.com/chatwoot/chatwoot/commits?author=sojan-official" title="Documentation">📖</a> <a href="#design-sojan-official" title="Design">🎨</a> <a href="#maintenance-sojan-official" title="Maintenance">🚧</a> <a href="#review-sojan-official" title="Reviewed Pull Requests">👀</a></td>
  </tr>
</table>

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!



*Chatwoot* &copy; 2017-2019, ThoughtWoot Inc - Released under the MIT License.
