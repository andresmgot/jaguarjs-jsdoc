Jaguar.js template for JSDoc 3

Forked from [davidshimjs's jaguarjs](http://davidshimjs.github.io/jaguarjs).

Use with [JSDoc3](https://github.com/jsdoc3/jsdoc).

Usage
---
1. If you want to create documentations with sample files, you can use commands below.
```
$ npm install
$ grunt demo
```

2. You can see any output related jsdoc process with a `--debug` flag.
```
$ grunt demo --debug
```

3. If you already have jsdoc system, you can use this project as jsdoc template.
```
$ jsdoc -t `project folder` -c `configuration file` `source files` `README.md file`
```

conf.json
---
You can set options for customizing your documentations.

```
"templates": {
    "applicationName": "Demo",
    "embedded": [{"path": "./tmp/otherdoc", "title": "NewCategorie", "subfolder": "newcategory", "includePattern": "^.*\\.html$", "excludePattern": "^.*/index.html$"}],
    "disqus": "",
    "googleAnalytics": "",
    "openGraph": {
        "title": "",
        "type": "website",
        "image": "",
        "site_name": "",
        "url": ""
    },
    "meta": {
        "title": "",
        "description": "",
        "keyword": ""
    },
    "linenums": true
}
```

License
---
This project under the MIT License. and this project refered by default template for JSDoc 3.
