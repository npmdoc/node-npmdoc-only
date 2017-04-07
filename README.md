# api documentation for  [only (v0.0.2)](https://github.com/visionmedia/node-only#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-only.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-only) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-only.svg)](https://travis-ci.org/npmdoc/node-npmdoc-only)
#### return whitelisted properties of an object

[![NPM](https://nodei.co/npm/only.png?downloads=true)](https://www.npmjs.com/package/only)

[![apidoc](https://npmdoc.github.io/node-npmdoc-only/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-only_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-only/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-only/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-only/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "TJ Holowaychuk",
        "email": "tj@vision-media.ca"
    },
    "bugs": {
        "url": "https://github.com/visionmedia/node-only/issues"
    },
    "dependencies": {},
    "description": "return whitelisted properties of an object",
    "devDependencies": {
        "mocha": "*",
        "should": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "2afde84d03e50b9a8edc444e30610a70295edfb4",
        "tarball": "https://registry.npmjs.org/only/-/only-0.0.2.tgz"
    },
    "homepage": "https://github.com/visionmedia/node-only#readme",
    "keywords": [
        "utility",
        "util",
        "object",
        "whitelist"
    ],
    "main": "index",
    "maintainers": [
        {
            "name": "tjholowaychuk",
            "email": "tj@vision-media.ca"
        }
    ],
    "name": "only",
    "optionalDependencies": {},
    "readme": "\n# only\n\n  Return whitelisted properties of an object.\n\n## Installation\n\n    $ npm install only\n\n## API\n\n An array or space-delimited string may be given:\n\n'''js\nvar obj = {\n  name: 'tobi',\n  last: 'holowaychuk',\n  email: 'tobi@learnboost.com',\n  _id: '12345'\n};\n\nvar user = only(obj, 'name last email');\n'''\n\nyields:\n\n'''js\n{\n  name: 'tobi',\n  last: 'holowaychuk',\n  email: 'tobi@learnboost.com'\n}\n'''\n\n## License \n\n(The MIT License)\n\nCopyright (c) 2012 TJ Holowaychuk &lt;tj@vision-media.ca&gt;\n\nPermission is hereby granted, free of charge, to any person obtaining\na copy of this software and associated documentation files (the\n'Software'), to deal in the Software without restriction, including\nwithout limitation the rights to use, copy, modify, merge, publish,\ndistribute, sublicense, and/or sell copies of the Software, and to\npermit persons to whom the Software is furnished to do so, subject to\nthe following conditions:\n\nThe above copyright notice and this permission notice shall be\nincluded in all copies or substantial portions of the Software.\n\nTHE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,\nEXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF\nMERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.\nIN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY\nCLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,\nTORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE\nSOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.",
    "readmeFilename": "Readme.md",
    "repository": {
        "type": "git",
        "url": "git://github.com/visionmedia/node-only.git"
    },
    "version": "0.0.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module only](#apidoc.module.only)



# <a name="apidoc.module.only"></a>[module only](#apidoc.module.only)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
