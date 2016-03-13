# BeeGo framework mini example

This repo aims to eliminate go-lang-plugin-org/go-lang-idea-plugin#2360.

Steps to reproduce debugger attachment problems:

1. Set up project in IntelliJ Idea 15.0.4 on El Capitan 10.11.3 (15D21) with bundled JDK.
2. Set up example breakpoints (see screenshot)
3. Try out to run zero-configuration debugging by pressing <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>D</kbd>

First run attaches debugger successfully.
Next time debugger will be attached randomly.

Go 1.6 from `homebrew` used in this example:

```bash
$ go version
go version go1.6 darwin/amd64
```
