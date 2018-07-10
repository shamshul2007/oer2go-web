# oer2go-web
This is the code that runs the oer2go.org website.

One piece of documentation at this point - a minimalist open API:

http://oer2go.org/cgi/json_api_v2.pl

This URL will return a JSON associative array of all modules -- the key is the "moddir" (eg: "en-wikipedia" for the English language Wikipedia module), and the data is a limited subset of the data useful for displaying a list.

You can also pass a moddir to the API like this:

http://oer2go.org/cgi/json_api_v2.pl?moddir=en-wikipedia

This will return all the data associated with the en-wikipedia module.


