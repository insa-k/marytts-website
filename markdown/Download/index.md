Title: Download

# The MARY Text-to-Speech System: Download

To install and run MARY TTS, you will need a recent [Java Runtime](http://www.java.com/getjava) installed (Java 1.6 or newer).

To install, download [MARY TTS 5.0 zip](https://github.com/downloads/marytts/marytts/marytts-5.0.zip) or [MARY TTS 5.0 tar.gz](https://github.com/downloads/marytts/marytts/marytts-5.0.tar.gz)

[MARY TTS 5.0 Release Notes (June 2012)](https://github.com/marytts/marytts/wiki/MARY-TTS-5.0)

## MARY TTS 5.0+ Releases

... are available from http://github.com/marytts/marytts.

## Older MARY Releases

| Version | Release Date | Java Version | Download | Size | |
|---|---|---|---|---|---|
| [4.3.1](https://github.com/marytts/marytts/releases/tag/v4.3.1) | 2011-11-30 | 1.6+ | [Standalone installer](http://mary.dfki.de/download/4.3.1/openmary-standalone-install-4.3.1.jar) | 41.2 MB | [Release notes](releasenotes-4.3.1.html) |

### 4.3.0

Download: [openmary-standalone-install-4.3.0.jar](http://mary.dfki.de/download/4.3.0/openmary-standalone-install-4.3.0.jar)

See the [MARY 4.3.0 Release notes](http://mary.opendfki.de/wiki/4.3.0).

### 4.2.0

Download: [openmary-standalone-install-4.2.0.jar](http://mary.dfki.de/download/4.2.0/openmary-standalone-install-4.2.0.jar)

See the [MARY 4.2.0 Release notes](http://mary.opendfki.de/wiki/4.2.0).

### 4.1.1

Download: [openmary-standalone-install-4.1.1.jar](http://mary.dfki.de/download/4.1.1/openmary-standalone-install-4.1.1.jar)

Fixed a critical bug for Windows users who got an "OutOfMemoryError" when trying to start the server with unit selection voices

* [#314 Memory mapping causes OutOfMemoryError if -Xmx is set too high](http://mary.opendfki.de/ticket/314)

For details, check the [MARY 4.1.1 Release notes](http://mary.opendfki.de/wiki/4.1.1).

### 4.1.0

Download: [openmary-standalone-install-4.1.0.jar](http://mary.dfki.de/download/4.1.0/openmary-standalone-install-4.1.0.jar)

This is a feature release, adding new features while maintaining compatibility with existing 4.0 voices.

For details, check the [MARY 4.1.0 Release notes](http://mary.opendfki.de/wiki/4.1.0)!

### 4.0.0

[openmary-standalone-install-4.0.0.jar](http://mary.dfki.de/download/4.0/openmary-standalone-install-4.0.0.jar) (32 MB)

This is the first stable release of the new 4.0 code.
MARY 4.0 is a major cleanup over previous versions of MARY TTS.
Its main features are:

* 100% Pure Java.
  All native libraries have been removed from the system.
  MARY should now run on any platform that has Java 1.5 or newer.
* Fully open source.
  All code is now open source under the  LGPL, including German TTS.
  Voices are distributed under Creative Commons or BSD licenses.
* Many languages and voices.
  In addition to several high-quality German and US English voices, this release adds four expressive British English voices built for the [SEMAINE project](http://www.semaine-project.eu/), a Turkish and a Telugu voice.
  Also, we have made it easy to add more languages and voices in the future.

MARY now comes with a toolkit for people who want to add support for new languages or build their own voices.
There is detailed documentation for

* [creating initial support for a new language](http://mary.opendfki.de/wiki/NewLanguageSupport);
* [recording and building a unit selection voice](http://mary.opendfki.de/wiki/VoiceImportToolsTutorial);
  and
* [creating an HMM-based voice from the same recordings](http://mary.opendfki.de/wiki/HMMVoiceCreationMary4.0).

More details can be found in the [MARY TTS 4.0 Release Notes](http://mary.opendfki.de/wiki/4.0.0).

### 4.0 beta

[openmary-standalone-install-4.0beta.jar](http://mary.dfki.de/download/4.0%20beta/openmary-standalone-install-4.0beta.jar) (32 MB)

This is a first beta release of the new 4.0 code.

More details can be found in the [MARY TTS 4.0 beta Release Notes](http://mary.opendfki.de/wiki/4.0beta).

NOTE: This is beta software.
It is not yet ready for production use.
You are likely to find problems, and we would appreciate if you tell us about it.
See the [development pages](http://mary.opendfki.de/) for details.

## Pre-4.0 releases

These releases are mixed open source / research license, and mostly contain native code.
This makes them more difficult to reuse and port to new platforms.
Support for these releases terminates with the publication of 4.0beta.

Older comments:

DFKI has released the core MARY system as open source, including English and Tibetan synthesis and various voices, including free unit selection voices based on the CMU Arctic databases.

In addition, German synthesis is released under a [DFKI research license](http://mary.dfki.de/download/DFKI%20MARY%20software%20user%20agreement.html).
The system can also use [MBROLA](http://tcts.fpms.ac.be/synthesis/mbrola.html) voices, under the [MBROLA license](http://mary.dfki.de/download/Mbrola%20software%20user%20agreement.html).

The interactive, web-based installer which you can download below will guide you through the installation process.
It will let you decide on the install location on your file system and will let you select the components you wish to install.
You will need to accept the licenses appropriate for the selected components before these will actually be downloaded and installed.

The system should run on MS Windows (2000 and XP, maybe others), PC-Linux, Sun Solaris, and Mac OS X.

### MARY 3.6.0

This is a minor feature release, providing one important new feature and several bugfixes over previous MARY 3.5.0.

[mary-install-3.6.0.jar](http://mary.dfki.de/download/mary-install-3.6.0.jar) (700 kB, will download only selected components)

[mary-standalone-install-3.6.0.jar](http://mary.dfki.de/download/mary-standalone-install-3.6.0.jar) (32 MB, additional voices can be downloaded during install time)


New feature:

* New tool for creating your own HMM-based voices for MARY (see tutorial at http://mary.opendfki.de/wiki/HMMVoiceCreation)
  Feedback and questions about building voices in MARY are welcome via the mary-users mailing list (http://www.dfki.de/mailman/listinfo/mary-users).

Bugfixes:

* Important for many will be that the "self-healing" capabilities of the MARY installation are now working again:
  if you install an English system but a German voice, the system detects a misconfiguration and offers to download and install the missing components, and will start up normally after that.
* the full list of bugs fixed can be found on http://mary.opendfki.de/query?milestone=3.6

### MARY 3.5.0

This release provides substantial new features while maintaining the API compatible to previous versions.
[mary-install-3.5.0.jar](http://mary.dfki.de/download/mary-install-3.5.0.jar) (700kB)

[mary-standalone-install-3.5.0.jar](http://mary.dfki.de/download/mary-standalone-install-3.5.0.jar) (32MB, including several voices)

New features include:

* installer slimmed down to just over 30 MB, including some voices;
* separate voice installer tool, allowing you to download voices comfortably  and with an integrity verification prior to installation;
* new synthesis technology:
  Marcela Charfuelan ported the excellent HMM-based synthesis code from the HTS project (http://hts.sp.nitech.ac.jp/) to Java - several HMM-based voices already ship with MARY;
* audio effects:
  Oytun Turk implemented a range of audio effects that can be applied to the MARY voices, and can be controlled through the MARYGUIClient;
* voice creation toolkit:
  Sathish Chandra Pammi and Anna Hunecke have cleaned up and [documented the tool](http://mary.opendfki.de/wiki/VoiceImportToolsTutorial) we use for building new synthesis voices;
* voice recording tool "Redstart":
  Mat Wilson has programmed a very nice GUI for recording new voices;
* OGG Vorbis support:
  under Linux, the MARY server can now generate audio in OGG Vorbis format.
	
### MARY 3.1.0

Ten months after the last stable release, a major milestone release is finally here:
MARY 3.1.0.

[mary-install-3.1.0.jar](http://mary.dfki.de/download/mary-install-3.1.0.jar) (web-based installer)

Its main features are:

* state of the art unit selection (English and German);
* support for two more platforms:
  64 bit Linux and Mac OS X on Intel platforms;
* a voice creation toolkit (work in progress, see http://mary.opendfki.de/browser/tags/3.1.0/lib/modules/import/README for preliminary documentation if you want to try it out).

Thanks to those who have helped test the beta versions!
All the problems that we have become aware of should be fixed in this release.
For a reasonably complete list of issues addressed in this release, see http://mary.opendfki.de/milestone/3.1.0

Should you come across additional bugs, please post them to the mary-users mailing list (http://www.dfki.de/mailman/listinfo/mary-users).

Some background info:

The unit selection code released here has performed better-than-average in this year's Blizzard Challenge (http://www.festvox.org/blizzard/), showing that the system can be considered state-of-the-art.
For details, see:
http://www.dfki.de/~schroed/publications.html#schroeder_hunecke2007a

The German voices have been created from the BITS corpora - for details, see:
http://www.dfki.de/~schroed/publications.html#schroeder_hunecke2007

### 3.1beta2

[mary-install-3.1beta2.jar](http://mary.dfki.de/download/mary-install-3.1beta2.jar) (web-based installer, 450kB)

**Release notes:**
Another beta release of the new unit selection code.
We have added acoustic targets, so slt-arctic, bdl-arctic and jmk-arctic voices should again sound better than in 3.1beta1.
Also, we have four German unit selection voices, using recordings from the BITS project!
Quality is not optimal yet, but we're getting there.

Audio data is still stored as uncompressed PCM data, which makes the full install bigger then 2 GB - therefore, unfortunately there is no standalone-installer for this release.
We hope to be able to offer smaller voices in the future.

**Known issue:**
The diphone voices in this release are pretty much broken.
If you want to use diphone voices, your best bet is probably the 3.0.3 stable release.

For some details of what has been done and what still needs to be done for the stable 3.1 release, see the [full list of issues](http://mary.opendfki.de/milestone/3.1.0) on the development portal.

### 3.1beta1

[mary-install-3.1beta1.jar](http://mary.dfki.de/download/mary-install-3.1beta1.jar) (web-based installer, 450kB) or use [mary-standalone-install-3.1beta1.jar](http://mary.dfki.de/download/mary-standalone-install-3.1beta1.jar) (standalone installer, ~500MB) if the web-based installer causes problems

**Release notes:**
First beta release of the new unit selection code.
Try the new slt-arctic, bdl-arctic and jmk-arctic voices!

For some details of what has been done and what still needs to be done for the stable release, see the [full list of issues](http://mary.opendfki.de/milestone/3.1.0) on the development portal.

### 3.0.3

[mary-install-3.0.3.jar](http://mary.dfki.de/download/mary-install-3.0.3.jar) (web-based installer, 450kB) or use [mary-standalone-install-3.0.3.jar](http://mary.dfki.de/download/mary-standalone-install-3.0.3.jar) (standalone installer, 420MB) if the web-based installer causes problems

**Release notes:**
Third bugfix release.
Most relevant changes:

* fixed standalone mode for running MARY ([ticket 80](http://mary.opendfki.de/ticket/80))
* improved control over prosody using ToBI tags (tickets [59](http://mary.opendfki.de/ticket/59), [60](http://mary.opendfki.de/ticket/60))
* Several minor improvements of German synthesis (tickets [44](http://mary.opendfki.de/ticket/44), [49](http://mary.opendfki.de/ticket/49), [57](http://mary.opendfki.de/ticket/57), [78](http://mary.opendfki.de/ticket/78))
* MBROLA to AUDIO conversion fixed (tickets [54](http://mary.opendfki.de/ticket/54), [55](http://mary.opendfki.de/ticket/55))
* An update is recommended only if you encountered one of these bugs.

See also the [full list of bugs fixed](http://mary.opendfki.de/query?milestone=3.0.3)

### 3.0.2

[mary-install-3.0.2.jar](http://mary.dfki.de/download/mary-install-3.0.2.jar) (web-based installer, 450kB) or use [mary-standalone-install-3.0.2.jar](http://mary.dfki.de/download/mary-standalone-install-3.0.2.jar) (standalone installer, 420MB) if the web-based installer causes problems

**Release notes:**
Second bugfix release.
A number of bugs have been fixed, including:

* WAV audio can now (really) be saved with proper audio headers ([ticket 38](http://mary.opendfki.de/ticket/38))
* several bugs related to failing validation of intermediate processing results (due to an outdated MaryXML Schema) were fixed (tickets [40](http://mary.opendfki.de/ticket/40), [41](http://mary.opendfki.de/ticket/41), [43](http://mary.opendfki.de/ticket/43))
* Synthesizing APML was improved (tickets [51](http://mary.opendfki.de/ticket/51), [52](http://mary.opendfki.de/ticket/52))
* Pronunciation for German compounds was improved ([ticket 36](http://mary.opendfki.de/ticket/36)) 
* An update is recommended if you encountered one of these bugs.

See also the [full list of bugs fixed](http://mary.opendfki.de/query?status=closed&amp;milestone=3.0.2&amp;order=priority)

### 3.0.1

[mary-install-3.0.1.jar](http://mary.dfki.de/download/mary-install-3.0.1.jar) (web-based installer, 450kB) or use [mary-standalone-install-3.0.1.jar](http://mary.dfki.de/download/mary-standalone-install-3.0.1.jar) (standalone installer, 420MB) if the web-based installer causes problems

**Relase notes:**
First bugfix release.
A number of bugs have been fixed which have occurred after the initial release.
Most relevant:

* Audio can now be saved with proper audio headers ([ticket 32](http://mary.opendfki.de/ticket/32))
* Mary GUI client is now accessible via the keyboard ([ticket 3](http://mary.opendfki.de/ticket/3))

An update is recommended.

See also the [full list of bugs fixed](http://mary.opendfki.de/query?status=closed&amp;milestone=3.0.1&amp;order=priority)

### 3.0.0

[mary-install-3.0.0.jar](http://mary.dfki.de/download/mary-install-3.0.0.jar) (web-based installer, 450kB) or use [mary-standalone-install-3.0.0.jar](http://mary.dfki.de/download/mary-standalone-install-3.0.0.jar) (standalone installer, 420MB) if the web-based installer causes problems

**Note:**
This is the first open-source release.
We have put in a lot of effort to test and debug it, but of course the system may have some teething problems.
Please help us improve the system by submitting [bug reports](http://mary.opendfki.de/newticket) on the [OpenMary development page](http://mary.opendfki.de/).

--------

## Related downloads

### Plone Speech Synthesis Tool

This Plone product endows your Plone portal with speech output capabilities.
It is a client which connects to a MARY TTS server, so you will need to install the MARY TTS system to use the Plone Speech Synthesis Tool.

Installation:
1. Install MARY TTS and run the server
2. Unpack SpeechSynthesisTool in your portal's Products/ folder;
   restart zope;
   install product using the portal_quickinstaller;
   and configure the location of your MARY TTS server under "site setup"->"SpeechSynthesisTool Setup".

Download [SpeechSynthesisTool-0.1.zip](http://mary.dfki.de/download/SpeechSynthesisTool-0.1.zip) or get from SVN:

    svn checkout https://mary.opendfki.de/repos/trunk/examples/client/SpeechSynthesisTool SpeechSynthesisTool
