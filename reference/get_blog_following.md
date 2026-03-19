# Retrieve following

This method can be used to retrieve the publicly exposed list of blogs
that a blog follows, in order from most recently-followed to first.
**Only works with your own account**

## Usage

``` r
get_blog_following(blog, limit = 50, offset = 0, app_credentials = NULL, ...)
```

## Arguments

- blog:

  name of the blog

- limit:

  The number of results to return: 1–50

- offset:

  post index to start at

- app_credentials:

  a named list containing the consumer key and consumer secret. If NULL,
  attempts to load from an env variable

- ...:

  further parameters as described here:
  <https://www.tumblr.com/docs/en/api/v2>

## Value

a tibble of blogs

## Examples

``` r
if (FALSE) { # \dontrun{
# replace "your-blog-name" with your Tumblr username
get_blog_following(blog = "your-blog-name")
} # }
```
