# Change Log

<!-- Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file. -->

## 0.1.5

- Recognize files named \*-app.py and \*\_app.py as potentially Shiny apps, enabling the "Run Shiny App" and "Debug Shiny App" buttons. (We continue to recognize app.py, app-\*.py, and app\_\*.py.) (#19)
- Stop using an exported API from the ms-python.python extension that has been deprecated and replaced. (#19)

## 0.1.4

- No code changes; required a new version number to recover from continuous integration issue.

## 0.1.3

- Add "Debug Shiny App" button to launch Shiny apps under the Python debugger. (#17)

## 0.1.2

- Recognize files named app-\*.py and app\_\*.py as potentially Shiny apps (and enabling the "Run Shiny App" button).

## 0.1.1

- Compatibility with VS Code instances that are hosted by Posit Workbench.

## 0.1.0

- Fix Windows compatibility (issue #7, thanks @djsmith17).

## 0.0.4

- The default value for `shiny.python.port` is now `0`, which means "choose an unused port at runtime". This is convenient for running multiple apps simultaneously on the same machine. For convenience, the extension remembers each VS Code Workspace's most recent random port, and tries to use it if available.

## 0.0.3

- Initial release
