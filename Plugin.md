[gif-before]: https://raw.githubusercontent.com/BarracudaPff/GitHub-Static/master/ezgif.com-gif-maker.gif
[gif-after]: https://raw.githubusercontent.com/BarracudaPff/GitHub-Static/master/ezgif.com-gif-maker.gif

[gif-async]: todo
[gif-red-code]: todo
[gif-first-token]: https://github.com/BarracudaPff/GitHub-Static/raw/master/first-token.gif
[gif-auto-import]: https://github.com/BarracudaPff/GitHub-Static/raw/master/auto-imports.gif
[gif-walking-strings]: https://github.com/BarracudaPff/GitHub-Static/raw/master/template-like%20walking.gif

[img-py-icon]: https://raw.githubusercontent.com/BarracudaPff/GitHub-Static/master/redCode.svg
[img-py-red-icon]: https://raw.githubusercontent.com/BarracudaPff/GitHub-Static/master/redCode.svg

[tracker]: https://raw.githubusercontent.com/BarracudaPff/GitHub-Static/master/ezgif.com-gif-maker.gif

# Full Line Code Completion
With the Full Line plugin, you can complete not only one token, but several or even the full line at once!
> *This project is still in beta, please send your feedback to [ML Code Completion][tracker] team*

![Completion example][gif-before] ![Completion example][gif-before]

Complete free fast and smart AI-based full line code completion.
General/AI/Languages/Difference

We will be very happy for any kind of comments, suggestions and found bugs. Please send your feedback here -> [https://github.com/JetBrains/full-line][tracker]

## How to use

After installing Full Line, your local model will download automatically, and you will immediately see new suggestions in the popup.
Our suggestions are marked with ![icon][img-py-icon] or ![icon][img-py-red-icon] *(such suggestions may contain an unknown references)*

You can find full information about the plugin here -> [https://github.com/JetBrains/full-line][tracker]

*If the model failed to download, you can do it through plugin settings or by restarting the IDE*

## Settings
You can find all plugin settings at `Preferences` -> `Editor` -> `General` -> `Code Completion` -> scroll down to `Full Line`
There you can:
- Enable/disable completion
- Control maximum amount of suggestions
- Show/hide suggestions with unknown references
- Enable/disable jumping on strings

## Features

### Fully Async
Our completion is fully asynchronous and won't affect your (standard workflow/smth about performance)

![First token][gif-async]
### Smart (как сказать, что он понимает структуру кода, а нетолько текст)
Sometimes our neural network suggests identifier names, which are not present in your project (but are likely to appear). 
You can decide whether to filter them out.
- Show all - disable inspection, it will slightly improve performance.
- Decorate invalid - mark and show **red** suggestions.
- Hide invalid - hide all suggestions with unknown references.

![First token][gif-red-code]
### Token-by-token
If you need only part of suggestion - press `Tab` and select tokens one-by-one

![First token][gif-first-token]
### Auto-Imports
Just like in std completion, if you're using a class, a static method, or a static field that you haven't imported yet - we will suggest you to import all missing parts

![Auto-import][gif-auto-import]
### String jumping
While completing strings, you can edit and jump on them just like typing template

![Walking on stings][gif-walking-strings]

## Frequently Asked Questions

### Security
All parts of Full Line plugin are stateless and running locally and NEVER EVER sending/sharing/storing your code.

### Hardware
Our models weigh less than 30 MB and can run on any device (mention linux/mac/windows? android/ios? :) ).
Depending on the power of your machine, the speed of predictions may vary, be sure to contact with us if you have any problems.

### Quality
?
### Speed
?
### Languages
Currently, we support only Python language.

We have plans to add popular languages such as: (добавить про то  что модели уже есть, но мы хотим улучшить качество?)
Java, Kotlin, JS/TS, PHP, Go, C and other

### Server-completion

### Future

### Comparison?

### Help & Feedback


#TO ADD: TO BOTTOM
- Email
- Documentation
- Issue Tracker
- Forum Page
- Copyright
- Authors
