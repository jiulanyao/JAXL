Jaxl v3.0.1
-----------

Jaxl v3.x is a successor of v2.x (and is NOT backward compatible), 
carrying a lot of code from v2.x while throwing away the ugly parts.
A lot of components have been re-written keeping in mind the feedback from
the developer community over the last 4 years. Also Jaxl shares a few
philosophies from my experience with erlang and python languages.

Jaxl is an asynchronous, non-blocking I/O, event based PHP library 
for writing custom TCP/IP client and server implementations. 
From it's previous versions, library inherits a full blown stable support 
for [XMPP protocol stack](https://github.com/frost-nzcr4/JAXL/tree/v3.0.1/xmpp). 
In v3.0, support for [HTTP protocol stack](https://github.com/frost-nzcr4/JAXL/tree/v3.0.1/http) 
has also been added.

At the heart of every protocol stack sits the [Core stack](https://github.com/frost-nzcr4/JAXL/tree/v3.0.1/core).
It contains all the building blocks for everything that we aim to do with Jaxl library. 
Both XMPP and HTTP protocol stacks are written on top of the Core stack. 
Infact the source code of protocol implementations knows nothing 
about the standard (inbuilt) PHP socket and stream methods.

## Contribute to JAXL

JAXL v3.0.1 adopt [PSR-2](http://www.php-fig.org/psr/psr-2/).
Check your PRs with [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer):

```ShellSession
/path/to/phpcs
```

[Examples](https://github.com/frost-nzcr4/JAXL/tree/v3.0.1/examples/)

[Documentation](http://jaxl.readthedocs.org/)

[Group and Mailing List](https://groups.google.com/forum/#!forum/jaxl)

[Create a bug/issue](https://github.com/abhinavsingh/JAXL/issues/new)

[Author](http://abhinavsingh.com/)
