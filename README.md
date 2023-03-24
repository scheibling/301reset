# 301reset
301 redirect reset for a given (source) URL

## Background
301 redirects are cached for a ridiculously long time, at least for GET requests. 
The only easy way to reset them is to clear a lot of browser cache data for the website in question... Or just make a post request to the same URL.
Since POST is assumed to contain actual data, those requests aren't cached. If a website doesn't respond with a 301 to a POST request, the redirect is cleared for GET as well.

## Usage
[301reset.v3.nu](https://301reset.v3.nu) or [scheibling.github.io/301reset](https://scheibling.github.io/301reset) just enter the URL and click reset!
