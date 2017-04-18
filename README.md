# *WordPress* Replace Video in Feed

## Summary

I'm using RSS feeds to generate content for email campaigns and the
WordPress-generated RSS feeds contain `iframe` embed code for YouTube and Vimeo
videos embedded in the content. The `iframe` embed code is useless in the
emails generated from the feed, so I want to override the code that generates
the embed code in the feed.

This plugin does just that. Where an `iframe` embed would be generated in
normal content, the feed will contain a link formatted something like this:

```html
<p><a href="https://vimeo.com/212323382">Watch Lil Dicky &#8211; Pillow Talking feat. Brain (Official Music Video) on Vimeo.</a></p>
```

## Required PHP Extensions

The plugin requires the PHP curl extension. The plugin doesn't check for its
presence, so if it is activated without it there will be errors.

## Releases

### 0.1.0

* Initial release

## License

Apache2

[1]: http://php.net/manual/en/class.domdocument.php
