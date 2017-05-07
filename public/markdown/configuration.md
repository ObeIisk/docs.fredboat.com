# Configuration Commands

The following commands can be used to change FredBoat♪♪'s behaviour.

## Guild settings configuration
 | Command                    | Description                                                           | Example usage                               |
 |----------------------------|-----------------------------------------------------------------------|---------------------------------------------|
| ;;config                     | Displays the current *auto_resume* and *track_announce* configuration of FredBoat♪♪ within this guild.                 | ;;config 
| ;;config track_announce ***true/false****                     | If enabled: The name of the track will be announced in the channel every time a new track is starting to play.                 | ;;config track_announce false
| ;;config auto_resume ***true/false****                     | If enabled: The bot will start playing music again if a user enters the voice channel.                   | ;;config auto_resume  true

*(***true*** means the setting is enabled and ***false*** means it's disabled)

### Viewing and changing the guild settings configuration
 
To view the guild settings configuration, use the `;;config` command:

```;;config```

FredBoat♪♪ will then respond with the current configuration for this guild:

```
Configuration for FredBoat Hangout:
track_announce = false
auto_resume = true
```
Let's say you want the new tracks to be announced once they start playing, then you will have to use the `;;config track_announce` command:

```;;config track_announce true```

```
Frederikam:  track_announce is now set to true.
```


Remember that you must have `Administrator` permissions to be able to change the configuration of FredBoat♪♪.


## Language settings configuration

FredBoat supports several user-contributed languages that you can select with this command.
Translating FredBoat is a community project, so translations may not be 100% accurate or complete. Missing translations may be contributed at https://crowdin.com/project/fredboat.

[![Crowdin](https://d322cqt584bo4o.cloudfront.net/fredboat/localized.svg)](https://crowdin.com/project/fredboat)

 | Command                    | Description                                                           | Example usage                               |
 |----------------------------|-----------------------------------------------------------------------|---------------------------------------------|
| ;;lang                    | Displays information about the ;;lang command and the list of currently supported languages. | ;;lang
 | ;;lang ***code***                    | Selects a language profile for the bot's responses. Click [here](https://hastebin.com/isebotirah.pas) to view the list of supported languages.                 | ;;lang en_US
 
 
### Changing the bot's language
 
In order to change FredBoat's language setting, you will first have to find your language code either [here](https://hastebin.com/isebotirah.pas) or by using `;;lang` which will make the bot respond with the following message:
 
 ```
FredBoat supports several user-contributed languages that you can select with this command. Users on this server can select a language with `;;lang <code>` Here is the full list of supported languages:

bg_BG - български език
ca_ES - Catalan
cs_CZ - Čeština
cy_GB - Cymraeg
da_DK - Dansk
de_DE - Deutsch
en_PT - Pirate English
en_TS - Tsundere English
en_US - English
es_ES - Español
fr_FR - Français
he_IL - עברית
id_ID - Bahasa Indonesia
it_IT - Italiano
ko_KR - 한국어
nl_NL - Nederlands
pl_PL - Polski
pt_BR - Português (Brazil)
pt_PT - Português
ro_RO - Română
ru_RU - Русский
sv_SE - Svenska
tr_TR - Türkçe
vi_VN - Tiếng Việt
zh_TW - 繁體中文

Translations may not be 100% accurate or complete. Missing translations may be contributed at https://crowdin.com/project/fredboat.
```

Now if you chose to set the bot's language to German, then the next step will be:

```
;;lang de_DE
```

The bot will then send a confirmation that the language has been successfully changed:

```
Frederikam:  Sprache wurde auf Deutsch geändert.
```

[Help us translate Fredboat♪♪!](https://crowdin.com/project/fredboat)

[![Crowdin](https://d322cqt584bo4o.cloudfront.net/fredboat/localized.svg)](https://crowdin.com/project/fredboat)

[![Crowdin Logo](https://i.imgur.com/0Hef2Bc.png)](https://crowdin.com/project/fredboat)
