Soiled is a TELNET client and terminal emulator (VT100, VT102, xterm etc).

The code repository also contains a server, [MCTS](MCTS.md) designed to test mud clients (TELNET clients in line-by-line mode with extra features) and various mud related protocols.

Soiled is implemented in haXe and it can be run in flash player, version 9 and later, making it a good way to let people easily access TELNET based services via webpages.

Soiled has a few features making it suitable for playing muds, it is able to redraw the input line and the prompt when new text arrives from the server, it has support for macros and it keeps a history of both commands entered and text received.

Unlike many mud clients it also supports char-by-char mode and therefor it can be used to access programs, such as vim, and play games like NetHack (with DECGraphics and all the colour one wants).

The terminal emulator has support for most of the commonly used VT100, VT102 and xterm control sequences. See the [Features](Features.md) page for more information.



&lt;wiki:gadget url="http://www.ohloh.net/p/270540/widgets/project\_users\_logo.xml" height="43"  border="0" /&gt;