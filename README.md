Chaos
=======

Chaos was named after a Chinese slang on Internet ("How dare you to name yourself Chao/Zhao?"). The idea was coming from SyncNet, which is a decentralized browser built on top of BitTorrent Sync. However, SyncNet didn't continue furtherer extent, only left some inspirations. Chaos continued as a p2p community-based information dashboard, which then able to recommend good content in a relative decentralized, free and organic way. 

Requirements
------------
* [enaml](https://github.com/nucleic/enaml) - enaml is used as the UI framework
  + You can find installation instructions [here](http://nucleic.github.io/enaml/docs/get_started/installation.html).
    If you have a working C++ compilier it is as simple as `pip install enaml`, if not you will have to install the
    various requirements from their project pages. Qt is the recommended backend. OS X users can install `PyQt4` with
    homebrew. Windows users can find binaries on the pyqt project page. Linux users know how to install things.

* [atom](https://github.com/nucleic/atom) - atom is used as the eventing framework
  + This is a dependency of `enaml`, so if you successfully installed `enaml` you should be good to go.

* [python-btsync](https://github.com/jminardi/python-btsync) - a lightweight wrapper around the BTSync API
  + `python-btsync` is a light weight wrapper I wrote around the btsync API. To use it you will have to apply
     for and receive an API key from BitTorrent. Once you have that key you will need to enter it into the
     config.json file and point btsync to that file when starting up. You can find more details on the linked
     github project page.
