#var_dump

var_dumps --> var_masterpieces!
[varmasterpiece.probitytechnology.com](http://varMasterpiece.probitytechnology.com)

##What is var_dump

var_dump is a work-in-progress chrome extension that will parse a var_dump out of the DOM and make it pretty!
Also, Just FYI, we are now over on the chrome store: [Here!](https://chrome.google.com/webstore/detail/varmasterpiece/chfhddogiigmfpkcmgfpolalagdcamkl).

##Here's The Deal

Trying to read var_dumps is a lot like trying to read multiple lines of text without punctuation that wraps in a big block and makes you want to cry.

Actually, that is exactly what is it.

There are alternatives to making var_dumps readable, such as:
* importing libraries into php, but that doesn't seem like a good idea.
  * Not only do you now have unnecessary, third part code running on your web server, 
  * but it also sets you up to have different things running between your dev and live sites.
* You could write code above and below all of your var_dumps, but that gets rid of the efficiency.
* You could use php's debugger and... oh wait, there isn't one

It is my conviction that a browser plugin is by far the best route to take, but I couldn't find any.

So here is mine. Hope it works for you!

## Versioning

### NEW
[semver](http://semver.org/): MAJOR.MINOR.PATCH

* 1.1.2 -> updated manifest description.
* 1.1.3 -> Hacky fix for issue caused by `\n` in strings
* 1.2.0 -> rewrote parser to use formal grammar + PEGjs
* 1.3.0 -> updated grammar. Added elegent error handling 

### OLD
version.major.feature.bug

* 1.0.0.# -> bug fixes
* 1.0.1.0 -> added statistics, some options
* 1.0.2.0 -> upgraded options page appearance, new icon
* 1.1.0.0 -> re-wrote a significant portion of code. Better html structure. Slightly better visuals. Removed statistics.
* 1.1.0.# -> small fixes caused by significant rewrite
* 1.1.0.5 -> Removed font awesome dependency to fix bug reported on chrome web store


