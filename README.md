theso
=====

A command line thesaurus utility. Written in Python.

The data is requested via API from: thesaurus.altervista.org.

To use the API you need a key, which you ca get by going to:

http://thesaurus.altervista.org/mykey

The key can be passed to theso by setting the THESO_KEY environment variable
or by editing the TOKEN variable in the source code.

So to use theso you simply run:

    theso word

You will then be returned a comma separated list of synonyms, antonyms and
similar terms. The list will be split into usages (noun, verb, adjective,
adverb) and then sorted alphabetically.

You can specify only certain usages that are of interest by adding a comma
separated list of the usages you would like, for example.
    
    theso heavy noun,adj

There are four possible usages: noun, verb, adj, and adv.
