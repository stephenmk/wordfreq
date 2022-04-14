# Japanese News Word Frequency Corpus

This is a mirror of the "wordfile" data used by the [JMdict project](https://www.edrdg.org/jmdict/j_jmdict.html) for
[word prioritization markings](https://www.edrdg.org/wiki/index.php/JMdict-EDICT_Dictionary_Project#Word_Priority_Marking).
The data has been converted from its original EUC encoding into UTF-8 by using [iconv](https://en.wikipedia.org/wiki/Iconv):

`iconv -f EUCJP -t UTF-8//IGNORE eucjp/wordfreq -o utf8/wordfreq`

The data was originally compiled by Alexandre Girardi in the 1990s using four years of
data gathered from the Mainichi Shimbun. See the original `wordfreq.README` file included here for
more information.

An original copy can be found on the edrdg.org public FTP server, and the data is said to be in the public domain.
