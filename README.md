
<!-- README.md is generated from README.Rmd. Please edit that file -->

# tidymodels-pipelines

<!-- badges: start -->
<!-- badges: end -->

## How to build site locally.

All examples on this website uses CRAN version of R packages, and they
should be installed as such.

### Docker

Installing Docker should be fairly straightforward. Please refer to [Get
Started](https://www.docker.com/get-started/) for how to.

### Setting up Posit Connect

For the smoothest experience, we recommend that you authenticate using
environment variables. The two variables you will need are
`CONNECT_SERVER` and `CONNECT_API_KEY`.

<div class="callout-tip">

The function
[usethis::edit_r_environ()](https://usethis.r-lib.org/reference/edit.html)
can be very handy to open `.Renviron` file to specify your environment
variables.

</div>

`CONNECT_SERVER` is the URL of the posit connect page. So if your
connect server is accessed through
`https://example.com/connect/#/content/` then you can find
`CONNECT_SERVER` by removing `connect/` and everything that follows it,
leaving you with `https://example.com/`.

`CONNECT_API_KEY` is created through your Connect server. 1. Click on
your name in the upper right upper right. 1. Click `API keys`. 1. Click
`New API Key`. 1. Give your API a key, click \``Create Key`.

Once you have those two, you can add them to your `.Renviron` file in
the following format:

``` markdown
CONNECT_API_KEY=xxxxxxxxxxxxxxxxxxxxxxxxxxxx
CONNECT_SERVER=https://example.com/
```
