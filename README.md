# Lords of Sigurvia (**Sigurvia**) *i18n*

This repository hosts the internationalizable parts of **Sigurva**'s site.

## How to translate
To participate in the translation process, please `fork` this repository. 
In your own fork make the [modifications or extensions](#translation-process) and `commit` the changes.
To finish the process create a `pull request`. Where we review your changes.

After the necessary modifications recommended at the `review` stage (if there were any), we will `merge` your pull requested `branch` to the `master` branch making it live.

Thank you for your cooperation!

## Translation process
All the required files are at top directory.
There are several `JSON` files named by their language they support.

### To translate to a new language:
* Create a new **[`$language-tag`](https://github.com/TAPevents/tap-i18n#languages-tags-and-translations-prioritization)**`.i18n.json` file.
* Copy paste the structure of any language's `.json` file known by you.
* Leave the first column *(`translation key`)* unchanged and translate all the values in the second column *(`translation value`)*. 

### To correct or change translation of a specific language:
* Open it's `.json` file that is prefix by the **[language's tag](https://github.com/TAPevents/tap-i18n#languages-tags-and-translations-prioritization)**.
* Search for the `translation value` *(or `translation key` if you know it)* and change the `translation value`.

### Translation note's
* The `__`$**KEY**`__` means a variable value will be raplaced there. Usually the **KEY**'s name represent what it contains *(ex: `__username__` should contain the user's username)*.
* If you wish to know more about the backend translation technology visit the [TAPevents/tap-i18n repository](https://github.com/TAPevents/tap-i18n#contents).

## Contributors
[@Szayet](http://github.com/Szayet) - English and Hungarian translation

## Currently supported languages

- [ ] Afrikaans
- [ ] Akan
- [ ] Albanian
- [ ] Amharic
- [ ] Arabic
- [ ] Armenian
- [ ] Aromanian
- [ ] Assamese
- [ ] Azerbaijani
- [ ] Azerbaijani (Turkey)
- [ ] Bashkir
- [ ] Basque
- [ ] Belarusian
- [ ] Bengali
- [ ] Bosnian
- [ ] Bulgarian
- [ ] Burmese
- [ ] Catalan
- [ ] Catalan (Balear)
- [ ] Chinese
- [ ] Chinese (China)
- [ ] Chinese (Hong Kong)
- [ ] Chinese (Taiwan)
- [ ] Corsican
- [ ] Croatian
- [ ] Czech
- [ ] Danish
- [ ] Dutch
- [ ] Dutch (Belgium)
- [x] English
- [ ] English (Australia)
- [ ] English (Canada)
- [ ] English (UK)
- [ ] Esperanto
- [ ] Estonian
- [ ] Faroese
- [ ] Finnish
- [ ] French (Belgium)
- [ ] French (France)
- [ ] Frisian
- [ ] Fulah
- [ ] Galician
- [ ] Georgian
- [ ] German
- [ ] Greek
- [ ] Guaraní
- [ ] Hawaiian
- [ ] Hazaragi
- [ ] Hebrew
- [ ] Hindi
- [x] Hungarian
- [ ] Icelandic
- [ ] Indonesian
- [ ] Irish
- [ ] Italian
- [ ] Japanese
- [ ] Javanese
- [ ] Kannada
- [ ] Kazakh
- [ ] Khmer
- [ ] Kinyarwanda
- [ ] Kirghiz
- [ ] Korean
- [ ] Kurdish (Sorani)
- [ ] Lao
- [ ] Latvian
- [ ] Limburgish
- [ ] Lithuanian
- [ ] Luxembourgish
- [ ] Macedonian
- [ ] Malagasy
- [ ] Malay
- [ ] Malayalam
- [ ] Marathi
- [ ] Mingrelian
- [ ] Mongolian
- [ ] Montenegrin
- [ ] Nepali
- [ ] Norwegian (Bokmål)
- [ ] Norwegian (Nynorsk)
- [ ] Ossetic
- [ ] Pashto
- [ ] Persian
- [ ] Persian (Afghanistan)
- [ ] Polish
- [ ] Portuguese (Brazil)
- [ ] Portuguese (Portugal)
- [ ] Punjabi
- [ ] Rohingya
- [ ] Romanian
- [ ] Russian
- [ ] Rusyn
- [ ] Sakha
- [ ] Sanskrit
- [ ] Sardinian
- [ ] Scottish Gaelic
- [ ] Serbian
- [ ] Sindhi
- [ ] Sinhala
- [ ] Slovak
- [ ] Slovenian
- [ ] Somali
- [ ] South Azerbaijani
- [ ] Spanish (Argentina)
- [ ] Spanish (Chile)
- [ ] Spanish (Colombia)
- [ ] Spanish (Mexico)
- [ ] Spanish (Peru)
- [ ] Spanish (Puerto Rico)
- [ ] Spanish (Spain)
- [ ] Spanish (Venezuela)
- [ ] Sundanese
- [ ] Swahili
- [ ] Swedish
- [ ] Swiss German
- [ ] Tagalog
- [ ] Tajik
- [ ] Tamil
- [ ] Tamil (Sri Lanka)
- [ ] Tatar
- [ ] Telugu
- [ ] Thai
- [ ] Tibetan
- [ ] Tigrinya
- [ ] Turkish
- [ ] Turkmen
- [ ] Ukrainian
- [ ] Uighur
- [ ] Ukrainian
- [ ] Urdu
- [ ] Uzbek
- [ ] Vietnamese
- [ ] Walloon
- [ ] Welsh

## Technologies

* JSON
