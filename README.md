#What is YQL Finance?

YQL Finance is just a simple jQuery (JSONP) script to call and process stock market data from Yahoo.

##Limitations

When you work with YQL you might want to consider the following few rules and notes taken from the official site. You can find out more at the [Yahoo! Developer Network](http://developer.yahoo.com/yql/).

- YQL can be used for commercial purposes
- If we're going to shut down YQL, we will give you at least 6 months notice with an announcement on this web page and in our forum
- <li>YQL has a performance uptime target of over 99.5%

###Usage Limits

- Per application limit (identified by your Access Key): 100,000 calls per day
- Per IP limits: /v1/public/*: 1,000 calls per hour; /v1/yql/*: 10,000 calls per hour

###Additional Notes

- All rates are subject to change
- You may also be subject to the underlying rate limits of other Yahoo! and 3rd party web services
- YQL relies on the correct operation of the web services and content providers it accesses

##License

(The MIT License)

Copyright © 2009-2012 Marcell Jusztin

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the ‘Software’), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED ‘AS IS’, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

YQL and Yahoo! are registered trademarks of Yahoo! For more information please visit [their website](http://info.yahoo.com/legal/uk/yahoo/ip_copyright.html)