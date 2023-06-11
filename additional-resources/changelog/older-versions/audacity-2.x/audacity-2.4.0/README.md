# Audacity 2.4.0

**Audacity 2.4.0 was released on 16th May 2020.**

### Checksums

```
audacity-win-2.4.0.exe 
SHA256 dc71fbfd4f6c1b921c6f8ec387125fb61f53a60abeeff30aa73e19ba675b2bec

audacity-macos-2.4.0.dmg 
SHA256 42d08496569556d22f2f22c84b9f0196ef207af1311a9089ebbfcf2af9e21922

audacity-minsrc-2.4.0.tar.xz 
SHA256 dcb85efe447e8c6fa815f5fa1c4a0678ec56fb4db52d767de2ecfb546f777878

audacity-manual-2.4.0.zip 
SHA256 3800bff937de7e8695c27dce107e5779d6d84ad2c49ef8906eb7069824209472

audacity-2.4.0.zip 
SHA256 b697958c49de95818f7322bca7a043cee1580c3ecab91d62bfb649457edd285a
```

### Changes and improvements since previous version

Audacity 2.4.0 replaces all previous versions.

* Over 100 bugs fixed since 2.3.3

Full details of new features in the visual guide to [new-features-in-audacity-2.4.0.md](new-features-in-audacity-2.4.0.md "mention")

### Supported Platforms

**Windows**

* Audacity 2.4.0 requires the CPU to support the [SSE2 ](http://en.wikipedia.org/wiki/SSE2)instruction set which should be available on any Intel hardware produced after 2001 and any AMD hardware produced after 2003.
  * To check what SSE levels your CPU supports, you can install [CPU-Z](http://www.cpuid.com/softwares/cpu-z.html).
  * If your hardware only supports SSE, you may download Audacity 2.0.6 see the [Legacy Windows](https://www.audacityteam.org/download/legacy-windows/) page on the Audacity Website.
* 2.4.0 does not support Windows XP.
  * You may try 2.2.2 on XP, but it is unsupported.

**macOS / Mac OS X**

* Audacity 2.4.0 is for Intel Macs running OS X 10.7 and later and macOS including Catalina.
  * There are legacy versions for older OS X at [https://audacityteam.org/download/legacy-mac/](https://audacityteam.org/download/legacy-mac/).

**Linux**

* Linux support is tested on Ubuntu Linux. Use the CMake build. The Automake build is no longer reliable.
  * Audacity may compile on Gentoo, Debian, Mint.
  * Audacity does not currently compile on SuSE Linux.

### Interactive Buglist Page

_We probably track more bugs than you are interested in..._

On the dynamic buglist page you can select to view:

* Complete list of bugs in 2.3.3 that we have fixed for 2.4.0
* Known bugs on the OS you use Mac, Windows or Linux.
* Known bugs to do with accessibility or localization.
* Workarounds for some bugs.
* Serious bugs and less serious bugs.

You can choose various combinations of these. However, there are probably too many minor bugs and too much detail on that dynamic buglist page for most users.

We **do** use this detail in our own QA work.

### Highlighted Issues

* Below are listed what we believe are the most common and important issues with 2.4.0 for most users.

**Accessibility**

* Less of Audacity is properly accessible to visually impaired users than we would like. Currently the best supported platform for accessibility is Windows. We lost a lot of custom accessibility programming when we had to move to a more recent version of the wxWidgets library.

**Internationalization**

* Audacity is only partially translated in many languages. We also have some issues, for example, with Right-To-Left Languages.

**Selected Bugzilla-Tracked Bugs**

<table data-header-hidden><thead><tr><th width="113"></th><th width="79"></th><th width="126"></th><th></th></tr></thead><tbody><tr><td><strong>ID</strong></td><td><strong>P</strong></td><td><strong>Status</strong></td><td><strong>Summary (5 tasks)</strong> <a href="http://bugzilla.audacityteam.org/buglist.cgi?&#x26;field0-0-0=bug_id&#x26;type0-0-0=equals&#x26;value0-0-0=276&#x26;field0-0-1=bug_id&#x26;type0-0-1=equals&#x26;value0-0-1=421&#x26;field0-0-2=bug_id&#x26;type0-0-2=equals&#x26;value0-0-2=1986&#x26;field0-0-3=bug_id&#x26;type0-0-3=equals&#x26;value0-0-3=2212&#x26;field0-0-4=bug_id&#x26;type0-0-4=equals&#x26;value0-0-4=2400&#x26;field0-1-0=bug_status&#x26;type0-1-0=notequals&#x26;value0-1-0=CLOSED"><strong>⇒</strong></a></td></tr><tr><td><a href="http://bugzilla.audacityteam.org/show_bug.cgi?id=2400">2400</a></td><td>P1</td><td>RESOLVED</td><td>Mac: Zoomed in, playback meters slow to respond.</td></tr><tr><td><a href="http://bugzilla.audacityteam.org/show_bug.cgi?id=1986">1986</a></td><td>P2</td><td>RESOLVED</td><td>Linux: Unwanted messages in console.</td></tr><tr><td><a href="http://bugzilla.audacityteam.org/show_bug.cgi?id=421">421</a></td><td>P2</td><td>RESOLVED</td><td>Crash importing malformed MP3 file using libmad</td></tr><tr><td><a href="http://bugzilla.audacityteam.org/show_bug.cgi?id=2212">2212</a></td><td>P2</td><td>RESOLVED</td><td>Mac: Keyboard tabbing in Timer Record stuck in left hand panel.</td></tr><tr><td><a href="http://bugzilla.audacityteam.org/show_bug.cgi?id=276">276</a></td><td>P3</td><td>NEW</td><td>Linux: PULSE-AUDIO issues. Freeze repeatedly starting/stopping streams</td></tr></tbody></table>

* Click on the bug numbers to see work done on these bugs.
