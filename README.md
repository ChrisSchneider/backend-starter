Backend Starter
===

### Uses
* [IBM App ID](https://www.ibm.com/cloud/app-id)
* Express
* Nodemon
* Mocha + Chai
* Docker

### Prepare

Environment variables

* Create copy of `.env.example`
* rename it to `.env`
* Replace values with yours

Install dependencies

```
npm i
```

### Start

Start running application on PORT defined in .env

```
npm start
```

### Testing

##### Unit testing

Run unit test once

```
test:unit
```

Run unit test with watcher

```
test:unit:watch
```

##### Integration testing

Run integration tests

```
test:integration
```

Run integration test with watcher
```
test:integration:watch
```

### Run in production

```
npm start
```
