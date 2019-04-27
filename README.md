# AppImageHub [![Build Status](https://travis-ci.org/AppImage/appimage.github.io.svg?branch=master)](https://travis-ci.org/AppImage/appimage.github.io)

https://appimage.github.io/


## This is...

* __A crowd-sourced directory of available, reviewed AppImages__ with data that 3rd party app stores and software centers can use. Given an URL to an AppImage, it inspects the AppImage and puts it into a community-maintained catalog. The idea is that all the metadata travels inside the AppImage, so besides adding an URL to this repository no additional information is asked, since it comes with the AppImage itself.

## This is NOT...

* __A distribution__. AppImageHub __does not distribute AppImages__ or provide them for download. It simply links to the respective author's download pages, from where users will be able to download AppImages. It also __does not keep track of versions__, only of channels such as "release", "beta", "nightly", "continuous" (as defined by the upstream application authors). We think that trying to keep track of all versions in a central repository is futile, since it does not scale.

## User stories

* "As a user, I would like to have a central catalog of available AppImages that I can download directly from the application authors, so that I know what is available."
* "As a developer, I would like to make my application known to as many potential users as possible in order to increase my user base."
* "As an app center or app store developer, I would like to get information about the available AppImages easily, so that I can focus on building my app center or app store rather than having to crawl the Internet for AppImages myself."

## How to submit AppImages to the catalog

Create a new file using

### **[this link](https://github.com/AppImage/AppImageHub/new/master/data)**

and send a Pull Request. 

**The file should contain one line with a link to the GitHub repository that hosts AppImages on its Releases page.**

**Alternatively, a link to the AppImage. Nothing else.**

Then send a Pull Request to this repository. Travis CI will instantly perform an automated review of the AppImage, and in case it succeeds, you will see a __green__ result in your pull request. If you get a __red__ result, check the log of the Travis CI build, and fix it.

### Checklist for submitting your own AppImage

As a format, AppImage is designed in a way that does not impose restrictions on the person generating AppImages. Basically you are free to put inside an AppImage whatever you want. For AppImageHub, however, additional rules apply. AppImages submitted to AppImage hub undergo automatic and possibly additional manual review.

* Must be downloadable from an URL. Our testing system fetches the AppImage using `wget`. Currently we cannot get AppImages from locations behind authentication and/or cookie-protected locations. For commercial applications we recommend to have a generally downloadable demo/trial version. Please contact us if you would like to add your commercial AppImage to the directory and it is not available for general download
* Must run on the [oldest still-supported Ubuntu LTS release](https://www.ubuntu.com/info/release-end-of-life) (currently Ubuntu 14.04) without the installation of additional packages. Targeting the oldest still-supported LTS is to ensure that the AppImage will run not only on the very latest, but also on older target systems, such as enterprise distributions (not limited to Ubuntu)
* Must execute in our Travis CI based testing environment
* Must pass [appdir-lint.sh](https://github.com/AppImage/AppImages/blob/master/appdir-lint.sh)
* Must have a desktop file that passes `desktop-file-validate`
* Must run without active Internet connection (and at least show some information)
* Should have an [AppStream metainfo file](https://people.freedesktop.org/~hughsient/appdata/) in `usr/share/metainfo`. If it does, must pass `appstreamcli` validation
* Should show a useful screen rather than some crude dialog box since the main window will be used for the main screenshots. Note that you can provide your own screenshots by using an [AppStream metainfo file](https://people.freedesktop.org/~hughsient/appdata/)
* Should be available under a constant URL that does not contain the version number. Alternatively, should be available on GitHub Releases or the openSUSE Build Service (you are free to suggest additional serices like these)
* Must display something sensible when there is no network connection (offline/air-gapped use). Electron apps, for example, can use something like

```
  (async () => {
    if (await isOnline() === true) {
      mainWindow.loadURL(HermesURL);
    } else {
      mainWindow.loadFile('offline.html')
    }
    mainWindow.maximize();
    mainWindow.show();
  })();
  ```

## How to use

App stores and software centers can consume the metadata collected by this project. See [AppImage ecosystem](https://github.com/AppImage/AppImageKit/wiki/Ecosystem). 

![peek 2017-11-26 11-28](https://user-images.githubusercontent.com/2480569/33243768-497bf74a-d2ba-11e7-8336-ae2018229e57.gif)

Currently we are providing a JSON feed at https://appimage.github.io/feed.json. If you would like to use this data but need changes, please contact us on #AppImage at irc.freenode.net, so that we can discuss an output format that would serve your needs best. __PLEASE NOTE__ that the data output format is not finalized yet and is subject to change any time without prior notice, until we release a stable version of it.

Projects already using this data
* Nitrux, NX Software Center: https://github.com/nomad-desktop/nx-software-center
* https://github.com/simoniz0r/spm
* https://github.com/sillasleal/appcenter
* https://github.com/lliurex/lliurex-store
* https://github.com/linuxappstore/linuxappstore-frontend
* Please contact us if you are using this data so that we can list your project here
