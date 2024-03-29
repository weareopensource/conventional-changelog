[![npm](https://badges.weareopensource.me/npm/v/@weareopensource/conventional-changelog.svg?style=flat-square)](https://www.npmjs.com/package/@weareopensource/conventional-changelog) [![Build Status](https://badges.weareopensource.me/travis/weareopensource/conventional-changelog.svg?style=flat-square)](https://travis-ci.org/github/weareopensource/conventional-changelog) [![Code Climate](https://badges.weareopensource.me/codeclimate/maintainability-percentage/weareopensource/conventional-changelog.svg?style=flat-square)](https://codeclimate.com/github/weareopensource/conventional-changelog/maintainability)
 [![Dependabot badge](https://badges.weareopensource.me/badge/Dependabot-enabled-2768cf.svg?style=flat-square)](https://dependabot.com) [![Known Vulnerabilities](https://snyk.io/test/github/WeAreOpenSourceProjects/waos-conventional-changelog/badge.svg?style=flat-square)](https://snyk.io/test/github/WeAreOpenSourceProjects/waos-conventional-changelog)
 
# :globe_with_meridians: [WeAreOpenSource](https://weareopensource.me) Conventional Changelog

## :book: Presentation

Prompts for [conventional changelog](https://github.com/conventional-changelog/conventional-changelog) standard, based on [cz-conventional-changelog](https://github.com/commitizen/cz-conventional-changelog), which seems to be abandoned. For this reason, we decided to make our own package and included some PRs, switch to ES6 and add an Emoji system for some fun.

Our rules on this dev, **Quick** / **Simple** / **Lite**.

![gif](https://github.com/weareopensource/conventional-changelog/blob/master/assets/demo.gif)

Quick links :

* [Mindset and what we would like to create](https://weareopensource.me/)
* [How to start a project and maintain updates from stacks](https://blog.weareopensource.me/start-a-project-and-maintain-updates/)
* [Global roadmap and  ideas about stacks](https://github.com/orgs/weareopensource/projects/3)
* [How to contribute and help us](https://blog.weareopensource.me/how-to-contribute/)

## :boom: Installation

Make sure you have installed all of the following prerequisites on your development machine:

- Node.js (10.x) - [Download & Install Node.js](https://nodejs.org/en/download/)

Local : 

```bash
npm install --save-dev @weareopensource/conventional-changelog commitizen
commitizen init @weareopensource/conventional-changelog --save-dev --save-exact
```

### Integration 

We suggest to follow something like this : [How to create good commit messages](https://medium.com/@klauskpm/how-to-create-good-commit-messages-67943d30cced). Juste change cz-conventional-changelog part with @weareopensource/conventional-changelog

### Configuration

#### package.json

Like commitizen, you specify the configuration of cz-conventional-changelog through the package.json's `config.commitizen` key.

```json5
{
// ...  default values
    "config": {
        "commitizen": {      
            "path": "./node_modules/cz-conventional-changelog",
            "maxHeaderWidth": 100,
            "maxLineWidth": 100,
            "defaultType": "",
            "defaultScope": "",        
            "defaultSubject": "",
            "defaultBody": "",
            "defaultIssues": ""
        }
    }
// ...    
}
``` 
### Environment variables

The following environment varibles can be used to override any default configuration or package.json based configuration.

* CZ_TYPE = defaultType 
* CZ_SCOPE = defaultScope
* CZ_SUBJECT = defaultSubject
* CZ_BODY = defaultBody
* CZ_MAX_HEADER_WIDTH = maxHeaderWidth
* CZ_MAX_LINE_WIDTH = maxLineWidth

### Commitlint

If using the [commitlint](https://github.com/conventional-changelog/commitlint) js library, the "maxHeaderWidth" configuration property will default to the configuration of the "header-max-length" rule instead of the hard coded value of 100.  This can be ovewritten by setting the 'maxHeaderWidth' configuration in package.json or the CZ_MAX_HEADER_WIDTH environment variable.


## :pencil2: [Contribute](https://blog.weareopensource.me/how-to-contribute/)

## :globe_with_meridians: [We Are Open Source, Who we are ?](https://weareopensource.me)

Today, we dreams to create Backs/Fronts, aligns on feats, in multiple languages, in order to allow anyone to compose fullstack on demand (React, Angular, VusJS, Node, Nest, Swift, Go).
Feel free to discuss, share other kind of bricks, and invite whoever you want with this mindset to come help us.

Feel free to help us ! :)

## :clipboard: Licence

[![Packagist](https://badges.weareopensource.me/packagist/l/doctrine/orm.svg?style=flat-square)](/LICENSE.md)

## :link: Links

[![Blog](https://badges.weareopensource.me/badge/Read-our%20Blog-1abc9c.svg?style=flat-square)](https://blog.weareopensource.me) [![Slack](https://badges.weareopensource.me/badge/Chat-on%20our%20Slack-d0355b.svg?style=flat-square)](https://join.slack.com/t/weareopensource/shared_invite/zt-62p1qxna-PEQn289qx6mmHobzKW8QFw) [![Discord](https://badges.weareopensource.me/badge/Chat-on%20our%20Discord-516DB9.svg?style=flat-square)](https://discord.gg/U2a2vVm)  [![Mail](https://badges.weareopensource.me/badge/Contact-us%20by%20mail-00a8ff.svg?style=flat-square)](mailto:brisorgueilp@gmail.com?subject=Contact)
