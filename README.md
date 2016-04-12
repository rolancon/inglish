# Inglish

Phonetic English

Version: 0.1

Datetime: 2016-03-30T21:36:15Z

## Overview

Inglish is a way to spell English phonetically while at the same time keeping the current spelling conventions. It does this by adorning the 26 letters of the Latin alphabet with various punctuation symbols and formatting markup.

Inglish adheres to the following principles:
- Keep the current spelling conventions for English as its basis
- However, only use lowercase letters for dictionary words
- Do not spell names phonetically: keep uppercase letters
- Do not spell foreign words phonetically: keep vowels and consonants as-is
- Use the semicolon (;) to separate sentences instead of the full stop (.)
- Use extended characters from the Unicode Latin code charts to express variations in pronunciation for the same base character
- This means the same character can have multiple renderings, each with different punctuation, which symbolizes 1 distinct sound per punctuated character
- Only use extended characters with punctuation that appears on top or under base Latin characters, in other words that do not modify the glyph of the base character
- The only minor exception is for extended characters that replace the dot on top of the 'i' and 'j' characters
- Characters that are not pronounced are formatted with italic markup
- Sounds that do not appear in the spelling of the word are shown as characters that are formatted with inserted markup
- The primary stress is shown with bold (strong) markup
- The aspirated unvoiced stop is shown as a Unicode character U+00B4 acute accent (&#x00B4;) appended to the 't', 'p', 'k' or 'q' character
- Syllables in a word are separated with a Unicode character U+00B7 middle dot (&#x00B7;) in between

## Charts

### Vowels

#### Closed
||English|Inglish|IPA|
|:-:|:-----:|:-----:|:-:|
|a|bad|b&#x00E0;d||
|e|bed|b&#x00E8;d||
|i|did|d&#x00EC;d||
|o|nod|n&#x00F2;d||
|u|bud|b&#x00F9;d||
|y|hymn|h&#x1EF3;m<ins>n</ins>||

#### Open
||English|Inglish|IPA|
|:-:|:-----:|:-----:|:-:|
|a|ate|&#x00E1;t<ins>e</ins>||
|e|me|m&#x00E9;||
|i|hi|h&#x00ED;||
|o|no|n&#x00F3;||
|u|sue|s&#x00FA;<ins>e</ins>||
|y|why|w<ins>h</ins>&#x00FD;||

#### Combinations with a
||English|Inglish|IPA|
|:-:|:-----:|:-----:|:-:|
|ae|aeon|&#x00;e&#x00B7;on||
|ai|aim|&#x00;im||
|ao|chaos|ch&#x00;os||
|au|haul|h&#x00;l||
|aw|law|l&#x00;w||
|ay|bay|b&#x00;y||

#### Combinations with e
||English|Inglish|IPA|
|:-:|:-----:|:-----:|:-:|
|ea||&#x00;||
|ee||&#x00;||
|ei||&#x00;||
|eo||&#x00;||
|eu||&#x00;||
|ew||&#x00;||
|ey||&#x00;||

#### Combinations with o
||English|Inglish|IPA|
|:-:|:-----:|:-----:|:-:|
|oa||&#x00;||
|oe||&#x00;||
|oi||&#x00;||
|oo||&#x00;||
|ou||&#x00;||
|ow||&#x00;||
|oy||&#x00;||

### Consonants

#### Basic
||English|Inglish|IPA|
|:-:|:-----:|:-----:|:-:|
|b|bad|b&#x00E0;d||
|c|arc|&#x00E2;rc||
|d|did|d&#x00EC;d||
|f|far|f&#x00E2;r||
|g|gun|g&#x00F9;n||
|h|hi|h&#x00ED;||
|j|jar|j&#x00E2;r||
|k|skin|sk&#x00EC;n||
|l|lid|l&#x00EC;d||
|m|me|m&#x00E9;||
|n|no|n&#x00F3;||
|p|spin|sp&#x00EC;n||
|q|quiz|q&#x016B;&#x00EC;z||
|r|rod|r&#x00F2;d||
|s|sue|s&#x00FA;<ins>e</ins>||
|t|stop|st&#x00F2;p||
|v|vet|v&#x00E8;t||
|w|why|w<ins>h</ins>&#x00FD;||
|x|six|s&#x00EC;x||
|y|yes|y&#x00E8;s||
|z|zip|z&#x00EC;p||

#### Aspirated voiceless stops
||English|Inglish|IPA|
|:-:|:-----:|:-----:|:-:|
|c|can|&#x010B;&#x00E0;n||
|k|keep|&#x1E33;&#x00E9;<ins>e</ins>p||
|p|pan|&#x1E57;&#x00E0;n||
|t|top|&#x1E6D;&#x00F2;p||

#### Other fricatives
||English|Inglish|IPA|
|:-:|:-----:|:-----:|:-:|
|ch|chip|&#x0109;<ins>h</ins>&#x00EC;p||
|ch|loch|l&#x00F2;<ins>c</ins>&#x0125;||
|g|gel|&#x011D;&#x00E8;l||
|gh|rough|r<ins>o</ins>&#x00F9;&#x01F5;<ins>h</ins>||
|j|raj|r&#x00E3;&#x0135;||
|ph|phone|&#x1E55;<ins>h</ins>&#x00F3;n<ins>e</ins>||
|s|measure|m<b>&#x00E8;</b><ins>a</ins>&#x00B7;&#x0161;&#x016D;r<ins>e</ins>||
|sh|ship|&#x015D;<ins>h</ins>&#x00EC;p||
|z|azure|<b>&#x00E0;</b>&#x00B7;&#x017E;&#x016D;r<ins>e</ins>||

### Example

à
á
â
ã
ä
ă
ā

è
é
ê
ẽ
ë
ĕ
ē

ì
í
î
ĩ
ï
ĭ
ī

ò
ó
ô
õ
ö
ŏ
ō

ő

ù
ú
û
ũ
ü
ŭ
ū

ỳ
ý
ŷ
ỹ
ÿ

ĉ
ċ
ç
č

ḟ

ǵ
ĝ

ĥ

ĵ

ḳ

ļ

ň

ṕ
ṗ

ŝ
ş
š

ṫ
ẗ
ṭ
ţ
ƫ

ẋ
ẍ

ž


hello there

how are you

i am good


hè<b>l</b>·l<ins>ó</ins> ẗ<b>h</b>èr<b>e</b>

hǒw âr<b>e</b> yő<b>u</b>

í àm gō<b>o</b>d

===

The Tower of Babel

Now the whole world had one language and a common speech. As people moved eastward, they found a plain in Shinar and settled there.

ẗ<b>h</b>ẽ t<ins>ǒ</ins>·wẽr ǒḟ Babel

nǒw ẗ<b>h</b>ẽ <b>w</b>hóļ<b>e</b> wörļd hàd <i>w</i>ŏn<b>e</b> l<ins>à</ins>ň·gŭāĝ<b>e</b> ànd ã ċ<ins>ò</ins><b>m</b>·mõn spé<b>e</b>ĉ<b>h</b>; àş ṗ<ins>é</ins><b>o</b>·p<i>ẽ</i>l<b>e</b> mőv<b>e</b>d <ins>é</ins><b>a</b>st·wãrd, ẗ<b>h</b>êy fǒųnd ã plá<b>i</b>n ìn Shumer ànd s<ins>è</ins><b>t</b>·ƫ<i>ẽ</i>l<b>e</b>d ẗ<b>h</b>èr<b>e</b>
