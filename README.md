# PROIEL-LOD

The PROIEL-LOD is the Linked Open Data version of the [UD_Latin-PROIEL](https://github.com/UniversalDependencies/UD_Latin-PROIEL) treebank, containing texts by authors from the 1st century BCE (Caesar, Cicero) and the 4th century CE (Hieronymus, Palladius). The 205,566 tokens were linked to the LiLa Lemma Bank through a semi-automatic process, with all ambiguous cases manually verified. The data was extracted as-is from the source, with a single typographical correction — namely, the token `magnanimnos` (sent_id 86312, token 5), corrected to `magnanimos`.

### Repository description

 - `TTL (folder)`--> provides a single turtle file for each text of the PROIEL-LOD corpus.
 - `conllup (folder)`--> provides a single conllup file for each text of the PROIEL-LOD corpus, containing the standard conllu format 10 columns with an additional column that specify the lemma URI in the LiLa Lemma Bank.

### Corpus description

| Document                                |  tokens  | % of full work* |
| :-------------------------------------- | -------: | --------------: |
| Hieronimus' _Vulgata_ (_New Testament_) |   109517 |           87.4% |
| Caesar's _De bello Gallico_             |    27386 |           53.4% |
| Cicero's _Epistulae ad Atticum_         |    45308 |           36.3% |
| Cicero's _De officiis_                  |    11375 |           33.3% |
| Palladius' _Opus agriculturae_          |    11980 |           29.9% |

\* The percentages are based on the word counts of the full texts available at [The Latin Library](https://www.thelatinlibrary.com/) and [The Forum Romanum](http://www.forumromanum.org/) websites.

## Funding

The *LiLa: Linking Latin* project has received funding from the European Research Council (ERC) under the European Union’s Horizon 2020 research and innovation programme – Grant Agreement No. 769994.


## Copyright
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />These resources are licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
