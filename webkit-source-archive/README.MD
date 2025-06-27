webkit-source-archive
=====================

Classical works of software: WebKit.

This repository contains what I can best find as the original source code for the WebKit browser engine. WebKit is a classical work - the original codebase of Safari, Chrome (now: Blink) and Bun's JS runtime (JavaScriptCore).

> The code that would become WebKit began in 1998 as the KDE HTML (KHTML) layout engine and KDE JavaScript (KJS) engine. The WebKit project was started within Apple by Lisa Melton[17] on June 25, 2001,[18][19] as a fork of KHTML and KJS. Melton explained in an e-mail to KDE developers[1] that KHTML and KJS allowed easier development than other available technologies by virtue of being small (fewer than 140,000 lines of code), cleanly designed and standards-compliant. KHTML and KJS were ported to macOS with the help of an adapter library and renamed WebCore and JavaScriptCore

This repository contains a few directories, as I'm trying to find the best canonical "first implementation":

 - the original source of KHTML, as forked by Apple.
 - the initial revision of WebKit.
 - the first stable build of the WebKit engine. 

## Source codes.

### KDE/KHTML.

**Source**: `kde-html/`

This was archived with thanks to [this post](https://retrocomputing.stackexchange.com/questions/27643/where-can-i-find-the-code-of-the-ancestors-of-the-webkit-family-of-web-browsers?utm_source=chatgpt.com). 

This repository contains KDE v1, at commit `bffedd01a749e5d33e257cacf1cd19b1e19c4baf` (retrospective since git didn't exist at the time; don't ask me for which VCS this code was originally in).

### WebKit.

**Source**: `webkit-initial-rev/`

WebKit's source repository was originally tracked in SVN, and migrated to Git. The code was archived from the commit below.

```
commit a063c2b75ddebd1edfe9c54c428d762bdb61f794 (HEAD)
Author: Ken Kocienda <XXXXXX>
Date:   Fri Aug 24 14:24:40 2001 +0000

    Initial revision
```

## Lore.

> I was part of the KDE project when KHTML was created. At the time, we were all flabbergasted that a small team of volunteers could build a fully functional web renderer, even if the year was 2000 and the internet was a lot simpler. We all thought this was the task of megacorps.
>
> The web browser was named Konqueror, a cheeky followup to Navigator and Explorer.
>
> Anyway. Most people don't know what KHTML is in the above list, but have a helping of history :)
