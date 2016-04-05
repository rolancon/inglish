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
|a|bad|b<b>&#x00E0;</b>d||
|e|bed|b<b>&#x00E8;</b>d||
|i|did|d<b>&#x00EC;</b>d||
|o|nod|n<b>&#x00F2;</b>d||
|u|bud|b<b>&#x00F9;</b>d||
|y|hymn|h<b>&#x1EF3;</b>m<ins>n</ins>||

#### Open
||English|Inglish|IPA|
|:-:|:-----:|:-----:|:-:|
|a|ate|<b>&#x00E1;</b>t<ins>e</ins>||
|e|me|m<b>&#x00E9;</b>||
|i|hi|h<b>&#x00ED;</b>||
|o|no|n<b>&#x00F3;</b>||
|u|sue|s<b>&#x00FA;</b><ins>e</ins>||
|y|why|w<ins>h</ins><b>&#x00FD;</b>||

### Consonants

#### Basic
||English|Inglish|IPA|
|:-:|:-----:|:-----:|:-:|
|b|bad|b<b>&#x00E0;</b>d||
|c|arc|<b>&#x00E2;</b>rc||
|d|did|d<b>&#x00EC;</b>d||
|f|far|f<b>&#x00E2;</b>r||
|g|gun|g<b>&#x00F9;</b>n||
|h|hi|h<b>&#x00ED;</b>||
|j|jar|j<b>&#x00E2;</b>r||
|k|skin|sk<b>&#x00EC;</b>n||
|l|lid|l<b>&#x00EC;</b>d||
|m|me|m<b>&#x00E9;</b>||
|n|no|n<b>&#x00F3;</b>||
|p|spin|sp<b>&#x00EC;</b>n||
|q|quiz|q&#x1E75;<b>&#x00EC;</b>z||
|r|rod|r<b>&#x00F2;</b>d||
|s|sue|s<b>&#x00FA;</b><ins>e</ins>||
|t|stop|st<b>&#x00F2;</b>p||
|v|vet|v<b>&#x00E8;</b>t||
|w|why|w<ins>h</ins><b>&#x00FD;</b>||
|x|six|s<b>&#x00EC;</b>x||
|y|yes|y<b>&#x00E8;</b>s||
|z|zip|z<b>&#x00EC;</b>p||

#### Aspirated voiceless stops
||English|Inglish|IPA|
|:-:|:-----:|:-----:|:-:|
|c|can|&#x010B;<b>&#x00E0;</b>n||
|k|keep|&#x1E33;<b>&#x00E9;</b><ins>e</ins>p||
|p|pan|&#x1E57;<b>&#x00E0;</b>n||
|t|top|&#x1E6D;<b>&#x00F2;</b>p||

#### Other fricatives
||English|Inglish|IPA|
|:-:|:-----:|:-----:|:-:|
|ch|chip|&#x0109;<ins>h</ins><b>&#x00EC;</b>p||
|ch|loch|l<b>&#x00F2;</b><ins>c</ins>&#x0125;||
|g|gel|&#x011D;<b>&#x00E8;</b>l||
|gh|rough|r<ins>o</ins><b>&#x00F9;</b>&#x01F5;<ins>h</ins>||
|j|raj|r<b>&#x00F2;</b>&#x0135;||
|ph|phone|&#x1E55;<ins>h</ins><b>&#x00F3;</b>n<ins>e</ins>||
|s|measure|m<b>&#x00E8;</b>&#x00B7;&#x0161;&#x016D;r<ins>e</ins>||
|sh|ship|&#x015D;<ins>h</ins><b>&#x00EC;</b>p||
|z|azure|<b>&#x00E0;&#x00B7;</b>&#x017E;&#x016D;r<ins>e</ins>||
