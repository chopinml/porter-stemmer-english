# English Stemmer - Porter's Algorithm

This code is based on Martin Porter's stemming algorithm.

Here you can find the paper on http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.848.7219&rep=rep1&type=pdf

And also a plain text version here https://tartarus.org/martin/PorterStemmer/def.txt

### Example Usage

```code
const stemmer = require("porter-stemmer-english") 
stemmer("possibly") //returns possibli
```