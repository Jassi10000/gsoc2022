# gsoc2022
Google Summer of Code 2022 ideas - Neutralinojs

## Make Neutralinojs compatible with older Windows versions

Issue: https://github.com/neutralinojs/neutralinojs/issues/486

Neutralinojs is tested on Windows 10 and 11, but it is not well-tested 
with previous Windows versions. The goal of this idea is to update Neutralinojs framework
source, build scripts, and DevOps workflow to officially support older Windows versions.

Areas: Windows API, DevOps, and Configuration

## Support Unicode characters in Neutralinojs Windows version

Issue: https://github.com/neutralinojs/neutralinojs/issues/613

Unicode characters work without any issue on Neutralinojs Linux and macOS versions. But, 
Neutralinojs Windows version doesn't render Unicode characters correctly.
The goal of this task is to use Windows Unicode APIs and fully support Unicode in the Neutralinojs Windows version.

Areas: Windows API, Refactoring, and Text Encoding


## Fix os.setTray function problem for older macOS versions

Issue: https://github.com/neutralinojs/neutralinojs/issues/615

The os.setTray function fails on macOS Catalina and some other versions.
The goal of this task to debug the Neutralinojs macOS binary on different macOS versions and 
apply a generic solution.

Areas: Cocoa API and Debugging
