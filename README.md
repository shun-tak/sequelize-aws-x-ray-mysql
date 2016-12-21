# sequelize-aws-x-ray-mysql

The `sequelize-aws-x-ray-mysql` module is a [`Sequelize`](http://sequelizejs.com/) extension for [AWS X-Ray](https://aws.amazon.com/xray/) to capture MySQL queries.

## Installation

```
npm install --save sequelize-aws-x-ray-mysql
```

## Usage

```
var Sequelize = require('sequelize');

var db = new Sequelize({
    dialect: 'mysql',
    dialectModulePath: 'sequelize-aws-x-ray-mysql',
});
```
