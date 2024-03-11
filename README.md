# Open Bible
A free and open source translation of The Bible.

This Bible translation was generated using an A.I. model (GPT 3.5 Turbo) from OpenAI. The original text used to derive each verse was sourced from the King James Version of The Bible provided by [Project Gutenberg](https://www.gutenberg.org/ebooks/10).

Currently, this translation has not been extensively reviewed, and as such, is specifically open for review.

To view the files, either download the repository, which allows for more flexibility, or when trying to view them here, be sure to click on "View raw", as the files are too big to automatically display on this site.

## Files
### `verses.txt`
The `verses.txt` file is simply every verse, in order, each on a single line, formatted as `<book number>:<chapter number>:<verse number>/<verse text>`

### `bible.json`
The `bible.json` file is structured such that the keys are `"<book number>:<chapter number>"`, and the values for each key are an array of verses, in order, for that chapter.

This translation is used by the website [ofChrist.life](https://ofchrist.life).
