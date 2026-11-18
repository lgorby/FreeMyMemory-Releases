# Security

## Reporting a problem

If you think you've found a security problem in FreeMyMemory, **please don't open a public issue.**

Tell us privately instead:
- **Preferred:** on this repository, open the **Security** tab, then **Report a vulnerability**. Only the maintainer can see your report.
- **Or e-mail:** FreeMyMemorySupport@gmail.com, with "Security" in the subject.

Please include:
- the FreeMyMemory version (Settings → About);
- your Windows version;
- the steps that show the problem.

Don't send passwords, tokens or personal files.

We'll reply as soon as we can and keep you updated while it's fixed. There is no bug bounty.

## Checking a download

Every release lists the SHA-256 of `FreeMyMemory.exe`. Before you run a download, check it with either command:

```
certutil -hashfile FreeMyMemory.exe SHA256
Get-FileHash .\FreeMyMemory.exe -Algorithm SHA256
```

If the result doesn't match the release page, don't run the file. Only download FreeMyMemory from this page or from https://freemymemory.com.
