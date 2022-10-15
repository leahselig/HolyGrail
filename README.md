# Holy Grail App

This project was part of the course work required in the MIT xPRO Full-Stack development course.

A full stack holy grail app, using [Redis](https://redis.io/) as a database from [Node.js](https://nodejs.org/en/).

## Holy grail design pattern

A holy grail is a design with a header, content, two sidebars, and a footer.

## Tasks:

- Use the Redis client to initialise values for header, left, article, right, and footer. These values should be.

```javascript
"header", 0, "left", 0, "article", 0, "right", 0, "footer", 0;
```

- Implement the `data()` method to use Promises to get the values, using the Redis client..

- Implement the `/update/:key/:value` enpoint by using the Redis client to update a given key-value pair.

## Installation

- Download all files into a directory of your choosing
- Install [Redis](https://redis.io/)
- `npm install`
- `node index.js` run on `http://localhost:3000`.

## Learn More

To learn about Redis, check out the [redis documentation](https://redis.io/documentation) and [installation](https://redis.io/download).

## License

[MIT](https://github.com/leahselig/HolyGrail/blob/main/LICENSE)
