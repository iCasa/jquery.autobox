# Autogrow `<textarea>` while typing

Resize the `<textarea>` (vertically or horizontally) automatically to fit the contents.

Note: This plugin is **under development**.
      It is fully operational, but might have some unexpected behaviour.

## Getting Started
Download the [production version][min] or the [development version][max].

[min]: https://raw.github.com/duzun/jquery.autobox/master/dist/jquery.autobox.min.js
[max]: https://raw.github.com/duzun/jquery.autobox/master/dist/jquery.autobox.js

In your web page:

```html
<script src="jquery.js"></script>
<script src="dist/jquery.autobox.min.js"></script>
<script>
jQuery(function($) {

    // Adjust once Height/Width of all TEXTAREAs in `.myView` and it's descendants.
    $('.myView').autobox();

    // Bind autobox events to all TEXTAREAs in `.myView` and it's descendants.
    $('.myView').bindAutobox();

    // Bind autobox events to `document`, listening on `textarea.autobox` events.
    $(document).autoboxOn('textarea.autobox');

});
</script>
```

## Documentation
_(Coming soon)_

## Examples
_(Coming soon)_

Live example on [DUzun.Me](https://duzun.me/playground/encode#base64UrlEncode=).

## Release History
_(Nothing yet)_
