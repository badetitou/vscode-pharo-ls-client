# Changelog

## v0.0.7

This update comes from the release of the [Pharo-LanguageServer](https://github.com/badetitou/Pharo-LanguageServer).
Thus, most of the code modification can be found in the server repository.

### Users

#### DAP

- Can stepIn (into), step next (through), step out (over)
- Can access the source code of the stack element
- Show the line where the error was signaled

#### LSP

- Add the help signature feature
  - When writing a method, a help box appears with information for this methods (parameters, comment, *etc.*)

### Developers

#### DAP

- The server uses now a Debug Session
- The DAP gives correctly the socket port using LSP

## v0.0.6

### Users

#### DAP

We introduce the [DAP](https://microsoft.github.io/debug-adapter-protocol/implementors/adapters/) in the server and client.
So it is possible now to debug your Pharo application from VSCode

## v0.0.5

### Users

#### LSP

- Bug fix when using printIt and showIt command with the current editor closed (or closed and then open again)

## v0.0.4

### Users

We introduced the [LSP](https://microsoft.github.io/language-server-protocol/).
It is now possible to get helps from a Pharo image inside VScode