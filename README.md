![Deploy Website](https://github.com/MarkBroerkens/markbroerkens.github.io/workflows/Deploy%20Website/badge.svg)

This is the source of my Jekyll based website that is hosted on GitHub at broerkens.de

### How to Contribute
Github automatically updates the websites on each commit.

You can locally check if the page gets rendered correctly using:
```
bundle install
bundle exec jekyll serve
```

### Custom Domain
In order to use the custom domain 'broerkens.de' the following configurations are required:

* in the GitHub settings of this repository set `GitHub Pages / Custom Domain` to `broerkens.de`
* in the file [_config.yml](_config.yml) set `url:` to `http://broerkens.de`
* at your DNS provider configure an A record for `broerkens.de` that points to `185.199.108.153`
* at your DNS provider configure a `permanent redirect` from subdomain `www.broerkens.de` to `broerkens.de`

See also [Managing a custom domain for your GitHub Pages site](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/managing-a-custom-domain-for-your-github-pages-site).

### Credits
* [Artem Sheludko](http://artemsheludko.com) for the great Jekyll thema [zolan](https://github.com/artemsheludko/zolan).

### License

MIT License


