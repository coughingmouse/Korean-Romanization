# Mawus Korean Romanization

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#github.com/coughingmouse/Korean-Romanization)

[A short sample text here](https://github.com/coughingmouse/Korean-Romanization/blob/main/sample.md)

[Full specifications here](https://github.com/coughingmouse/Korean-Romanization/blob/main/main.md).

Thanks to a particular Joris Bohnson for urging me toward diacritics.

## Introduction

This is somewhat like a different version of Yale Romanization of Korean. There are a transliteration system and a phonemic transcription made fit for both Modern Korean and Middle Korean, all made compatible with the international Qwerty layout, as well as ASCII-compatible versions. For extra details regarding the Modern Korean Romanization, click [this](https://github.com/coughingmouse/Korean-Romanization/blob/main/Modern_Korean_MKSR.md).

To type letters with diacritics on a standard Qwerty layout, use English (United States) United States-International keyboard on Windows and us altgr-intl on Linux. You can use ⟨AltGr⟩ + ⟨e⟩ to type ⟨é⟩, ⟨AltGr⟩ + the key next to ⟨u⟩ to type ⟨ü⟩, etc. On Apple devices, long pressing a key pops up a menu from which you can select an appropriate diacritic. You can also use  ⟨AltGr⟩ + ⟨e⟩, ⟨AltGr⟩ + ⟨u⟩, and ⟨AltGr⟩ + ⟨i⟩ to type diacritics directly there on the default keyboard layout. 

결과적으로는 예일 로마자 표기법을 고친 꼴이 된 마우스식 국문 로마자화를 소개합니다. 국제 쿼티 자판에 맞게 설계된 현대 한국어와 중세 한국어에 대한 전자법과 음운론적 전사법이 있으며, ASCII 호환성을 고려한 버전도 있습니다. 현대 한국어에 맞춘 국문 로마자화에 대한 추가적인 사항은 [여기서](https://github.com/coughingmouse/Korean-Romanization/blob/main/Modern_Korean_MKSR.md) 확인할 수 있습니다.

쿼티 자판을 사용해 발음 구별 기호가 있는 글자를 입력하려면 윈도우즈를 사용 시에는 English (United States) United States-International keyboard 자판을 사용하고, 리눅스에서는 us altgr-intl 자판을 사용하셔서 ⟨AltGr⟩ + ⟨e⟩와 ⟨AltGr⟩ + ⟨u⟩ 옆의 글쇠 등을 누르면 됩니다. 애플 사의 기기에서는 글자를 길게 누르면 글자에 추가할 발음 구별 기호가 나와서 선택할 수 있습니다. 또한 기본 쿼티 자판에서는 ⟨AltGr⟩ + ⟨e⟩나 ⟨AltGr⟩ + ⟨u⟩, ⟨AltGr⟩ + ⟨i⟩로 발음 구별 기호를 직접 입력할 수도 있습니다.

Why this came to be is written [here](https://github.com/coughingmouse/Korean-Romanization/blob/main/why.md). In making this system, a [proto](https://github.com/coughingmouse/Korean-Romanization/blob/main/proto.md) version was [modified](https://github.com/coughingmouse/Korean-Romanization/blob/main/ASCII.md) to fit with ASCII, then was further modified and extended to fit every practical need coherently.

## Todo

- [ ] Implement an IME.
- [ ] Make a romanizing bot on some platform.
- [ ] Implement a custom layout in case an IME can't run and you would like to write without pressing Alt-Gr.
______

## Sample Romanization

Hangul | Trans.
--- | ---
ㅇ | ʼ(')
ㅣ | i
〮 | ꜛ(^)
〯 | :
ː | :

* ⟨i⟩ is used if it is or is a part of a nucleus. ⟨y⟩ is used if it is the first letter of a vowel cluster. Else, ⟨j⟩ is used: when it's the last letter of a vowel cluster, except when preceded by a semivowel, e.g. ⟨ퟄ⟩, romanized as ⟨yi⟩.
* Accent markers go before a nucleus, and the long vowel symbol goes after the nucleus.

| H | T | H | T |
| - | - | - | - |
| ㄱ | q | ㅈ | z |
| ㄴ | n | ㅊ | c |
| ㄷ | d | ㅿ | j |
| ㄹ | l | ㅋ | k |
| ㅁ | m | ㅌ | t |
| ㅂ | b | ㅍ | p |
| ㅅ | s | ㆆ | ˮ(") |
| ㆁ | g | ㅎ | x |
| ㄲ | qq | ㅱ | w |
| ㄸ | dd | ㅸ | v |
| ㅃ | bb | ㅹ | vv |
| ㅆ | ss | ㆄ | f |
| ㅉ | zz | ᄛ | r |
| ᄾ | ś(s\\) | ᄼ | š(s\`) |
| ᄿ | sś(ss\\) | ᄽ | sš(ss\`) |
| ᅐ | ź(z\\) | ᅎ | ž(z\`) |
| ᅑ | zź(zz\\) | ᅏ | zž(zz\`) |
| ᅕ | ć(c\\) | ᅔ | č(c\`) |

* ⟨ng⟩ can be used instrad of ⟨g⟩.
* In transcription, it's allowed to use ⟨r⟩ if pronounced rhotically.
* For combinational letter clusters, just write them out by each compositig letter.

### Consonants for pronunciation-education

| H | T | H | T |
| - | - | - | - |
| ㄱ | kh/g/k | ㅈ | zhj/t | 
| ㄴ | nh/n/n | ㅊ | chj/t | 
| ㄷ | th/d/t |    |    |
| ㄹ | l/r | ㅋ | kx/kh | 
| ㅁ | mh/m/m | ㅌ | tx/t | 
| ㅂ | ph/b/p | ㅍ | px/p |
| ㅅ | sh/shj | ㆆ | ˮ(") |
| ㆁ | ng | ㅎ | x/h |
| ㄲ | k |    |    |
| ㄸ | t |    |    |
| ㅃ | p |    |    |
| ㅆ | s/sj |  |   |
| ㅉ | zj |   |    |

### Vowels in ASCII compatible Modern Korean Transcription

| H | T | H | T |
--- | --- | --- | ---
ㅏ | a | ㅘ | wa |
ㅣ | i | ㅟ | wi |
ㅡ | u | ㅜ | wu |
ㅔ | e | ㅞ | we |
ㅐ | e | ㅙ | we |
ㅓ | o | ㅝ | wo |
ㆍ | oh | ㅗ | woh |
| ㅑ | ya |
| ㅢ | yi |
| ㅠ | yu |
| ㅖ | ye |
| ㅒ | ye |
| ㅕ | yo |
| ㅛ | yoh |


* Apostrophe is used to indicate abbreviation instead of for the transliteration of ⟨ㅇ⟩.
* Are-a is unused.

### Vowels in Middle Korean Transliteration

| H | T | H | T |
--- | --- | --- | ---
ㅏ  | a | ㅘ | ôa
ㅓ  | e | ㅝ | ûe
ㆍ | o | ㅗ | ô
ㅡ  | u | ㅜ | û
ㅐ | ai | ㅙ | ôai
ㅔ | ei | ㅞ | ûei
ㆎ | oi | ㅚ | ôi
ㅢ | ui | ㅟ | ûi
 ㅑ | ya | ㆇ | yôya
 ㅕ | ye | ㆊ | yûye
 ㅛ | yô |   | 
 ㅠ | yû |   | 
 ㅒ | yai | ㆈ | yôyai
 ㅖ | yei | ㆋ | yûyei
 ㆉ | yôi |   | 
 ㆌ | yûi |   | 
 
* Unspecified vowel clusters are transliterated as the combination of each traditionally minimal vowels.

### Miscellaneous

* Halfwidth font is strogly preferred.

## Comparison

The romanization for Middle Korean introduced here covers more letter than Yale Romanization and differs in a few ways. Here are some very brief examples.

| Text | Here (Middle) | Yale |
| - | - | - |
| ㅇ | ʼ(') | (G) |
| ㅗ | ô(wo) | (w)o |
| ㅜ | û(wu) | (w)u |
| ㅐ | ai | ay |
| ㅔ | ei | ey |
| ㄱ | q | k |
| ㄷ | d | t |
| ㅂ | b | p |
| ㆁ | g/ng | ng |
| ㅈ | z | c |
| ㅉ | zz | cc |
| ㅿ | j | z |
| ㆆ | ˮ(") | q |
| (ㅅ) | n/d | (q) |
| ㅸ | v | W |
______

## FAQ

* What about Cia-cia?

That's not what this system addresses.
This is a Korean Romanization system.

* ...Did you just use ⟨g⟩ instead of ⟨ng⟩ and ⟨q⟩ instead of ⟨g⟩?

Yes. Yes, we did.

* Why not use both ⟨k⟩/⟨g⟩ for ⟨ㄱ⟩, ⟨t⟩/⟨d⟩ for ⟨ㄷ⟩, and ⟨p⟩/⟨b⟩ for ⟨ㅂ⟩?

Were we to make a system that translated Korean to English, we would happily just use the revised romanization of korean (again, if using breves), and you should, too. But the purpose of writing systems including Korean ones is not to depict phones or phonemes but to convey granular meaning, or morphophonemes. Using both letters for the phonemes will help understand more Korean at first, but will not only lose semantic meaning making it hard to understand for Korean users, but be very inconsistent as one learns more of the language. That Koreans pronounce voiced plosives with [˩] tone voicelessly when it's the initial letter of a word is something you'll have to learn when learning the Korean language, not the writing system.

* Why not ⟨k⟩ for ⟨ㄱ⟩, ⟨kh⟩ for ⟨ㅋ⟩, and ⟨kk⟩ for ⟨ㄲ⟩? (also applies for t/th/d, p/ph/b)

Because we can reduce the number of double letters per phoneme. Because it feels intuitive to use ⟨g⟩ for ⟨ㄱ⟩, since ⟨ㄱ⟩ is more often pronounced as /g/, it can be remapped. Also, this would make how ⟨ㅅ⟩ /sʰ/ and ⟨ㅆ⟩ /s/ are mapped counter-intuitive, no matter what.

* Why not ⟨k⟩ for ⟨ㄱ⟩, ⟨kh⟩ for ⟨ㅋ⟩, and ⟨g⟩ for ⟨ㄲ⟩, like Thai? It would also be more intuitive for Chinese users. (also applies for t/th/d, p/ph/b)

It will be, but it will be less intuitive for Korean users. As mentioned above, it feels slightly more intuitive to use ⟨g⟩ for ⟨ㄱ⟩, since ⟨ㄱ⟩ is more often pronounced as /g/. There not being a way to intuitively and coherently map ⟨ㅅ⟩ /sʰ/ and ⟨ㅆ⟩ /s/ is also a factor.

* Why ⟨c⟩, not ⟨ch⟩?

There is no particular reason in Korean language to use multiple letters against the design requirement, and it doesn't feel too far-fetched.

* Why ⟨q⟩ for ⟨ㄱ⟩? or Why ⟨g⟩, for ⟨ㆁ⟩?

⟨g⟩ was in use for ⟨ㆁ⟩ to meet design requirement. 
It needs be used exclusively for the character to avoid use of apostrophe.

* Why ⟨g⟩ and ⟨ng⟩, not ⟨ŋ⟩?

It's not a commonly used letter, so it's hard to type that letter. 
Also, you can't type that with Qwerty. 
This is important for more people than you might imagine.

* Why allow both ⟨ng⟩ and ⟨g⟩?

Although using ⟨ng⟩ does not meet design requirement, it does fit well, and people like it that way. 
But if this system were to be used for long, it's likely that providing the option to use ⟨g⟩ instead of ⟨ng⟩ will come in handy.

* Why are Old Korean letters here?/Why are some Latin letters unused for Modern Korean?

Because Old Korean is used by some people, and this system is for (almost) everyone.

* Why is there an addon for the archaic "s" but none for tense pronunciations?

This is not a spelling reform. 
The addons included here take advantage of writing in the unit of alphabets to write what should have been written, but couldn't have been due to the improper system in use.

* You have Hangul. Why are you doing this?

We need something like this. We hope to provide a template for the solution to the problems regarding writing Korean which this system tries to solve for.
Firstly, you can't type Hangul with Qwerty layout on barebone computing systems, so you need an ASCII compatible romanization system. 
Unlike European letter systems traditional Korean scripts require a little more powerful input method engine.
Secondly, people starting to learn Korean don't have a decent writing system to start out with. 
Yale romanization is the only system that is in use and is "actually" usable, but it is outdated and not very often used. RR is absurd, and MR does not handle semantics properly.
Hangul isn't a great fit for the Korean language either. 
Because the characters are written in syllabic blocks, it can't handle the frequent sandhis properly. For Middle Korean and Cia-cia, combination of two different letters are used to write a single phoneme for an inadequate reason, which makes Hangul a mediocre choice.
To meet every demand, we propose these systems, to be selectively used as needed.

* About ⟨ㅢ⟩...

Yeah, about that. We don't think that's a topic to be dealt with romanization but rather in stadardizing Korean pronunciation. 

* About 사이시옷 "s"...

Further improvement from what is suggested here is not a part of a Romanization system but a separate orthographic matter.

* About the difference between the actual pronunciation and the written form of tensed consonants...

Likewise, it's not what Romanization is about, and it should be dealt with separately. For the same reason, which system to use or whether to use the system or not in certain situation is not a part of this system.

## To read more about the topic

Heselwood, B. (2013). Phonetic Transcription in Theory and Practice. Edinburgh University Press.

정경일. (2013). 규범적 측면에서 본 로마자표기법의 제 문제. 언어학, 21(1), 139-154.

EDWARD F. KLEIN.(1982).Romanization of Korean.코리아저널,22(8),16-23.

Kyung Il Jung. (2013). Some Issues on the Korean Romanization as the Normative Law. The Linguistic Association of Korea Journal, 21(1), 139-154.

李相億. "국어의 로마자 표기법 문제 종합 검토." 언어와 언어학 7.- (1981): 15-48. "누구를 위하여 로마자 표기를 하여야 하나?".
