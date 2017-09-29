## Ultibo port of Ararat Synapse

This is the Ultibo port of the Ararat Synapse synchronyous socket library, all features except SSL/TLS are available including serial port support.

A number of examples from the original Synapse download have been ported to Ultibo and can be found at:

   https://github.com/ultibohub/Examples/tree/master/Synapse

A zip file containing the source plus examples and documentation of the latest release can be found at:

   https://github.com/ultibohub/AraratSynapse/releases

Below is the original README.txt from the Synapse download package.

### Synapse - The synchronyous socket library.

File content:

1. About Synapse
2. Distribution package
3. Installation instructions
4. Usage notes

Synapse homesite is at http://synapse.ararat.cz/
On homesite is Wiki documentation system and other informations.

1. About Synapse

SYNAPSE library aims to create complete library of classes and functions 
that would markedly simplify application programming of network communication 
using Winsock.

2. Distribution package

Package must be unpacked with subdirectories.
There are these derectories:

```
\Html               - Off-line version of Synapse support WEB
\Source             - Synapse source code
\Source\Lib         - shared units
\Source\Demo        - Synapse demo applications
```

3. Installation instructions

There aren't any difficulties with current distribution other than add
`\Source\Lib` directory to library or search path. (...or you can simply put all 
required Synapse files into your project directory.)

4. Usage notes

Simply write BLCKSOCK to USES section in your source code 
(or any other unit from package, when you need it).
To read documentation, simply open INDEX.HTM file (in HTML subdirectory)
on your HTML browser.

Last update 2006-09-12
