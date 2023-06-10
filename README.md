
# ost - Oscar's Saying Tool
Provides straightfoward Text-to-Speech via say. 

## Platform details
Written originally for macOS; should work for GNU/Linux with [say](https://manpages.org/say) installed (check your package manager). It may be possible to utilize this alternate say package upon Windows too by utilizing the [GNUstep windows installer](https://gnustep.github.io/windows/installer.html) however, this has not yet been tested.

### For Windows users: 
You may choose to try the path above or, install [zsh](https://walterteng.com/using-zsh-on-windows) and [wsay](https://github.com/p-groarke/wsay). Then update the ost file via a global search-and-replace in order to add the letter 'w' infront of all existing calls to say. Alternatively, you could just rename wsay.exe to say.exe and leave the source alone.

### GNU/Linux users: 
Of course you're free to use any speech engine you like and modify the source as needed. A couple of alternatives are [espeak](https://espeak.sourceforge.net/) and [espeak-ng](https://github.com/espeak-ng/espeak-ng).

## Installation
Assuming you don't have git installed, to install: click the green [ Code ] button and select Download ZIP. Extract and then via Terminal type:
```
cd Downloads/ost-mvp/
chmod +x ost
sudo mv ost /usr/local/bin/
```
You will be prompted for your account password.
>Note: if you don't want to provide your account password in order to make the tool accessable via the run command below then, you can (after issuing cd Downloads/ost-mvp/) simply type: ```zsh ost``` and the program will still run, by default under macOS and also, under any equipped Windows or GNU/Linux computer.

If the destination does not exist:
```
sudo mkdir -p /usr/local/bin/
```
And repeat the mv command.

### To run:
```
ost
```

### To quit:
^c (control-C)

#### Questions or comments:
Write the man listed on the third line of the ost file.
