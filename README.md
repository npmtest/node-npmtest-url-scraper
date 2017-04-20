# npmtest-url-scraper

#### basic test coverage for  [url-scraper (v1.0.2)](https://github.com/krishcdbry/url-scraper#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-url-scraper.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-url-scraper) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-url-scraper.svg)](https://travis-ci.org/npmtest/node-npmtest-url-scraper)

#### Url scraper which takes the text input and finds the links/urls, scraps them using cheerio and will returns an object with original text, parsed text (using npm-text-parser) and array of objects where each object contains scraped webpage's information.

[![NPM](https://nodei.co/npm/url-scraper.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/url-scraper)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-url-scraper/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-url-scraper/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-url-scraper/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-url-scraper/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-url-scraper/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-url-scraper/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-url-scraper/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-url-scraper/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-url-scraper/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-url-scraper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-url-scraper/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-url-scraper/build/test-report.html](https://npmtest.github.io/node-npmtest-url-scraper/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-url-scraper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-url-scraper/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-url-scraper/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-url-scraper/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-url-scraper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-url-scraper/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-url-scraper/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-url-scraper/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "url-scraper",
    "version": "1.0.2",
    "description": "Url scraper which takes the text input and finds the links/urls, scraps them using cheerio and will returns an object with original text, parsed text (using npm-text-parser) and array of objects where each object contains scraped webpage's information.",
    "main": "index.js",
    "scripts": {
        "test": "node index.js"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/krishcdbry/url-scraper.git"
    },
    "keywords": [
        "url",
        "scraper",
        "urlscrap",
        "webscraper",
        "webcrawler",
        "scrapping",
        "webcrawling",
        "bots",
        "urlscrapping",
        "scanner",
        "urlparser",
        "parse",
        "url",
        "web",
        "scrap",
        "url-scrapper",
        "web-bot",
        "scrapper"
    ],
    "author": "KrishCdbry",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/krishcdbry/url-scraper/issues"
    },
    "maintainers": [
        {
            "name": "krishcdbry"
        }
    ],
    "homepage": "https://github.com/krishcdbry/url-scraper#readme",
    "dependencies": {
        "async": "^2.0.1",
        "cheerio": "^0.22.0",
        "npm-text-parser": "^1.0.7",
        "request": "^2.74.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
