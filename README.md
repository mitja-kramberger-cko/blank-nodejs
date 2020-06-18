## Blank Nodejs lambda 

```
module.exports.submit = (event, context, callback) => {
  const response = {
    statusCode: 200,
    body: JSON.stringify({
      message: 'Your function executed successfully!',
      input: event,
    }),
  };

  callback(null, response);
}
```

Already packaged as: `blank-nodejs.zip`