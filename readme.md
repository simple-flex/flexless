# flex.less
###### simpler flex syntax
###### flex with less effort

### [simple-flex](https://github.com/simple-flex/simple-flex) implementation as less mixins

```sh
npm i flexless # -- save
```
```less
@import '../node_modules/flexless/flex'

body {
  .flex(less);
  // display: flex;

  .flex(line);
  // display: inline-flex;

  .flex(center);
  /*
    align-items: center;
    align-content: center;
    justify-content: center;
  */

  .flex(wrap);
  // flex-wrap: wrap;

  .flex(column);
  // flex-direction: column;

  .justify(end);
  // justify-content: flex-end;

  .justify(around);
  // justify-content: space-around;

  .align(start);
  // align-items: flex-start;

  .self(auto);
  // align-self: auto;

  .flex(grow);
  // flex-grow: 1;
}
```
