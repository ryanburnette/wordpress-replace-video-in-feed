# *WordPress* Replace Video in Feed

## In Development

This is a work in progress.

## Rationale

I'm using RSS feeds to generate content for email campaigns and the WordPress-generated
RSS feeds contain `iframe` embed code for videos embedded in content. This isn't how
I want to add videos to emails. The goal of this plugin is to replace the `iframe`
embed with the video thumbnail and a link to play the video to keep the emails
generated from the feed working properly.

## Required PHP Extensions

The plugin requires the PHP curl extension. The plugin doesn't check for its
presence, so if it is activated without it there will be errors.

## License

Apache2

[1]: http://php.net/manual/en/class.domdocument.php
