# bitly_link_shortener
A simple PHP script that uses the bit.ly v4 API to shorten a url.

https://dev.bitly.com/v4_documentation.html

You'll need to provide the script an auth token.
Auth tokens are available from bit.ly for free, you'll just have to make an account.

Sample use:

serveraddress/bitly_link_shortener.php?url=link_to_shorten

Make sure 'link_to_shorten' is url encoded first.
Script will write out the generated bit.ly link upon success.
