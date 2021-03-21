# SQL

A simple SQL injection protection module that allows you to use ES6 template strings for escaped statements. Works with [pg](https://www.npmjs.com/package/pg), [mysql](https://www.npmjs.com/package/mysql) and [mysql2](https://www.npmjs.com/package/mysql2) library.

[![npm version][1]][2] [![build status][3]][4] [![js-standard-style][5]][6]

1. [Install](#install)
2. [Usage](#usage)
   1. [Linting](#linting)
3. [Methods](#methods)
   1. [append](#appendstatement)
   2. [glue](#gluepieces-separator)
4. [How it works?](#how-it-works)
5. [Undefined values and nullable fields](#undefined-values-and-nullable-fields)
6. [Testing, linting, & coverage](#testing-linting--coverage)
7. [Benchmark](#benchmark)
8. [License](#license)

## Install

```bash
npm install @nearform/sql
```
