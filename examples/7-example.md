# JavaScript
```js
function foo(){return 'foo'
}

const bar = [ 1, 2,3,4,5, '6'];

foo( 'some arg','even longer arg',"it's getting ridiculous long", `wtf, please send help!`, 1010001100100, bar  );

let baz = {
  h: 'a', n: 'n', o: 'v', e: 'r',
    j: 's'
};

```
# React
```js
import React from 'react';

const Heading = (props) => <h1 {...props}    >{props.children   }</h1>

export     default   function HelloWorld({prop, otherProp, anotherProp, anotherOtherProp,    ...rest}) {
  const { destructured} = prop;

  return (
         <div className="asdf">
      <Heading prop={prop} otherProp={otherProp} anotherProp={anotherProp} anotherOtherProp={anotherOtherProp}          {...rest}>asdfasdfasdfasdfadsfasdfasdf</Heading>
    </div>
  )
}

```
# JSON

```json
{
  "asdf":    "asdf",

"value": true,

    "other_value": false
}
```
# CSS
```css
p    {
  color: red;
}

body { font-family:
      'Georgia',sans-serif; }
```
# SCSS
```scss
$color: red;

@mixin generateContent( $otherColor: $color ) {
      background-color: $otherColor;
}

body {
  @include generateContent();
}
```
# LESS
```less
@base: #f938ab;

  .box-shadow(@style, @c) when (iscolor(@c)) {
  -webkit-box-shadow: @style @c;
  box-shadow:         @style @c;
}
.box-shadow(@style, @alpha: 50%) when (isnumber(@alpha)) {
      .box-shadow(@style, rgba(0, 0, 0, @alpha));
}
.box {
  color: saturate(@base,  5%);
    border-color: lighten(@base, 30%);
  div { .box-shadow(0 0 5px, 30%) }
}
```
