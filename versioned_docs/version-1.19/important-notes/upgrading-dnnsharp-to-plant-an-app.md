---
id: upgrading-dnnsharp-to-plant-an-app
title: Upgrading - DNNSharp tools to Plant an App
sidebar_label: Upgrading - DNNSharp tools to Plant an App
---

# Migrate/Upgrade document

### `General Advice`

* You may find additional helpful information on our [DNN Compatibility](/important-notes/dnn-compatibility.md) page.
* Best practice - perform the upgrade on a clone to encounter and resolve issues without impacting your production site
    * Clone the site
    * Upgrade the clone per instructions
    * Test the site
* Add steps to take backups of the site - site crashes can occur during upgrades & backups can help you avoid data loss or having to start over from the beginning
    * Initially
    * Along the way
* Each backup must include an SQL Database & DNN File System
* All modules must be upgraded to the same level (version & subversion) before moving on to the next step.

### `First checks`

* If you have very old DNNSharp modules, you will need to upgrade all of them
    incrementally. For this process, please contact our support and provide the following:
    all the modules installed and their versions, DNN Version Installed, .NET Framework
    installed. After we analyze it, you'll receive a new list with all the download links
    that you'll need for the incremental upgrade process. After that, you’ll have all the
    DNNSharp modules & addons to the latest versions of 5.0.x.
* If you have DNN 9.3.1(or lower) installed, please make sure all your DNN Sharp
    modules are upgraded to the latest 5.0.x version before upgrading DNN or to DNN
    Sharp 5.1+ modules. Even if you already have a 5.0.x version of a module installed,
    confirm it is the last 5.0.x version that was released for the module. If you aren't sure
    you have the latest version of a 5.0.x module, please contact us.
* If you use our URL Adapter module, please do not forget to disable it before the
    upgrade process begins. This way, you will get rid of any conflicts that may occur
    during the upgrade process, due to various module settings. You will be able to
    enable the module after the entire upgrade process is complete.
* Contact Support for a list of all the latest module versions you will need for your unique upgrade path.

### `Upgrade steps`

* [ ] Upgrade all the products to the latest 5.1.x.
* [ ] Upgrade the DNN to 9.3.2.
* [ ] Upgrade all the products to the latest 5.6.x.
* [ ] Install .NET Framework 4.7.2 (or 4.8) .
* [ ] Upgrade the DNN to 9.6.1.
* [ ] Upgrade all the products to the latest 5.9.x.
* [ ] Upgrade the DNN to 9.7.2.
* [ ] Upgrade all third-party modules to their current versions
* [ ] Install the AppBuilder version 1.12.91, which can be downloaded from our [Downloads](https://console.plantanapp.com/Downloads) page.
* [ ] Create an administrative page (typically named Configuration).
* [ ] Add an AppBuilder module to the Configuration page. This module is your primary way to configure Plant An App.
* [ ] If prompted, allow App Builder to install dependencies.
* [ ] Upgrade the DNN to 9.9.1.
* [ ] On the Configuration page, use the Updates feature to update to successive versions (1.13, 1.14, ...) until you are at the current version.


### `Known Incompatibilities`

* [ ] Some versions of 2sxc content are incompatible with AppBuilder version 1.12.91. Install the latest version of 2sxc before installing AppBuilder.