
# CTIS166 HW Analyzing commonly used words in two articles.

Entire descriptions about CTIS166 HW details mentioned on Word Document.

Commands that I used in this Homework:

 * cat input.txt | tr ‘[:upper:]’ ‘[:lower:]’ > output.txt

 * sed ‘s/\(.*\)/\L\1/’ Article1.txt > lowerArticle1.txt

 * cat lowerArticle1.txt | tr -d ‘[:punct:]’ >puncAritlce1.txt

 * tr ‘[:space:]’ ‘\n’ < puncArticle1.txt > rArticle1.txt

 * tr -cs '[:alnum:]' '\n' < puncArticle1.txt | sort | uniq > rArticle1.txt

 * comm -12 uniqueWord1.txt uniqueWord2.txt













## Authors

- [@onurcangnc](https://github.com/onurcangnc)

