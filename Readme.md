
# insert-at-cursor

  insert an html string at the cursor position, or over the selected text. Credits: [Tim Down](http://stackoverflow.com/a/6691294/1198166).

## Installation

  Install with [component(1)](http://component.io):

    $ component install bmcmahen/insert-at-cursor

## Example

```javascript
var insert = require('insert-at-cursor');
document.getElementById('insert').onclick = function(e){
  insert('<b>hello</b>', {selectContent: true});
};
```

## License

  MIT
