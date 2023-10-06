# Welcome to Week 15
Simple Cors Implementation 

## 👋 Keep In Touch With Me 
**fadliaryadinata011@gmail.com**

## Authors

👤 **Fadli Aryadinata**

- GitHub: [@fadli131](https://github.com/fadli131)

### Getting Started

## Installation

This is a [Node.js](https://nodejs.org/en/) module available through the
[npm registry](https://www.npmjs.com/). Installation is done using the
[`npm install` command](https://docs.npmjs.com/getting-started/installing-npm-packages-locally):

```sh
$ npm install cors
```

## Deployment Link 

- Origin Link : https://rad-genie-f2e7ed.netlify.app/
- Client Link : https://65206641c240cb403c6362b6--loquacious-granita-9eb441.netlify.app/
- Database : https://ill-tan-elk-vest.cyclic.app/

## Usage 

```javascript
app.get('/', (req, res) => {
  res.json({ message: 'Transfer Request Management API' });
});

app.use("/api-docs", swaggerUi.serve, swaggerUi.setup(swaggerDocument));
app.use(
  OpenApiValidator.middleware({
    apiSpec: openApiPath,
    validateRequests: true,
  })
);
```
