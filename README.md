# elastic-client-highlight-builder

A polymer web component that builds an elasticjs highlight.

Example:
```html
        <elastic-client-highlight-builder
          fields="[_all]"
          pre-tags="<highlight>"
          post-tags="</highlight>"
          number-of-fragments="0"
          require-field-match="false"
          ejs-highlight="{{highlight}}">
        </elastic-client-highlight-builder>
```

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install
