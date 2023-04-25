# Lanes-Lexicon-Database

I started off with the lexicon.sqlite database from this repo: https://github.com/laneslexicon/LexiconDatabase/blob/master/lexicon.sqlite.zip.

From there I used it to filter and create some new tables that would make search a lot easier.

Column Names:

index: column index.

id: unique id for each word.
search_word: These are all of the words in Lanes Lexicon without any tashkeel.
root: All of the roots corresponding to these words.
display_word: This is the same list as the search_word, but with all of the tashkeel (diacritics).
itype: It contains if the word is a verb form, then which verb form? etc.
xml: This contains the entire definition of the world.
