# Tea Database Api

Tea is an world famous beverage originated from Asia, this api allows you to fecth types of tea's available in the world and its various details. This is a super stripped down version, so has no routing/controllers.

I have bootstrapped this project with <https://github.com/typicode/json-server> package. It allows us to get `Mock Rest API` with zero coding in less than 30 seconds.

I have also took inspiration from [Ania Kubow's](https://github.com/kubowania) videos.

## Things you can do with this API

You can actually playaround with this API, you can do actions like GET, POST, PUT, DELETE. You can fetch individual tea type.

Example code for fetching tea:
```
fetch('https://tea-collection.herokuapp.com/types_of_tea/0')
  .then(response => response.json())
  .then(data => console.log(data));
  ```

If you wish to contribute to this database please make a pull request.
