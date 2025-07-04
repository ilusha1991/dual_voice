# Dual Voice for NVDA #

Dual voice is an addon that make it possible to use two different voices in NVDA. Currently both voices must support SAPI5 standard for reading two languages, one for reading a Latin script and another for reading a non-Latin script. For example, a user can select a voice for reading English as a language with the Latin writing script and select a voice for reading Persian (my language) as a language with the non-Latin writing script. 
Some of the supported languages with the Latin writing script are English, Czech, Croatian, Dutch, Finnish, French, German, Italian, Polish, Portuguese, Slovenian, Spanish, and Turkish.
On the other hand, some of the supported languages with the non-Latin script are Arabic, Belarusian, Bulgarian, Chinese, Greek, Hebrew, Japanese, Korean, Persian, Russian, and Ukrainian.



You can download the [latest version of the Dual Voice for NVDA](https://github.com/Mahmood-Taghavi/dual_voice/releases/download/v5.3/dual_voice-5.3.nvda-addon) which requires NVDA version 2021.1 or later. 
                  

Note 1: You can now use a custom dialog box entitled "Dual voice" in the NVDA menu to select the secondary voice and setting of the Dual voice.
Note 2: A complimentary free software namely SAPI_Unifier is designed to add support for Windows 10 oneCore voices and Microsoft speech platform (speech server) voices to the Dual Voice for NVDA. So, I suggest using [SAPI_Unifier](https://mahmood-taghavi.github.io/SAPI_Unifier/) to extend the capabilities of the Dual Voice.
Note 3: The latest version of NVDA which supports Windows XP and Windows Vista is NVDA 2017.3 and the latest Dual Voice which is compatible with NVDA 2017.3 is version 3.1.
This package is distributed under the terms of the GNU General Public License, version 2. Please see the file "COPYING.txt" for further details.
Copyright © 2015-2020 Seyed Mahmood Taghavi-Shahri.
## Building
Run `scons` in the repository root to create the `.nvda-addon` package.

