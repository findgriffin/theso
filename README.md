theso
=====

A command line thesaurus utility.

The data is requested via API from: thesaurus.altervista.org.

To use the API you need a key, which you ca get by going to:

http://thesaurus.altervista.org/mykey

The key can be passed to theso by setting the THESO_KEY environment variable
or via the command line.

So to use theso you simply run:

    theso word

or if you want to pass the key in via the command line:

    theso word [your_key]

You will then be returned a list of synonyms, antonyms and similar terms. The
list will be split into usages (noun, verb, adjective, adverb) and then sorted
alphabetically.
