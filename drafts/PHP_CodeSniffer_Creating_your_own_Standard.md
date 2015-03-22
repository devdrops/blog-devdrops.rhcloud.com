TITLE: PHP_CodeSniffer: Creating your own Standard
POST:
Hi!

In this post I'll show how to create your own validation standard for PHP_CodeSniffer.

{add image here}

###PHP_CodeSniffer

We've covered this tool in [another post](http://blog-devdrops.rhcloud.com/using-php_codesniffer-on-netbeans-7-4/). PHP_CodeSniffer is one of the most important tools for code quality in PHP, and if you never used it before, you should be doing it right now.

The tool have a set of _Standards_, which are composed by _Sniffs_, a set of PHP classes created to validate most common mistakes and errors on PHP code styles.

But to first create your own standard, you don't need to write these classes: actually, PHP_CodeSniffer provides a huge list of Sniffs, as you can see through this [link](http://pear.php.net/package/PHP_CodeSniffer/docs/latest/li_PHP_CodeSniffer.html).

{image: list of sniffs}

