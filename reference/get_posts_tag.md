# Get Posts with Tag

Get Posts with Tag

## Usage

``` r
get_posts_tag(tag, before, limit = 20, api_key = NULL, ...)
```

## Arguments

- tag:

  tag to search for

- before:

  the timestamp of when you'd like to see posts before

- limit:

  The number of results to return: 1–50

- api_key:

  app consumer key. If NULL, attempts to load from the environment
  variable RTUMBLR_TOKEN

- ...:

  further parameters as described here:
  <https://www.tumblr.com/docs/en/api/v2>

## Value

a list of tibbles of blog posts by format of posts

## Details

This function uses the legacy post format since it appears to not
support the new post format

## Examples

``` r
if (FALSE) { # \dontrun{
get_posts_tag(tag="meme")
} # }
```
