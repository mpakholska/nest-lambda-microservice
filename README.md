# @nest-lambda-microservice

A microservice application built with NestJS for AWS Lambda.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
  - [Scripts](#scripts)
- [Development](#development)
  - [Linting and Formatting](#linting-and-formatting)
  - [Testing](#testing)
- [Dependencies](#dependencies)

## Introduction

`@nest-lambda-microservice` is a microservice boilerplate using NestJS framework, optimized for serverless environments with AWS Lambda integration.

## Installation

Clone the repository and install dependencies:

```bash
$ git clone <repository-url>
$ cd @nest-lambda-microservice
$ yarn install
```

## Usage

### Scripts

| Command             | Description                                                    |
|---------------------|----------------------------------------------------------------|
| `yarn build`        | Cleans and compiles the TypeScript files to the `dist` folder. |
| `yarn build:clean`  | Removes the `dist` folder.                                     |
| `yarn build:ts`     | Compiles the TypeScript files to the `dist` folder.            |
| `yarn build:watch`  | Compiles TypeScript files in watch mode.                      |
| `yarn lint`         | Lints and formats the codebase.                                |
| `yarn test`         | Runs both unit and integration tests.                         |
| `yarn test:unit`    | Runs unit tests.                                               |
| `yarn test:integration` | Runs integration tests.                                     |
| `yarn prettier`     | Checks for prettier issues.                                    |
| `yarn prettier:fix` | Fixes prettier issues.                                         |

## Development

### Linting and Formatting

To ensure code consistency, run the following:

```bash
$ yarn lint
```

### Testing

Run tests using Jest:

```bash
# Run all tests
$ yarn test

# Run unit tests
$ yarn test:unit

# Run integration tests
$ yarn test:integration
```

## Dependencies

### Production

- `@nestjs/common`: 10.4.4
- `@nestjs/core`: 10.4.4
- `@nestjs/microservices`: 10.4.4
- `reflect-metadata`: 0.2.2
- `rxjs`: 7.8.1
- `uuid`: 10.0.0

### Development

- `typescript`: 5.6.2
- `jest`: 29.7.0
- `eslint`: 9.9.1
- `prettier`: 3.3.3
- See `devDependencies` in `package.json` for the full list.
