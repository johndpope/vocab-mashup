# Vocabulary Mashup

A cheating pseudo-entry in [NaNoGenMo 2015](https://github.com/dariusk/NaNoGenMo-2015/).

This code mashes up two source texts. The first text is used for structure,
while the second provides the vocabulary. Word replacements are chosen to be
semantically close (using word2vec and part-of-speech identification) as well
as similar in frequency between the texts.

pip3 install click, gensim         
python3 mashup.py mash input/alices.txt input/bible.txt        