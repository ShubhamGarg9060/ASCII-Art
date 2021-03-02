# ASCII-Art
Creating an ASCII Art using python module pyfiglet that will make the coding experience much creative. ASCII Art means showing a word using some pattern of special symbols which is specially made for the creative coding experience andenhances the overall look of the code.
# Required Module
## pyfiglet:
For creating ASCII Art we require a python module pyfiglet.

## Installation
```pip install pyfiglet```

## Code to create ASCII Art
```
import pyfiglet
text = pyfiglet.figlet_format("Python")
print(text)
```

## Change font style
```
#import pyfiglet module
import pyfiglet
text = pyfiglet.figlet_format("Python" , font='digital')
print(text)
```

## List of ASCII Art styles
We can get all the list of available ASCII Art style using the method getFonts() of pyfiglet module.

```
#import pyfiglet module
import pyfiglet
fonts = pyfiglet.FigletFont.getFonts()
fonts = list(fonts)
print(len(fonts))
```

# Happy Learning!
