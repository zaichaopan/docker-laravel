# docker-laravel

 This project is inspired by [serverForHacker](#https://serversforhackers.com/dockerized-app). It allows you to set up a laravel development environment quickly and easily using docker.

## Installation

* clone the project to your project's root directory

* create develop script using the develop.example provided

```
cp develop.example develop
```

* change environment variables in develop script to site your need

* make the develop script executable

```
chmod +x develop
```

## Build and Run Your App with Compose

```
./develop up -d
```

## Stop Compose

```
./develop down
```

### Use Composer

```
./develop composer commandName
```

## Use Artisan Command

```
./develop art artisanCommand
```

## Run Phpunit

```
./develop test
```
