# Wikipedia samples for the Session 1 notebooks

| file | text | articles | words |
|---|---|---|---|
| `wiki_gl_2M.txt.gz` | Galician Wikipedia | 4,672 | 2,000,390 |
| `wiki_es_2M.txt.gz` | Spanish Wikipedia | 3,897 | 2,001,065 |

One article per line, whitespace collapsed. Articles were drawn at random from the
November 2023 dumps (`wikimedia/wikipedia`, configs `20231101.gl` and `20231101.es`, on
Hugging Face), skipping articles under 50 words, until each sample reached 2 million
words (a word is a run of letters). Notebooks 01b and 01c use them.

The full dumps have 200,092 Galician articles (70.9 million words) and 1,841,155 Spanish
articles (891.2 million words).

**License:** the text is from Wikipedia, licensed under
[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/); these samples are shared
under the same license. Authors: the contributors to Galician and Spanish Wikipedia
(article histories at gl.wikipedia.org and es.wikipedia.org).
