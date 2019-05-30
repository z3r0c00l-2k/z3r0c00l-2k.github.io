---
layout: post
title:  "KGet-Integrator"
featured-image: "/images/KGet-Integrator/128-apps-kget.png"
date:   2018-05-08 13:59:27 +0530
categories: project
author: z3r0c00l_2k
--- 
<a href="https://github.com/z3r0c00l-2k/kget-integrator" target="_blank"><i class="icon-github" style="font-size:30px;"></i></a>

![KGetImage](https://kde.org/images/screenshots/kget.png)

<a href="https://www.kde.org/applications/internet/kget/" target="_blank">KGet</a> is a versatile and user-friendly download manager in Linux.

Features of KGet

* Downloading files from FTP and HTTP(S) sources, including pages and individual hyperlinks.
* Pausing and resuming of downloading files, as well as the ability to restart a download.
* Tells lots of information about current and pending downloads.
* Embedding into system tray.
* Metalink support which contain multiple URLs for downloads, along with checksums and other information.

Unfortunately, KGet only supports integration with Konqueror. So I decided to build an integrator for KGet for Chrome/Chromium.

This project is based on <a href="https://github.com/slgobinath/uget-chrome-wrapper.git" target="_blank">uget-chrome-wrapper</a> .

# Installation
Download and install KGet if don't have it installed already.

For Ubuntu
```bash
sudo apt-get install kget
```
For ArchLinux 
```bash
sudo pacman -S kget
```
Or you can simply download it from Store if available 

Clone the repo and change directory
```bash
git clone https://github.com/z3r0c00l-2k/kget-integrator.git
cd kget-integrator
```

Run the installation Script 
```bash
sh install.sh
```

Now Open Chrome/Chromium, Extenstion and enable Developer mode

<img src="/images/KGet-Integrator/dev-mode.jpg" width="90%">

Then Drag and Drop extension.crx file to Chrome/Chromium.

Finally restart your browser.

<img src="/images/KGet-Integrator/final.jpg" width="90%">

Enjoy downloading with KGet on Chrome/Chromium

# Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

# License

GNU General Public License v3