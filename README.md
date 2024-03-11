# Open Bible
A free and open source translation of The Bible.

This Bible translation was generated using an A.I. model (GPT 3.5 Turbo) from OpenAI. The original text used to derive each verse was sourced from the King James Version of The Bible provided by [Project Gutenberg](https://www.gutenberg.org/ebooks/10).

Currently, this translation has not been extensively reviewed, and as such, is specifically open for review. To raise an issue, please utilize the [Issues](https://github.com/ofchrist/OpenBible/issues) tab, where issues, concerns, and suggestions may be addressed.

To view the files, either download the repository/files, which allows for more flexibility, or when trying to view them here, be sure to click on "View raw", as the files are too big to automatically display on this site. For those unfamiliar with using repositories, simply click on the green `<> Code` button up and to the right, then select "Download Zip". Once downloaded, open the zip file to unzip it, and the files will be in the unzipped folder.

## Files
### `verses.txt`
The `verses.txt` file is simply every verse, in order, each on a single line, formatted as:

`<book number>:<chapter number>:<verse number>/<verse text>`

### `bible.json`
The `bible.json` file is structured using JavaScript Object Notation (JSON) such that the keys are:

`"<book number>:<chapter number>"`, 

and the values for each key are an array/list of verses, in order, for that chapter.

This translation is used by the website [ofChrist.life](https://ofchrist.life).
