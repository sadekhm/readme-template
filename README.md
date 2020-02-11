# Nairobi

Brief description of what this repository contains. It should cover what this service, application or function do.

## Installation

### Project Dependencies

* NodeJS v12.14 or higher.
* Yarn v1.21 or higher.
* Python v2.9 or higher.
* XCode v11.0 or higher
* Android Studio v3.5 or higher
* Android SDK 28
* MySQL v8.0 or higher
* Maven v4.0 or higher
* JDK v8.0 or higher

### Environment Variables

Copy `.env.copy` to a new file `.env` and add the values that match with each key and description. All variables must be loaded in `.env` to be able to run the project.

### Install Code Dependencies

In root directory run the following command:

```bash 
yarn install
```

## Run Project in Development

In root directory run the following command:

```bash 
yarn dev
```

## Run Project in Production

In root directory run the following command:

```bash 
yarn build && yarn start
```

## Run Application Container

You can run application container using Dockerfile. You must have Docker installed on your system to be able to run container.

### Database Container

```bash
docker run --name mysql --rm -p 3308:3306 -e MYSQL_ROOT_PASSWORD=toor mysql:8
```

### Run Redis Container

```bash
docker run --rm --name redis -p 6379:6379 redis:5.0.5-buster
```

## Run using IDE

### Visual Studio Code

> Steps to run on VS Code

### Android Studio

> Steps to run on VS Code

### XCode

> Steps to run on XCode

### IntelliJ

> Steps to run on IntelliJ

## Supporting Documents

* [API Blueprint](https://aucstudentcloud.docs.apiary.io/)
* [Swagger](https://aucstudentcloud.docs.apiary.io/)

This project is based on Next.JS. if you need to know more about the framework you can know more in [Next.js documentation](https://nextjs.org/docs) 

## Internal Documents

* [Changelog](./CHANGELOG)
* [Technical Actions](./ACTIONS)