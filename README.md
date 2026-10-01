
# HakuNeko
🏡 Website : https://hakuneko.download

---

<img width="200" height="200" alt="Screenshot 2026-09-29 142942" src="" />
<img width="200" height="200" alt="Screenshot 2026-09-29 142942" src="" />
## Download

Yes, the download section comes first, because this is what most users are looking for anyway.
You can download and run the installer/archive for your operating system from one of the mirror sites above.
There is also a portable version available for Windows which stores all its application data inside the application folder.

---

=== Status

This section shows the latest build and test results for the master branch of the mirrored repository on link:https://dev.azure.com/manga-download/hakuneko/_build[Azure].

image:https://img.shields.io/azure-devops/tests/manga-download/hakuneko/8?label=CI%20Tests&logo=azure-pipelines[Test Results, link="https://dev.azure.com/manga-download/hakuneko/_testManagement/runs?_a=runQuery", title="List of CI Test Results"]
image:https://dev.azure.com/manga-download/hakuneko/_apis/build/status/CI?branchName=master&label=CI%20Pipeline[Build Status, link="https://dev.azure.com/manga-download/hakuneko/_build/latest?definitionId=5&branchName=master", title="Latest CI Pipeline Summary"]
image:https://dev.azure.com/manga-download/hakuneko/_apis/build/status/Nightly?branchName=master&label=Nightly%20Build[Build Status, link="https://dev.azure.com/manga-download/hakuneko/_build/latest?definitionId=7&branchName=master", title="Latest Nightly Build Summary"]

[%collapsible, title="Details"]
====
Continuous Integration::
image:https://dev.azure.com/manga-download/hakuneko/_apis/build/status/CI?branchName=master&jobName=CI&configuration=CI%20Windows&label=CI%20-%20Windows[title="CI Pipeline: Windows"]
 +
image:https://dev.azure.com/manga-download/hakuneko/_apis/build/status/CI?branchName=master&jobName=CI&configuration=CI%20Ubuntu&label=CI%20-%20Ubuntu[title="CI Pipeline: Ubuntu"]
 +
image:https://dev.azure.com/manga-download/hakuneko/_apis/build/status/CI?branchName=master&jobName=CI&configuration=CI%20macOS&label=CI%20-%20macOS[title="CI Pipeline: macOS"]

Nightly Builds::
image:https://dev.azure.com/manga-download/hakuneko/_apis/build/status/Nightly?branchName=master&jobName=Windows&label=Nightly%20-%20Windows[title="Nightly Build: Windows"]
 +
image:https://dev.azure.com/manga-download/hakuneko/_apis/build/status/Nightly?branchName=master&jobName=Ubuntu&label=Nightly%20-%20Ubuntu[title="Nightly Build: Ubuntu"]
 +
image:https://dev.azure.com/manga-download/hakuneko/_apis/build/status/Nightly?branchName=master&jobName=macOS&label=Nightly%20-%20macOS[title="Nightly Build: macOS"]
====

---

=== Introduction

HakuNeko is a cross-platform downloader for manga and anime from various websites.
HakuNeko was made to help users downloading media for circumstances that require offline usage.
The philosophy is ad-hoc consumption, get it when you going to read/watch it.
It is not meant to be a mass downloader to stock up thousands of chapters that are just collected and will probably never be read.

[.clearfix]
--
[.center]
image::screenshot-pages.png[link=screenshot-pages.png, width=720, title="HakuNeko - Chapter Page Preview", window=_blank]

{nbsp} +

image::screenshot-video.png[link=screenshot-video.png, width=720, title="HakuNeko - Anime Playback", window=_blank]
--

---

=== Development

For developer documentation please check the link:https://github.com/manga-download/hakuneko/wiki/Developer-Manual[Wiki]

---
