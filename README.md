\<AutoLinkText /\>
================

A React component for converting URLs in a given string of text into clicking link tags. Forked from http://github.com/OpenGov/react-autolink-text

Forked in order to update the React dependency to work with version `15.0.0`

Installation
------------
`npm install @kapost/react-autolink-text`

Usage
-----
```js
import ReactDOM from 'react-dom';
import AutoLinkText from '@kapost/react-autolink-text';

ReactDOM.render(
  <AutoLinkText text="Check out this cool component: http://github.com/OpenGov/react-autolink-text" />,
  document.body
);
```

Thanks
------
Thank you to @gregjacobs for creating [Autolinker.js](https://github.com/gregjacobs/Autolinker.js) from which this component was based.
