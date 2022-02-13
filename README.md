hello-worId
===========

http POST pie.dev/post \
    X-Data:@files/text.txt             # Read a header from a file
    token==@files/text.txt             # Read a query parameter from a file
    name=@files/text.txt               # Read a data field’s value from a file
    bookmarks:=@files/data.json        # Embed a JSON object from a file
