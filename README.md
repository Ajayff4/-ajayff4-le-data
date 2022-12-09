<div align="center">
  <img src="./docs/public/logo.svg" width="200" alt="Logo"/>
  <h1>Le-data</h1>
  <p>Generates placeholder data for testing and development. Made with indian touch in it.</p>

  <img alt="Downloads" src="https://img.shields.io/npm/dw/@ajayff4/le-data" />
  <img alt="Code Size" src="https://img.shields.io/github/languages/code-size/ajayff4/-ajayff4-le-data" />
  <img alt="Health Score" src="https://snyk.io/advisor/npm-package/@ajayff4/le-data/badge.svg" />
  <img alt="Activity" src="https://img.shields.io/github/commit-activity/w/ajayff4/-ajayff4-le-data" />
  <img alt="Github License" src="https://img.shields.io/github/license/ajayff4/-ajayff4-le-data" />
  
  [![@ajayff4/le-data Versions](https://badges.openbase.com/js/versions/@ajayff4/le-data.svg?token=6ZsB1PXI74de3lWHOo1V/BKAnawwBhBbxXk2l4GrnLE=)](https://openbase.com/js/@ajayff4/le-data?utm_source=embedded&amp;utm_medium=badge&amp;utm_campaign=rate-badge)]
</div>

## 🚀 Features

- 🧍 - Generate random person with an Indian identity.
- 🙏 - Data generated by this package is Indian origin based. Soon international data will be included too.


## 📦 Install

```bash
npm install -D @ajayff4/le-data
or
yarn add -D @ajayff4/le-data
```

## 🪄 Usage

```ts
import { ldt } from "@ajayff4/le-data";
// or
const ldt = require("@ajayff4/le-data").default;


console.log("int:", ldt.number.int()); // int: -1161972571
console.log("int:", ldt.number.int({max:100})); // int : -2095377662
console.log("int:", ldt.number.int({min:0, max:100})); // int : 35

console.log("seed:", ldt.utils.seed()); // seed: orz3lKJg6m
console.log("seed:", ldt.utils.seed(21)); // seed: 2yGIVAtxWJPGualh62kK5
console.log("slug:", ldt.utils.slug('I am @ajayff4/le-data')); // slug: i-am-ajayff4ledata

console.log("age:", ldt.person.age()); // age: 57
console.log("age:", ldt.person.age({min:18})); // age: 57
console.log("age:", ldt.person.age({min:18, max:60})); // age: 33
console.log("firstname:", ldt.person.firstName()); // firstname: Laxmi
console.log("firstname:", ldt.person.firstName({sex:'female'})); // firstname: Sarika
console.log("middlename:", ldt.person.middleName()); // middlename: Kumar
console.log("lastname:", ldt.person.lastName()); // lastname: Ahluwalia
console.log("fullname:", ldt.person.fullName()); // fullname: Sahadev Agarwal
console.log("fullname:", ldt.person.fullName({middle:true})); // fullname: Sherry Kumar Ahuja
console.log("gender:", ldt.person.gender()); // gender: female
console.log("gender:", ldt.person.gender({binary:false})); // gender: xenogender
```

## 💎 Modules

The API covers the following modules:

| Module   | Example                   | Output                                           |
| -------- | --------------------------|--------------------------------------------------|
| Card     | `ldt.card.info()`         | Card module will be available soon!              |
| Color    | `ldt.color.info()`        | Color module will be available soon!             |
| Id       | `ldt.id.info()`           | Id module will be available soon!                |
| Location | `ldt.location.info()`     | Location module will be available soon!          |
| Number   | `ldt.number.int()`        | 56                                               |
| Person   | `ldt.person.fullName()`   | Ajay Agrawal                                     |
| Product  | `ldt.product.info()`      | Product module will be available soon!           |
| String   | `ldt.string.info()`       | String module will be available soon!            |
| Utils    | `ldt.utils.seed(21)`      | xayaW9LU0ncPdW1JJtuOn                            |
                                                    
## 🛤️ Roadmap - Plans ahead
  - demo setup will be added
  - JSDocs will be added
  - unit tests will be added
  - documentation page will be released
  - introduced factories need to be completed

## 📝 Changelog

Detailed changes for each release are documented in the [release notes](https://github.com/Ajayff4/-ajayff4-le-data/blob/main/CHANGELOG.md).


## 🔑 License

[MIT](https://github.com/Ajayff4/-ajayff4-le-data/blob/main/LICENSE)
