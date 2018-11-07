# Singapore Bible College Zotero Style for English and Chinese.
## Need
* A Zotero citation style that incorporates both English and Chinese citations that are ordered according to Turabian style but use language-specific punctuation and text such as “edited by” or “translated by”, and so on.
* This style Does not use "ibid" where Turabian does but simply uses the form: **Last name, *Short title*, pages**.
## Solution
* This new style is based on the Turabian 8th edition style for Zotero.
* Ibid and ibid-subsequent citations are set to be the same as subsequent citations in the citation layout: **Last name, *Short title*, pages**.
* For multilingual citations, this style follows the approach found in https://github.com/pulipulichen/blogger/blob/f7544634ebc2ab2ff6fb96362255233d26c05b8d/project/zotero/apa_zh_pulipuli.csl). 
** It uses separate macros and citation and bibliographic layouts based on the language of the item. 
** This solution is not valid CSL, and Zotero complains when installing it, but the solution works.
## Instructions
### Installation
* Download the citation style to your computer. 
* In Zotero > Preferences > Cite > Styles, click the + button and select the downloaded citation style file (sbc-bilingual.csl).
### Creating Citations
* For Chinese items in Zotero, add **zh-cn** to the Language field.
* For all other items, English style and formatting will be followed. 
* Double check that the characters display correctly in your word processor.
