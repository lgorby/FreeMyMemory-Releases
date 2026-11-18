# FreeMyMemory — downloads

This repository holds the **downloads** of FreeMyMemory, a free Windows app that shows what is using your PC's memory and helps you free it safely. Only the program file is published here. To learn more, see **https://freemymemory.com**.

## Download

Open the [latest release](https://github.com/lgorby/FreeMyMemory-Releases/releases/latest) and, under **Assets**, click **FreeMyMemory.exe**. There is nothing to install: save it anywhere and double-click it. Each release lists one file, `FreeMyMemory.exe`, and its SHA-256 checksum. Always take a download from a release on this page or from freemymemory.com, never from anywhere else.

The "Source code" files GitHub adds to every release contain only this README and the licence, not the program.

## Check that your download is genuine

Open the folder where you saved the file, click the address bar, type `cmd` and press Enter, then run:

```
certutil -hashfile FreeMyMemory.exe SHA256
```

Or, in PowerShell in that folder:

```
Get-FileHash .\FreeMyMemory.exe -Algorithm SHA256
```

The long code it prints must match the SHA-256 shown in the release notes (capital or small letters and spaces don't matter). If it doesn't, delete the file and don't run it.

## Suggest a program

When FreeMyMemory doesn't know a program, its row offers **Suggest this program**. That opens a new issue here, filled in with the program's file name, description, company and kind. Issues are public: read it and remove anything personal before you send it. For help and questions, use the [support page](https://freemymemory.com/support.html).

## Requirements

Windows 10 (version 1809 or newer) or Windows 11, 64-bit.

## Licence

MIT. See [LICENSE](LICENSE).
