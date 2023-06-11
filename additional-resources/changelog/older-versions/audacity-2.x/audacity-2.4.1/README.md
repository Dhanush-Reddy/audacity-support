# Audacity 2.4.1

**Audacity 2.4.1 was released on 20th May 2020.**

### Checksums

```
audacity-win-2.4.1.exe - 28245064 bytes
SHA-256	dde069264974b3bf7a0b556ea3037bb424630e3112735f99129f3d84921e547f

audacity-macos-2.4.1.dmg - 39745448 bytes
SHA-256	5d340b025b80eb0c3ea41ae2487a77b86527bc8fb0e058d32e37762ac3d85575

audacity-minsrc-2.4.1.tar.xz - 11368524 bytes
SHA-256	d476e25129846108d8a57f818ea0c0b90912d3dd4127eb7365cac5fbe0458dc6

audacity-2.4.1.zip - 11636331 bytes
SHA-256	23f388b22974eb9ee05672e52d34971000e9c5656551bfe9b348e16ac1c5e495

audacity-manual-2.4.1.zip - 22600322 bytes
SHA-256	a18186de8788510a34298b857947b55e49029b622ce8e6119e53db4c427b60d5
```

### Changes and improvements since previous version

Audacity 2.4.1 replaces all previous versions. It contains a rapid fix for a serious bug in the briefly issued Audacity 2.4.0 release.

* Over 100 bugs fixed since 2.3.3

Full details of new features in the visual guide to [new-features-in-audacity-2.4.1.md](new-features-in-audacity-2.4.1.md "mention")

### Supported Platforms

**Windows**

* Audacity 2.4.1 requires the CPU to support the [SSE2 ](http://en.wikipedia.org/wiki/SSE2)instruction set which should be available on any Intel hardware produced after 2001 and any AMD hardware produced after 2003.
  * To check what SSE levels your CPU supports, you can install [CPU-Z](http://www.cpuid.com/softwares/cpu-z.html).
  * If your hardware only supports SSE, you may download Audacity 2.0.6 see the [Legacy Windows](https://www.audacityteam.org/download/legacy-windows/) page on the Audacity Website.
* 2.4.1 does not support Windows XP.
  * You may try 2.2.2 on XP, but it is unsupported.

**macOS / Mac OS X**

* Audacity 2.4.1 is for Intel Macs running OS X 10.7 and later and macOS including Catalina.
  * There are legacy versions for older OS X at [http://audacityteam.org/download/legacy-mac/](http://audacityteam.org/download/legacy-mac/).

**Linux**

* Linux support is tested on Ubuntu Linux. Use the CMake build. The Automake build is no longer reliable.
  * Audacity may compile on Gentoo, Debian, Mint.
  * Audacity does not currently compile on SuSE Linux.

### Interactive Buglist Page

_We probably track more bugs than you are interested in..._

On the dynamic buglist page you can select to view:

* Complete list of bugs in 2.3.3 that we have fixed for 2.4.1
* Known bugs on the OS you use Mac, Windows or Linux.
* Known bugs to do with accessibility or localization.
* Workarounds for some bugs.
* Serious bugs and less serious bugs.

You can choose various combinations of these. However, there are probably too many minor bugs and too much detail on that dynamic buglist page for most users.

We **do** use this detail in our own QA work.

### Highlighted Issues

* Below are listed what we believe are the most common and important issues with 2.4.1 for most users.

**Accessibility**

* Less of Audacity is properly accessible to visually impaired users than we would like. Currently the best supported platform for accessibility is Windows. We lost a lot of custom accessibility programming when we had to move to a more recent version of the wxWidgets library.

**Internationalization**

* Audacity is only partially translated in many languages. We also have some issues, for example, with Right-To-Left Languages.

**Selected Bugzilla-Tracked Bugs**

<table data-header-hidden><thead><tr><th width="116"></th><th width="78"></th><th width="133"></th><th></th></tr></thead><tbody><tr><td><strong>ID</strong></td><td><strong>P</strong></td><td><strong>Status</strong></td><td><strong>Summary (5 tasks)</strong> <a href="http://bugzilla.audacityteam.org/buglist.cgi?&#x26;field0-0-0=bug_id&#x26;type0-0-0=equals&#x26;value0-0-0=276&#x26;field0-0-1=bug_id&#x26;type0-0-1=equals&#x26;value0-0-1=421&#x26;field0-0-2=bug_id&#x26;type0-0-2=equals&#x26;value0-0-2=1986&#x26;field0-0-3=bug_id&#x26;type0-0-3=equals&#x26;value0-0-3=2212&#x26;field0-0-4=bug_id&#x26;type0-0-4=equals&#x26;value0-0-4=2400&#x26;field0-1-0=bug_status&#x26;type0-1-0=notequals&#x26;value0-1-0=CLOSED"><strong>⇒</strong></a></td></tr><tr><td><a href="http://bugzilla.audacityteam.org/show_bug.cgi?id=2400">2400</a></td><td>P1</td><td>RESOLVED</td><td>Mac: Zoomed in, playback meters slow to respond.</td></tr><tr><td><a href="http://bugzilla.audacityteam.org/show_bug.cgi?id=1986">1986</a></td><td>P2</td><td>RESOLVED</td><td>Linux: Unwanted messages in console.</td></tr><tr><td><a href="http://bugzilla.audacityteam.org/show_bug.cgi?id=421">421</a></td><td>P2</td><td>RESOLVED</td><td>Crash importing malformed MP3 file using libmad</td></tr><tr><td><a href="http://bugzilla.audacityteam.org/show_bug.cgi?id=2212">2212</a></td><td>P2</td><td>RESOLVED</td><td>Mac: Keyboard tabbing in Timer Record stuck in left hand panel.</td></tr><tr><td><a href="http://bugzilla.audacityteam.org/show_bug.cgi?id=276">276</a></td><td>P3</td><td>NEW</td><td>Linux: PULSE-AUDIO issues. Freeze repeatedly starting/stopping streams</td></tr></tbody></table>

* Click on the bug numbers to see work done on these bugs.
