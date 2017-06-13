# chrome-debug-bug

This exposes a bug in [vscode-chrome-debug-core](https://github.com/Microsoft/vscode-chrome-debug-core), specifically for issue [#212](https://github.com/Microsoft/vscode-chrome-debug-core/issues/212).

## Steps to reproduce:

1. Clone this repository.
2. Run `npm install`.
3. In the VSCode debug section, run `Node`. This launches the web server.
4. In the VSCode debug section, run `Launch Chrome`.
5. Go to the Debug Console in VSCode. Click here:

![](http://i.imgur.com/y9yRTpg.png)

Then it produces this error:

![](http://i.imgur.com/Ja6ewXn.png)
