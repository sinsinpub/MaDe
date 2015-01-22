# This is an H1
## This is an H2
### This is an H3
#### This is an H4
##### This is an H5
###### This is an H6

> This is the first level of quoting.
>
> > This is nested blockquote.
>
> Back to the first level.

### Unordered List
- Red
- Green
- Blue

### Ordered List
1. Red
2. Green
3. Blue
*   Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
    Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,
    viverra nec, fringilla in, laoreet vitae, risus.
*   Donec sit amet nisl. Aliquam semper ipsum sit amet velit.
    Suspendisse id sem consectetuer libero luctus adipiscing.

A sample text here. And some code below:
    
    import sys
    import gobject
    def init():
        for i in range(0, 10):
            print 'task %d, done' % i

    if __name__ == '__main__':
        init()

Inline code `printf()` here.

Block code:
```javascript
var marked = require('marked');
marked.setOptions({
  renderer: new marked.Renderer(),
  gfm: true,
  tables: true,
  breaks: false,
  pedantic: false,
  sanitize: false,
  smartLists: true,
  smartypants: false,
  highlight: function (code) {
    return require('highlight.js').highlightAuto(code).value;
  }
});
```

This is a link to [Google](http://google.com).

*single asterisks*

**double asterisks**

Create fake iPhone text conversations. Enter a conversation: Example: Dad: Your mom and I are going to divorce next month. Son: Why ? Call me please. 

Create fake iPhone text conversations. Enter a conversation: Example: Dad: Your mom and I are going to divorce next month. Son: Why ? Call me please. 

Inline HTML:
<center>Go to center</center>

GFM Table:

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
