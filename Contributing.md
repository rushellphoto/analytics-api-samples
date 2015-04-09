How to contribute code to the project

# Introduction #

A work in progress describing how to contribute code


# Details #

We use Rietveld for code reviews prior to committing. See http://code.google.com/p/rietveld/wiki/CodeReviewHelp for details.

Checkout using subversion (_need details_).

To submit, upload it to codereview.appspot.com using the [upload.py](http://codereview.appspot.com/static/upload.py) script and add a list of reviewers. For example
```
upload.py -r nrhodes@google.com --cc=analytics-api-samples-discuss@googlegroups.com --send_mail  
```
Make sure you're **subscribed** to [analytics-api-samples-discuss](https://groups.google.com/forum/#forum/analytics-api-samples-discuss) or else notification to group may bounce. If you're uploading a patch using the web based form at codereview.appspot.com, don't forget to use the Publish+Mail link on the issue page. To update your patch, use `-i` option with your issue number:
```
upload.py -i XXXXXX --send_mail
```

# Once uploaded #
The reviewers will add comments to your code and publish them as feedback. Go to the [Code Review Tool](http://codereview.appspot.com/), find your issue, and reply to each comment. Once complete you will be given an LGTM and given access to commit your code.


# Legal stuff #
We're living in interesting times. That's why individual contributors need to fill out the [Individual Contributor License Agreement](http://code.google.com/legal/individual-cla-v1.0.html). (Please use the electronic form at the bottom of the page.) It does not transfer copyright, it is actually a slightly modified version of the CLA for the Apache Software Foundation.

For Corporate contributors, there's the [Software Grant and Corporate Contributor License Agreement](http://code.google.com/legal/corporate-cla-v1.0.html).

Google employees do **not** have to fill out one of these!