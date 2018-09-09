# vocab
A single assistant for helping you improve your vocabulary.

## Why am I starting this project
I love opensource community so much.
I love learning languages and building my vocabulary.
I face many problems everyday in my vocabulary learning flow.
I want to join with others to make a tool that would help us all improve our vocabulary easier.

## principles
There should be no server or anything. Everything should be completely local. Protecting users privacy is red line.
Everything should remain completely free. The code/name/browser extention or anything should never ever be sold to any disgusting tracking company.

## roadmap
### fetching data
- [ ] fetching word information from google define
     - [ ] using a crafted url and a simple get request and cleaning up the html result with bs4.(preferred method)
     - [ ] using selenium.(last resort)
- [ ] fetching from urban dictionary
- [ ] fetching from the free dictionary
- [ ] fetching from merriam-webster
- [ ] fetching from wikitionary
### storing data
- [ ] using sqlite
### word of the day and stuff in terminal
I aliased clear to print a random word with it's definition after doing clear. But I notice that I ignore it every time. I also added something to add a word on top of my terminal evertime I open a new terminal but I also tend to ignore that. I don't know if others have the same experience about this. And Ideas? suggestions?
### integration with other applications
I think this is so useful if we can integrate this with chat/mail clients and browsers so that every word we type we see it's synonym sugested and so we will use more complex and more specific synonyms instead of simple english words. I think this is extremely good for learning.
- [ ] weechat plugin
  another feature would be to work with some bots that lookup definitions. so whenever we lookup the definition of a word in a channel using a bot the plugin will lookup the word and insert it to the apps database.
- [ ] firefox plugin that would suggest alternative words from local database whenever we type.
- [ ] chrome plugin
### loading external wordsets such as GRE
### customization
- [ ] # of synonyms
- [ ] # of antonyms
- [ ] store the origin of the word
- [ ] # of examples
- [ ] # of definitions
- [ ] # translations
- [ ] # audio file for pronunciation
- [ ] Phonetics
