## unstated-class-constructor-bug
A bug I found with [`@gitbook/unstated`](https://github.com/GitbookIO/unstated/) not working for Parcel.

```
Uncaught TypeError: Class constructor Container cannot be invoked without 'new'
```

See [#1](https://github.com/GitbookIO/unstated/issues/1) for more details.

### Running
Run the following, then open up `localhost:1234`. Check the console for errors.
```bash
npm start
```
