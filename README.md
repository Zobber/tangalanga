# Tangalanga

Zoom Conference scanner

This are all the possible flags:

```bash
tangalanga \
    -token=user-token \ # User token to user
    -output=log/history \ # Write founds on file
    -debug=true \ # Show not founds too
    -tor=true # Enable tor connection
```

![](http://share.elcuervo.net/tangalanga-find-02.png)

## TOR

Tangalanga has a tor runtime embedded so it can connect to the onion network and run the queries
there instead of exposing your own ip

![](http://share.elcuervo.net/tangalanga-find-tor-01.png)
