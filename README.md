## Translation
Hi guys, a main goal of this project is to give the possibility to everyone to enjoy it. And since I know what it means to be born as a non-English native speaker I've studied a way to give everyone the possibility to translate it and use the most updated translation.

### Install the latest translation
First open these [links](https://github.com/DonRP/ABFD/tree/languages). Then download the files
![alt text](https://github.com/DonRP/ABFD/blob/master/images/languages-download.webp "Languages Download")
and extract them into the main folder.

**ATTENTION**: I will always do some tests to verify that the translations done do not affect the game. But I can always miss something ([Bug Report](https://discord.gg/5UFPjP9)).

### Instructions to translate & improve my English
If you want to help me do it respecting the rules, every time someone doesn't it makes me waste a lot of time.

First of all sign up for [Crowdin](https://crowdin.com/project/ABFD). Then in [Discord](https://discord.gg/HFfeJKR) go a **#rules** and become a translator (to stay updated and ask for help).

Then before you start, read the [Instructions](https://github.com/DonRP/ABFD#Instructions) carefully.

### English
That's why I created a "false English translation", in this way those who notice errors or who want to improve the report can do so, please write a comment in the English translation when you make correction (eg Fix grammar, syntax, punctuation ...).

### Other languages
The translation from English to another language can often change a lot, so in case the text in that context doesn't make much sense you can not translate word for word, but create a meaningful sentence even if it changes a lot from the original one. Note that usually the dialogs are in order.

### Instructions
- Do not translate the sentence after `#` or `old` (Should be hidden).
- The sentences to be translated are always between `""`
- In case of `new "..."` do not translate `new`
- In case of `"..." nointeract` do not translate `nointeract`

#### e.g:

OK:
```renpy
"Hi, my name is Liam"
```
```renpy
"Hola, me llamo Liam"
```

OK:
```renpy
"Hi, my name is Liam.
I am 20 years old"
```

```renpy
"Salut, je m'appelle Liam.
J'ai 20 ans"
```

OK:
```renpy
new "Hello"
```
```renpy
new "Здравствуйте"
```

OK:
```renpy
"Hello" nointeract
```
```Renpy
"Hola" nointeract
```

NO:
```renpy
new "Hello"
```
```renpy
новый "Здравствуйте"
```

No:
```renpy
"Hello" nointeract
```
```renpy
"Hola" nointeractúa
```
