# Retrieve Published Posts

Retrieve Published Posts

## Usage

``` r
get_blog_posts(blog, limit = 50, offset = 0, api_key = NULL, ...)
```

## Arguments

- blog:

  name of the blog

- limit:

  The number of results to return: 1–50

- offset:

  post index to start at

- api_key:

  app consumer key. If NULL, attempts to load from the environment
  variable RTUMBLR_TOKEN

- ...:

  further parameters as described here:
  <https://www.tumblr.com/docs/en/api/v2>

## Value

a tibble of blog posts

## Details

this function uses the new post format (npf:
<https://www.tumblr.com/docs/npf>)

## Examples

``` r
if (FALSE) { # \dontrun{
# replace "blog-name" with a Tumblr username
get_blog_posts(blog = "blog-name")
} # }
```
