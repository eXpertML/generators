# Generators and Deferred Evaluation in XPath

These are the files containing the executable formal definition of the Generator Function Library, operating on generators, as defined in my 
Balisage 2026 paper [Generators and Deferred Evaluation in XPath](https://www.balisage.net/Proceedings/vol31/html/Novatchev01/BalisageVol31-Novatchev01.html) And the powerpoint presentation slides are also in the current directory..

There are two separate code-bases - one for XPath 4, and one for XPath 3.1. 

The function definitions are contained in _generator-functions.xqm_ in the appropriate directory (xpath-4 or xpath-3.1). More than 140 test sub-expressions 
are in the file _generator-functions-test.xq_ in the same directory. I have verified that both test versions execute correctly with BaseX and Saxon.

Please, feel free to post comments and suggestions.
