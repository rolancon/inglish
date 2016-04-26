# Inglish

Phonetic English

Version: 0.1

Datetime: 2016-03-30T21:36:15Z

## Overview

Inglish is a way to spell English phonetically while at the same time keeping the current spelling conventions. It does this by adorning the 26 letters of the Latin alphabet with various punctuation symbols and formatting markup. The pronunciation is based on the GA (General American) variety of English.

Inglish adheres to the following principles:
- Keep the current spelling conventions for English as its basis
- However, only use lowercase letters for dictionary words
- Do not spell names phonetically and keep existing uppercase letters
- Do not spell foreign words phonetically: keep vowels and consonants as-is
- Use the semicolon (;) to separate sentences instead of the full stop (.)
- Use extended characters from the Unicode Latin code charts to express variations in pronunciation for the same base character
- This means the same character can have multiple renderings, each with different punctuation, which symbolizes 1 distinct sound per punctuated character
- The same sound can therefore be rendered in multiple ways
- Only use extended characters with punctuation that appears on top or under base Latin characters, in other words that do not modify the glyph of the base character
- The only minor exception is for extended characters that replace the dot on top of the 'i' and 'j' characters
- Characters that are written but not pronounced are formatted with bold markup
- Sounds that are pronounced but not written are written as characters formatted with bold markup
- Syllables in a word are separated with a Unicode character U+00B7 middle dot (&#x00B7;) in between
- The primary stress in multi-syllable words is shown with underline markup
- The secondary stress in multi-syllable words is shown as a Unicode character U+00B4 acute accent (&#x00B4;) appended to the vowel
- Noun compounds are written with a hyphen (-)
 
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
|y|hymn|h&#x1EF3;m<b>n</b>||

#### Open
||English|Inglish|IPA|
|:-:|:-----:|:-----:|:-:|
|a|ate|&#x00E1;t<b>e</b>||
|e|me|m&#x00E9;||
|i|hi|h&#x00ED;||
|o|no|n&#x00F3;||
|u|sue|s&#x00FA;<b>e</b>||
|y|why|w<b>h</b>&#x00FD;||

#### Unstressed
||English|Inglish|IPA|
|:-:|:-----:|:-----:|:-:|
|a|basal|b<ins>&#x00E1;</ins>&#x00B7;s&#x00E3;l||
|e|over|<ins>&#x00F3;</ins>&#x00B7;v&#x1EBD;r||
|i|denim|d<ins>&#x00E8;</ins>&#x00B7;n&#x0129;m||
|o|nation|n<ins>&#x00E1;</ins>&#x00B7;&#x0163;<b>i</b>&#x00F5;n||
|u|datum|d<ins>&#x00E0;</ins>&#x00B7;&#x0165;&#x0169;m||
|y|vinyl|v<ins>&#x00ED;</ins>&#x00B7;n&#x1EF9;&#x1E37;||

#### Stressed followed by -r-
||English|Inglish|IPA|
|:-:|:-----:|:-----:|:-:|
|e|her|h&#x00EB;r||
|i|sir|s&#x00EF;r||
|o|world|w&#x00F6;r&#x1E37;d||
|u|fur|f&#x00FC;r||

#### Other vowel variations

#### a
||English|Inglish|IPA|
|:-:|:-----:|:-----:|:-:|
|a|air|&#x00E4;<b>i</b>r||
|a|far|f&#x00E2;r||
|a|ball|b&#x00E5;&#x1E37;<b>l</b>||
|a|bandage|b</ins>&#x00E0;</ins>n&#x00B7;d&#x0103;&#x011D;<b>e</b>||
|a|bayou|b<ins>&#x0101;</ins>&#x00B7;y&#x0151;<b>u</b>||

#### e
||English|Inglish|IPA|
|:-:|:-----:|:-----:|:-:|
|e|they|&#x1E97;<b>h</b>&#x00EA;y||
|e|beer|b&#x0115;<b>e</b>r||
|e|sew|s&#x0113;w||

#### i
||English|Inglish|IPA|
|:-:|:-----:|:-----:|:-:|
|i|magazine|m<ins>&#x00E0;</ins>&#x00B7;g&#x0103;&#x00B7;z&#x00EE;n<b>e</b>||
|i|coin|c&#x00F4;&#x012D;n||

#### o
||English|Inglish|IPA|
|:-:|:-----:|:-----:|:-:|
|o|coin|c&#x00F4;&#x0129;n||
|o|one|<i>w</i>&#x014F;n<b>e</b>||
|o|too|t&#x0151;<b>o</b>||
|o|book|b&#x020D;<b>o</b>k||
|o|how|h&#x014D;w||

#### u
||English|Inglish|IPA|
|:-:|:-----:|:-----:|:-:|
|u||&#x0000FB;||
|u|quiz|q&#x016D;&#x00EC;z||

#### y
||English|Inglish|IPA|
|:-:|:-----:|:-----:|:-:|
|y||&#x1EF9;||

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
|q|quiz|q&#x0169;&#x00EC;z||
|r|rod|r&#x00F2;d||
|s|sue|s&#x00FA;<b>e</b>||
|t|stop|st&#x00F2;p||
|v|vet|v&#x00E8;t||
|w|why|w<b>h</b>&#x00FD;||
|x|six|s&#x00EC;<i>k</i>x||
|y|yes|y&#x00E8;s||
|z|zip|z&#x00EC;p||

#### Aspirated voiceless stops
||English|Inglish|IPA|
|:-:|:-----:|:-----:|:-:|
|c|can|&#x010B;&#x00E0;n||
|k|keep|&#x1E33;&#x00E9;<b>e</b>p||
|p|pan|&#x1E57;&#x00E0;n||
|t|top|&#x1E6D;&#x00F2;p||

#### Other fricatives
||English|Inglish|IPA|
|:-:|:-----:|:-----:|:-:|
|c|cent|&#x00E7;&#x00E8;nt||
|ch|chip|&#x0109;<b>h</b>&#x00EC;p||
|ch|chef|&#x010D;<b>h</b>&#x00E8;f||
|ch|loch|l&#x00F2;<b>c</b>&#x0125;||
|f|of|&#x00F2;&#x1E1F;||
|g|gem|&#x011D;&#x00E8;m||
|gh|rough|r<b>o</b>&#x00F9;&#x01F5;<b>h</b>||
|j|raj|r&#x00E2;&#x0135;||
|ph|phone|&#x1E55;<b>h</b>&#x00F3;n<b>e</b>||
|s|is|&#x00EC;&#x1E61;||
|s|measure|m<ins>&#x00E8;</ins><b>a</b>&#x00B7;&#x0161;&#x016D;r<b>e</b>||
|sh|ship|&#x015D;<b>h</b>&#x00EC;p||
|t|nation|n<ins>&#x00E1;</ins>&#x00B7;&#x0163;<b>i</b>&#x014F;n||
|th|thin|&#x1E6B;<b>h</b>&#x00EC;n||
|th|that|&#x1E97;<b>h</b>&#x00E0;t||
|x|exam|&#x1EBD;<i>g</i>&#x00B7;&#x1E8B;<ins>&#x00E0;</ins>m||
|z|azure|<ins>&#x00E0;</ins>&#x00B7;&#x017E;&#x016D;r<b>e</b>||

#### Other consonant
||English|Inglish|IPA|
|:-:|:-----:|:-----:|:-:|
|l|ball|b&#x00E5;&#x1E37;<b>l</b>||
|n|wing|w&#x00EC;&#x0148;<b>g</b>||
|t|utter|<ins>&#x00F9;</ins><b>t</b>&#x00B7;&#x0165;&#x0115;r||

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
ő
ȍ
ō

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

ḷ

ň

ṕ
ṗ

ŝ
ṣ
š

ṫ
ẗ
ṭ
ţ
ť

ẋ

ž


hello there

how are you

i am good


hè<b>l</b>·l<ins>ó</ins> ẗ<b>h</b>èr<b>e</b>

hōw âr<b>e</b> yő<b>u</b>

í àm gȍ<b>o</b>d

===

The Tower of Babel

Now the whole world had one language and a common speech. As people moved eastward, they found a plain in Shinar and settled there.

ẗ<b>h</b>ĕ t<ins>ō</ins>·wĕr òḟ Babel

nōw ẗ<b>h</b>ĕ <b>w</b>hóḷ<b>e</b> wörḷd hàd <i>w</i>õn<b>e</b> l<ins>à</ins>ň·gũãĝ<b>e</b> ànd ă ċ<ins>ò</ins><b>m</b>·mŏn spé<b>e</b>ĉ<b>h</b>; àṣ ṗ<ins>é</ins><b>o</b>·p<i>ĕ</i>l<b>e</b> mőv<b>e</b>d <ins>é</ins><b>a</b>st·wărd, ẗ<b>h</b>êy fōũnd ă plá<b>i</b>n ìn Shumer ànd s<ins>è</ins><b>t</b>·ṫ<i>ĕ</i>l<b>e</b>d ẗ<b>h</b>èr<b>e</b>
