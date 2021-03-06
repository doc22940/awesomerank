---
layout: default
title: Awesome Rank for ashishb/android-security-awesome
---

<p align="center">
	This list is a copy of <a href="https://github.com/ashishb/android-security-awesome">ashishb/android-security-awesome</a> with ranks
</p>
---
android-security-awesome [![Backers on Open Collective](https://opencollective.com/android-security-awesome/backers/badge.svg)](#backers) [![Sponsors on Open Collective](https://opencollective.com/android-security-awesome/sponsors/badge.svg)](#sponsors) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★73813](https://github.com/sindresorhus/awesome)
========================

A collection of android security related resources.

1. [TOOLS](#tools)
2. [ACADEMIC / RESEARCH / PUBLICATIONS / BOOKS](#academic)
3. [EXPLOITS / VULNERABILITIES / BUGS](#exploits)

----
# <a name="tools"></a>TOOLS

Online Analyzers
----

1. [AndroTotal](http://andrototal.org/)
2. [Tracedroid](http://tracedroid.few.vu.nl/)
4. [Visual Threat](http://www.visualthreat.com/)
5. [Mobile Malware Sandbox](http://www.mobilemalware.com.br/analysis/index_en.php)
7. [Appknox](https://www.appknox.com/) - not free
8. [IBM Security AppScan Mobile Analyzer](https://appscan.bluemix.net/mobileAnalyzer) - not free
9. [NVISO ApkScan](https://apkscan.nviso.be/)
10.[AVC UnDroid](http://undroid.av-comparatives.info/)
12.[habo](https://habo.qq.com/) 10/day
13.[Virustotal](https://www.virustotal.com/)-max 128MB
14.[Fraunhofer App-ray](http://app-ray.co/) - not free
15.[AppCritique](https://appcritique.boozallen.com) - Upload your Android APKs and receive comprehensive free security assessments.
16.[NowSecure Lab Automated](https://www.nowsecure.com/blog/2016/09/19/announcing-nowsecure-lab-automated/) - Enterprise tool for mobile app security testing both Android and iOS mobile apps. Lab Automated features dynamic and static analysis on real devices in the cloud to return results in minutes. Not free
17. ~~[CopperDroid](http://copperdroid.isg.rhul.ac.uk/copperdroid/)~~
18. ~~[SandDroid](http://sanddroid.xjtu.edu.cn/)~~
19. ~~[Stowaway](http://www.android-permissions.org/)~~
20. ~~[Anubis](http://anubis.iseclab.org/)~~
21. ~~[Mobile app insight](http://www.mobile-app-insight.org)~~
22. ~~[Mobile-Sandbox](http://mobile-sandbox.com)~~
23. ~~[Ijiami](http://safe.ijiami.cn/)~~
24. ~~[Comdroid](http://www.comdroid.org/)~~
25. ~~[Android Sandbox](http://www.androidsandbox.net/)~~
26. ~~[Foresafe](http://www.foresafe.com/scan)~~
27. ~~[Dexter](https://dexter.dexlabs.org/)~~
28. ~~[MobiSec Eacus](http://www.mobiseclab.org/eacus.jsp)~~
29. ~~[Fireeye](https://fireeye.ijinshan.com/)- max 60MB 15/day~~
 
Static Analysis Tools
----

1.  [Androwarn ★166 ⏳4Y](https://github.com/maaaaz/androwarn) - detect and warn the user about potential malicious behaviours developped by an Android application.
2. [ApkAnalyser ★840 ⏳4Y](https://github.com/sonyxperiadev/ApkAnalyser)
3. [APKInspector ★547 ⏳4Y](https://github.com/honeynet/apkinspector)
4. [Droid Intent Data Flow Analysis for Information Leakage](https://www.cert.org/secure-coding/tools/didfail.cfm)
5. [DroidLegacy](https://bitbucket.org/srl/droidlegacy)
6. [Several tools from PSU](http://siis.cse.psu.edu/tools.html)
7. [Smali CFG generator ★68 ⏳3Y](https://github.com/EugenioDelfa/Smali-CFGs)
8. [FlowDroid](https://blogs.uni-paderborn.de/sse/tools/flowdroid/)
9. [Android Decompiler](https://www.pnfsoftware.com/) – not free
10. [PSCout](http://pscout.csl.toronto.edu/) - A tool that extracts the permission specification from the Android OS source code using static analysis
11. [Amandroid](http://amandroid.sireum.org/)
12. [SmaliSCA ★187](https://github.com/dorneanu/smalisca) - Smali Static Code Analysis
13. [CFGScanDroid ★25 ⏳2Y](https://github.com/douggard/CFGScanDroid) - Scans and compares CFG against CFG of malicious applications
14. [Madrolyzer ★61 ⏳2Y](https://github.com/maldroid/maldrolyzer) - extracts actionable data like C&C, phone number etc.
15. [SPARTA](https://www.cs.washington.edu/sparta) - verifies (proves) that an app satisfies an information-flow security policy; built on the [Checker Framework](https://types.cs.washington.edu/checker-framework/)
16. [ConDroid ★23 ⏳1Y](https://github.com/JulianSchuette/ConDroid) - Performs a combination of symoblic + concrete execution of the app
17. [DroidRA ★12](https://github.com/serval-snt-uni-lu/DroidRA)
18. [RiskInDroid ★10](https://github.com/ClaudiuGeorgiu/RiskInDroid) - A tool for calculating the risk of Android apps based on their permissions, with online demo available.
19. [SUPER ★139](https://github.com/SUPERAndroidAnalyzer/super) - Secure, Unified, Powerful and Extensible Rust Android Analyzer
20. [ClassyShark ★4422](https://github.com/google/android-classyshark) - Standalone binary inspection tool which can browse any Android executable and show important infos.

App Vulnerability Scanners
----

1. [QARK ★1481](https://github.com/linkedin/qark) - QARK by LinkedIn is for app developers to scan app for security issues
2. [AndroBugs ★483](https://github.com/AndroBugs/AndroBugs_Framework)
3. [Nogotofail ★2219](https://github.com/google/nogotofail)
4. [Devknox](https://devknox.io/) - Autocorrect security issues as if it was spell check from your IDE
5. [JAADAS ★174](https://github.com/flankerhqd/JAADAS) - Joint intraprocedure and interprocedure program analysis tool to find vulnerabilities in Android apps, built on Soot and Scala

Dynamic Analysis Tools
----

1.  [Android DBI frameowork](http://www.mulliner.org/blog/blosxom.cgi/security/androiddbiv02.html)
2.  [Androl4b ★521](https://github.com/sh4hin/Androl4b)- A Virtual Machine For Assessing Android applications, Reverse Engineering and Malware Analysis
3. [Android Malware Analysis Toolkit](http://www.mobilemalware.com.br/amat/download.html) - (linux distro) Earlier it use to be an [online analyzer](http://dunkelheit.com.br/amat/analysis/index_en.php)
4. [Mobile-Security-Framework MobSF ★2369](https://github.com/MobSF/Mobile-Security-Framework-MobSF) - Mobile Security Framework is an intelligent, all-in-one open source mobile application (Android/iOS) automated pen-testing framework capable of performing static, dynamic analysis and web API testing.
5. [AppUse](https://appsec-labs.com/AppUse/) – custom build for pentesting
6. [Cobradroid](https://thecobraden.com/projects/cobradroid/) – custom image for malware analysis
7. ~~[ViaLab Community Edition](https://www.nowsecure.com/blog/2014/09/09/introducing-vialab-community-edition/)~~
8. [Droidbox ★329](https://github.com/pjlantz/droidbox)
9. ~~[Mercury](https://labs.mwrinfosecurity.com/tools/2012/03/16/mercury/)~~
10. [Drozer ★1247](https://github.com/mwrlabs/drozer)
11. [Xposed](https://forum.xda-developers.com/xposed/xposed-installer-versions-changelog-t2714053) - equivalent of doing Stub based code injection but without any modifications to the binary
12. [Inspeckage ★816](https://github.com/ac-pm/Inspeckage) - Android Package Inspector - dynamic analysis with api hooks, start unexported activities and more. (Xposed Module)
13. [Android Hooker ★298 ⏳1Y](https://github.com/AndroidHooker/hooker) - Dynamic Java code instrumentation (requires the Substrate Framework)
14. [ProbeDroid ★149](https://github.com/ZSShen/ProbeDroid) - Dynamic Java code instrumentation
15. [Android Tamer](https://androidtamer.com/) - Virtual / Live Platform for Android Security Professionals
16. [DECAF ★232](https://github.com/sycurelab/DECAF) - Dynamic Executable Code Analysis Framework based on QEMU (DroidScope is now an extension to DECAF)
17. [CuckooDroid ★314](https://github.com/idanr1986/cuckoo-droid) - Android extension for Cuckoo sandbox
18. [Mem ★29 ⏳2Y](https://github.com/MobileForensicsResearch/mem) - Memory analysis of Android (root required)
19. [Crowdroid](http://www.ida.liu.se/labs/rtslab/publications/2011/spsm11-burguera.pdf) – unable to find the actual tool
20. [AuditdAndroid ★23 ⏳4Y](https://github.com/nwhusted/AuditdAndroid) – android port of auditd, not under active development anymore
21. [Android Security Evaluation Framework](https://code.google.com/p/asef/) - not under active development anymore
22. [Android Reverse Engineering](https://redmine.honeynet.org/projects/are/wiki) – ARE (android reverse engineering) not under active development anymore
23. [Aurasium ★18 ⏳3Y](https://github.com/xurubin/aurasium) – Practical security policy enforcement for Android apps via bytecode rewriting and in-place reference monitor.
24. [Android Linux Kernel modules ★96 ⏳3Y](https://github.com/strazzere/android-lkms)
25. [Appie](https://manifestsecurity.com/appie/) - Appie is a software package that has been pre-configured to function as an Android Pentesting Environment.It is completely portable and can be carried on USB stick or smartphone.This is a one stop answer for all the tools needed in Android Application Security Assessment and an awesome alternative to existing virtual machines.
26. [StaDynA ★7](https://github.com/zyrikby/StaDynA) - a system supporting security app analysis in the presence of dynamic code update features (dynamic class loading and reflection). This tool combines static and dynamic analysis of Android applications in order to reveal the hidden/updated behavior and extend static analysis results with this information.
27. [DroidAnalytics ★19 ⏳2Y](https://github.com/zhengmin1989/DroidAnalytics) - incomplete
28. [Vezir Project ★59 ⏳1Y](https://github.com/oguzhantopgul/Vezir-Project) - Virtual Machine for Mobile Application Pentesting and Mobile Malware Analysis
29. [MARA ★217](https://github.com/xtiankisutsa/MARA_Framework) - Mobile Application Reverse engineering and Analysis Framework
30. [Taintdroid](http://appanalysis.org/download.html) - requires AOSP compilation

Reverse Engineering
----

1. [Smali/Baksmali ★2420](https://github.com/JesusFreke/smali) – apk decompilation
2. [emacs syntax coloring for smali files ★22 ⏳1Y](https://github.com/strazzere/Emacs-Smali)
3. [vim syntax coloring for smali files](http://codetastrophe.com/smali.vim)
4. [AndBug ★425 ⏳1Y](https://github.com/swdunlop/AndBug)
5. [Androguard ★1815](https://github.com/androguard/androguard) – powerful, integrates well with other tools
6. [Apktool](https://ibotpeaches.github.io/Apktool/) – really useful for compilation/decompilation (uses smali)
7. [Android Framework for Exploitation ★127 ⏳2Y](https://github.com/appknox/AFE)
8. [Bypass signature and permission checks for IPCs ★49 ⏳4Y](https://github.com/iSECPartners/Android-KillPermAndSigChecks)
9. [Android OpenDebug ★64 ⏳4Y](https://github.com/iSECPartners/Android-OpenDebug) – make any application on device debuggable (using cydia substrate).
10. [Dare](http://siis.cse.psu.edu/dare/index.html) – .dex to .class converter
11. [Dex2Jar ★4018](https://github.com/pxb1988/dex2jar) - dex to jar converter
12. [Enjarify ★2091](https://github.com/google/enjarify) - dex to jar converter from Google
13. [Dedexer](http://dedexer.sourceforge.net)
14. [Fino ★75 ⏳3Y](https://github.com/sysdream/fino)
15. [Frida](https://www.frida.re/) - inject javascript to explore applications and a [GUI tool ★87 ⏳1Y](https://github.com/antojoseph/diff-gui) for it
16. [Indroid](https://bitbucket.org/aseemjakhar/indroid) – thread injection kit
17. [IntentSniffer](https://www.nccgroup.trust/us/about-us/resources/intent-sniffer/)
18. [Introspy ★325 ⏳4Y](https://github.com/iSECPartners/Introspy-Android)
19. [Jad]( https://varaneckas.com/jad/) - Java decompiler
20. [JD-GUI ★4140](https://github.com/java-decompiler/jd-gui) - Java decompiler
21. [CFR](http://www.benf.org/other/cfr/) - Java decompiler
22. [Krakatau ★795](https://github.com/Storyyeller/Krakatau) - Java decompiler
23. [Procyon](https://bitbucket.org/mstrobel/procyon/wiki/Java%20Decompiler) - Java decompiler
24. [FernFlower ★929](https://github.com/fesh0r/fernflower) - Java decompiler
25. [Redexer ★103](https://github.com/plum-umd/redexer) – apk manipulation
26. [Smali viewer](http://blog.avlyun.com/wp-content/uploads/2014/04/SmaliViewer.zip)
27. ~~[ZjDroid](https://github.com/BaiduSecurityLabs/ZjDroid)~~, ~~[fork/mirror](https://github.com/yangbean9/ZjDroid)~~
28. [Simplify Android deobfuscator ★2428](https://github.com/CalebFenton/simplify)
29. [Bytecode viewer ★8875](https://github.com/Konloch/bytecode-viewer)
30. [Radare2 ★6396](https://github.com/radare/radare2)

Fuzz Testing
----

1. [IntentFuzzer](https://www.nccgroup.trust/us/about-us/resources/intent-fuzzer/)
2. [Radamsa Fuzzer ★36](https://github.com/anestisb/radamsa-android)
3. [Honggfuzz ★942](https://github.com/google/honggfuzz)
4. [An Android port of the melkor ELF fuzzer ★44 ⏳3Y](https://github.com/anestisb/melkor-android)
5. [Media Fuzzing Framework for Android ★226 ⏳1Y](https://github.com/fuzzing/MFFA)
6. [AndroFuzz ★24 ⏳3Y](https://github.com/jonmetz/AndroFuzz)

App Repackaging Detectors
----

1. [FSquaDRA ★36](https://github.com/zyrikby/FSquaDRA) - a tool for detection of repackaged Android applications based on app resources hash comparison.

Market Crawlers
----

1. [Google play crawler (Java) ★387](https://github.com/Akdeniz/google-play-crawler)
2. [Google play crawler (Python) ★682](https://github.com/egirault/googleplay-api)
3. [Google play crawler (Node)  ★151](https://github.com/dweinstein/node-google-play) - get app details and download apps from official Google Play Store.
4. [Aptoide downloader (Node) ★13 ⏳2Y](https://github.com/dweinstein/node-aptoide) - download apps from Aptoide third-party Android market
5. [Appland downloader (Node) ★7 ⏳2Y](https://github.com/dweinstein/node-appland) - download apps from Appland third-party Android market

Misc Tools
----

1. [smalihook](http://androidcracking.blogspot.com/2011/03/original-smalihook-java-source.html)
2. [APK-Downloader](http://codekiem.com/2012/02/24/apk-downloader/)
3. [AXMLPrinter2](http://code.google.com/p/android4me/downloads/detail?name=AXMLPrinter2.jar) - to convert binary XML files to human-readable XML files
4. [adb autocomplete ★173 ⏳1Y](https://github.com/mbrubeck/android-completion)
5. [Dalvik opcodes](http://pallergabor.uw.hu/androidblog/dalvik_opcodes.html)
6. [Opcodes table for quick reference](http://ww38.xchg.info/corkami/opcodes_tables.pdf)
7. [ExploitMe Android Labs](http://securitycompass.github.io/AndroidLabs/setup.html) - for practice
8. [GoatDroid ★161 ⏳3Y](https://github.com/jackMannino/OWASP-GoatDroid-Project) - for practice
9. [mitmproxy ★9150](https://github.com/mitmproxy/mitmproxy)
10. [dockerfile/androguard ★27 ⏳1Y](https://github.com/dweinstein/dockerfile-androguard)
11. [Android Vulnerability Test Suite ★894](https://github.com/AndroidVTS/android-vts) - android-vts scans a device for set of vulnerabilities
12. [AppMon ★447](https://github.com/dpnishant/appmon)- AppMon is an automated framework for monitoring and tampering system API calls of native macOS, iOS and android apps. It is based on Frida.
----

# <a name="academic"></a>ACADEMIC / RESEARCH / PUBLICATIONS / BOOKS

Research Papers
----
1. [Exploit Database](https://www.exploit-db.com/papers/) 
2. [Android security related presentations ★91 ⏳3Y](https://github.com/jacobsoo/AndroidSlides)
3. [A good collection of static analysis papers](https://tthtlc.wordpress.com/2011/09/01/static-analysis-of-android-applications/)

Books
----
1. [SEI CERT Android Secure Coding Standard](https://www.securecoding.cert.org/confluence/display/android/Android+Secure+Coding+Standard)

Others
----
1. [OWASP Mobile Security Testing Guide Manual ★1720](https://github.com/OWASP/owasp-mstg) 
2. [Android Reverse Engineering 101 by Daniele Altomare](http://www.fasteque.com/android-reverse-engineering-101-part-1/)
3. [doridori/Android-Security-Reference ★517](https://github.com/doridori/Android-Security-Reference)
4. [android app security checklist ★304](https://github.com/b-mueller/android_app_security_checklist)
5. [Mobile App Pentest Cheat Sheet ★994](https://github.com/tanprathan/MobileApp-Pentest-Cheatsheet)

----

# <a name="exploits"></a>EXPLOITS / VULNERABILITIES / BUGS

List
----

1. [Android Security Bulletins](https://source.android.com/security/bulletin/)
2. [Android's reported security vulnerabilities](https://www.cvedetails.com/vulnerability-list/vendor_id-1224/product_id-19997/Google-Android.html)
3. [Android Devices Security Patch Status](https://kb.androidtamer.com/Device_Security_Patch_tracker/)
4. [AOSP - Issue tracker](https://code.google.com/p/android/issues/list?can=2&q=priority=Critical&sort=-opened)
5. [OWASP Mobile Top 10 2016](https://www.owasp.org/index.php/Mobile_Top_10_2016-Top_10)
6. [Exploit Database](https://www.exploit-db.com/search/?action=search&q=android) - click search
7. [Vulnerability Google Doc](https://docs.google.com/spreadsheet/pub?key=0Am5hHW4ATym7dGhFU1A4X2lqbUJtRm1QSWNRc3E0UlE&single=true&gid=0&output=html)
8. [Google Android Security Team’s Classifications for Potentially Harmful Applications (Malware)](https://source.android.com/security/reports/Google_Android_Security_PHA_classifications.pdf)


Malware
----
1. [androguard - Database Android Malwares wiki](https://code.google.com/p/androguard/wiki/DatabaseAndroidMalwares)
2. [Android Malware Github repo ★179](https://github.com/ashishb/android-malware)
3. [Android Malware Genome Project](http://www.malgenomeproject.org/policy.html) - contains 1260 malware samples categorized into 49 different malware families, free for research purpose.
4. [Contagio Mobile Malware Mini Dump](http://contagiominidump.blogspot.com)
5. [VirusTotal Malware Intelligence Service](https://www.virustotal.com/en/about/contact/) - powered by VirusTotal, not free
6. [Admire](http://admire.necst.it/)
7. [Drebin](https://www.sec.cs.tu-bs.de/~danarp/drebin/)



Bounty Programs
----
1. [Android Security Reward Program](https://www.google.com/about/appsecurity/android-rewards/)

How to report
----
1. [Android - reporting security issues](https://source.android.com/security/overview/updates-resources.html#report-issues)
2. [Android Reports and Resources ★106](https://github.com/B3nac/Android-Reports-and-Resources) - List of Android Hackerone disclosed reports and other resources

----

# Other Awesome Lists
Other amazingly awesome lists can be found in the
[awesome-awesomeness ★20295](https://github.com/bayandin/awesome-awesomeness) list.

# Contributing
Your contributions are always welcome!


## Backers

Support us with a monthly donation and help us continue our activities. [[Become a backer](https://opencollective.com/android-security-awesome#backer)]

<a href="https://opencollective.com/android-security-awesome/backer/0/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/0/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/1/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/1/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/2/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/2/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/3/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/3/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/4/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/4/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/5/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/5/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/6/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/6/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/7/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/7/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/8/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/8/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/9/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/9/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/10/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/10/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/11/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/11/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/12/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/12/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/13/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/13/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/14/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/14/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/15/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/15/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/16/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/16/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/17/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/17/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/18/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/18/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/19/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/19/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/20/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/20/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/21/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/21/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/22/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/22/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/23/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/23/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/24/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/24/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/25/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/25/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/26/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/26/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/27/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/27/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/28/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/28/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/backer/29/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/backer/29/avatar.svg"></a>


## Sponsors

Become a sponsor and get your logo on our README on Github with a link to your site. [[Become a sponsor](https://opencollective.com/android-security-awesome#sponsor)]

<a href="https://opencollective.com/android-security-awesome/sponsor/0/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/sponsor/0/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/sponsor/1/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/sponsor/1/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/sponsor/2/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/sponsor/2/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/sponsor/3/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/sponsor/3/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/sponsor/4/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/sponsor/4/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/sponsor/5/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/sponsor/5/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/sponsor/6/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/sponsor/6/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/sponsor/7/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/sponsor/7/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/sponsor/8/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/sponsor/8/avatar.svg"></a>
<a href="https://opencollective.com/android-security-awesome/sponsor/9/website" target="_blank"><img src="https://opencollective.com/android-security-awesome/sponsor/9/avatar.svg"></a>


---
<p align="center">
	This list is a copy of <a href="https://github.com/ashishb/android-security-awesome">ashishb/android-security-awesome</a> with ranks
</p>
