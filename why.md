## Original Design Goals

* Don't be a D.
* Make an alphabetic transliteration system, not a spelling reform
* Use Latin letters
* Use only the standard Latin Letters for the transliteration of modern Korean
* Avoid using two or more letters for a single phoneme
* Make it computer friendly
* Respect coalescence and the historic usage of Hangeul and Hunminjeongeum
* Respect the historic usage of Latin Letters
* Be Korean while designing
* Be intuitive for Korean users
* Be intuitive for English users
* Be okay for Chinese

## ...Why?

There are some transcription systems in use, the most common being Revised Romanization of Korean, but they just don't work. So I decided to make a [better one that works for everyone](https://xkcd.com/927/).

As for the RRK, the transcription system relies on the pronunciation, but also because there's not enough correlation between the romanized forms and the form written in Korea-originated scripts. Korean is a language with numerous liasons and sandhis. Phonetic transcription makes it impossible to comprehend what the words are. They tried to mitigate that by making a complex hyphenation system that is only used for the romanization, and is not very well kept anyway. All in all, it kinda works when you're trying to make someone pronounce a meaningless phrase without knowing what it means. It's an absolutely great tool for fooling western foreigners into thinking that they understand Korean phonetics–as long as ⟨ĕ⟩, ⟨ŏ⟩, and ⟨ŭ⟩ are used instead of ⟨ae⟩, ⟨eo⟩, and ⟨eu⟩. There is one big flaw to the RRK. It’s made for western foreigners that are not willing to spend any time getting used to Korean language, and that only. It’s a niche. To its creators' defense, people at the time did not think foreigners visiting Korea are in the slightest interested in Korean language, and were completely careless about non-western foreigners. The problem is that it's a weird use case for something that is mandated to be used for everything. RRK is complicated to use, phonologically inconsistent, and caters only to some western tourists. On the contrary, most foreigners in Korea are from East Asia and Southeast Asia, and they speak not "some foreign language" but their own respective languages, each with their own writing system and pronunciation.

Almost all other romanization systems that I'd looked through look like they were made by people who seem to think that American English is the only language using Latin Alphabet or have no idea what they're doing. Although I'm most certainly one of them, I thought maybe I can make it better. Honestly, what I originally intended designing was a system where I could use ⟨zz⟩ for ⟨ㅉ⟩, which was most intuitive (as can be seen in [the frequenct use of the word ⟨zzang⟩](https://www.google.com/search?q=zzang) despite it having never been a part of any major romanization attempt). I also thought it would work better when teaching Korean if I actually could integrate it to a working system. It took longer than I initially imagined, but I somehow got here.

Yale Romanization of Korean is used often and it's a good system overall. But it also doesn't get much support from Korea just because it wasn't made in or by a Korean, which is quite significant to the point that RRK is being more often used where it should not be. The more time I spent on this subject, the more I realized it made quite a lot of sense. But comparatively, there are slight problems regarding intuitivity, casual readability, and effeciency, all of which are not critical in academic use case but more necessary in everyday use. 

To fix things for good, I made this for a general use, to target 1. Aiding Foreigners (willing to learning Korean) in a culture neutral way by designing around Korean language instead of western use (more fit in an environment where Korean culture has a significant influence around the world), 2. Aiding foreigners willing to learning Korean script, 3. Scholarly use, 4. For creative use in fictional situations where Hangul didn’t exist, and 5. For Koreans trying to look back on their own language from a foreign perspective. Although the system I was making looked completely different at first, it started looking more like Yale's and in the end, the differences were minimal.

The major differences are that
1. transliterations for ⟨ㅓ⟩ and ⟨ㅡ⟩ are switched,
2. semivowel /j/ is written as ⟨j⟩ in coda to indicate change in articulation and to refrain from using too many transliteration for ⟨ㅇ⟩,
3. ⟨ㅇ⟩ is transliterated with ⟨'⟩,
4. ⟨ㄱ⟩ is transliterated with ⟨q⟩ to save ⟨g⟩ for /ŋ/,
5. and ⟨ㄷ⟩, ⟨ㅂ⟩, and ⟨ㅈ⟩ are transliterated with ⟨d⟩, ⟨b⟩, and ⟨z⟩ to make it more intuitive.

Switching Latin letter for ⟨ㅓ⟩ and ⟨ㅡ⟩ was what made me publish the system. Although I have approached rather naïvely, the switch seemed to illustrate well the pronunciation change of ⟨ㅢ⟩, and felt like a novel approach. There are also other interesting parts of the system, some of which may not look great to some. Because they are the reason the system is being published, I've introduced them in the tl;dr section, just in case they may help future designers make decisions. As such, the system is completely free to use, modify, etc. without warranty or liability on me.
