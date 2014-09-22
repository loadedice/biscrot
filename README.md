biscrot
=======
*I like this name, it sounds like biscuit.*

###Installation
Installation is easy, just run
`npm install -g biscrot`
(You may need to use sudo or root)

##Usage and other info
The program evokes scrot, so you need that installed. by default scrot -s is used, but you can change the arguments used. Thanks to yargs being great and stuff you can just run `biscrot -h` and it'll tell you everything you need to know about using the options you can supply to biscrot.

drag over an area, and then it magically gets uploaded to img.bi. By default it will print the url and the deletion URL into the terminal. With optional flags you can make it open in your web browser afterward (-o), which is good if you're running the command from something other than a terminal (like dmenu or something else your window manager has)

I honestly have no idea what I'm doing, don't be afraid to make an issue or submit a pull request so I can further my learning. I just like img.bi and my other script I used for uploading images in the way that this works stopped working because pomf.se was/is down. All in all I wanted to learn some node.js while making something I would actually find useful.
