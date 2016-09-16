madlibs
=======

`madlibs` is a random sentence generator that you can use for test
input, chat bot integration, annoying coworkers, etc.

It operates on a lexicon file, which defines the structure of a
sentence.  The format of the lexicon file is:

    SENTENCE STRUCTURE

    phrase1 ::
      alternate
      text
      or words

    phrase2 ::
      etc.

Whitespace is optional, but definitely helps the legibility of the
string definition.

To run it:

    madlibs < /path/to/lexicon/file

Have fun!
