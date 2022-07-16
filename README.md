Add your new lambda function inside src/ folder

Compile with this command:
```shell
npm run compile
```

Test lambda function with event:
```shell
sam local invoke rLambdaTest -e ./src/lambda-test/event.json
```