# Simple English Dictionary
_Usecase:_ You are used to reading complex English but need to write texts for a beginner audience. Sure, vocabulary analyzers such as textinspector.com and AntWordProfiler exist but they require swapping tools and getting used to a new workflow.

Wouldn't it be nice to see when you are using complex English during writing? This is where these dictionary files come in.
By installing the provided files in your text-processor and selecting it in your spellchecker, your text-processor will start showing
English words of C1 language level and higher as incorrect. See a red squiggly line? Change the word!  Unintrusive, simple, and just like you used to.

To check "real" spelling errors, simply switch to a real English dictionary again.

# Installation
## Onlyoffice
Onlyoffice desktop does not support installation of dictionaries at the time of writing. However, there is a workaround ![here](https://community.onlyoffice.com/t/custom-dictionaries/2916/9).
In case you installed onlyoffice as a Flatpack, the dictionaries might be located at `/var/lib/flatpak/app/org.onlyoffice.desktopeditors/x86_64/stable/<VERYLONGIDENTIFIER>/files/bin/opt/onlyoffice/desktopeditors/dictionaries/`.
`<VERYLONGIDENTIFIER>` is a placeholder for the Flatpak ID.

To install the dictionary, remove the contents of an unneeded language and replace them with the .dic and .aff file provided in this repository. Make sure to rename both files to have the same name as the folder while keeping the .dic/.aff endings.

## Libreoffice
Libreoffice installs dictionaries using .oxt extentions. I'm not using it anymore so good luck figuring out how to make one <3

# Credits
This list of words was created using the CEFR-J Vocabulary Profile (ver 1.5), a vocabulary list annotated with A1 to B2 classifications for each word.
In addition, kind thanks to ![this](https://web.archive.org/web/20130810100226/http://www.suares.com/index.php?page_id=25&news_id=233) useful explanation of hunspell files.
