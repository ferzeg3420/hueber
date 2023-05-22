# hueber
randomly picks a German exercise from Hueber online (script only works on MacOS)

The way to make this script available in your OS is by first getting rid of anything resembling my file system and adapting it to your file system. So any lines with the words: fernandozegada (if there is anything, I'm actually not sure) should be changed. Then, I believe I am using MacOS's `say`, which you need to change to whatever works in your system (look up text-to-speech in `insert your system`). And finally I'm using MacOS `open` command. So anything that says `open -a ` should be changed to however you open stuff in your system.

This is a mostly posix shell script, so it should work fine with bash and zsh. I'm using sort -R (I think) which I don't believe is posix compliant so if you need this to be absolutely posix compliant, you need to use awk or something else to get the effect of sort -R (btw shuffle would work well in place of sort -R but also not posix compliant). 

chmod +x to make this script executable

If you're on windows, you need to install git-bash and figure out how to modify the script in the cases mentioned above.
