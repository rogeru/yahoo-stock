yahoo-stock
================

Based on https://github.com/PolymerLabs/polymer-stock

Changed to use Yahoo API since Google Finance APIs are deprecated and don't work due to the MIME-TYPE (application/json 
which is blocked from jsonp execution in Chrome).

`<yahoo-stock autoupdate="true" symbol="GOOG"></yahoo-stock>`