*AppPot* is a way to implement generic application deployment on a computational Grid, and especially to enable users to provide their own software to the computing cluster.

*AppPot* uses [User Mode Linux](http://user-mode-linux.sf.net/) to provide users with a development and running environment they have full control over. User Mode Linux provides a virtualized environment in which users can build and run their own computational applications. AppPot? augments this with scripts that can take a copy of the UserModeLinux? system image and submit it as a regular computational job using the ARC middleware.

An overview of *AppPot* and its purpose can be found in [these slides](http://www.egi.eu/indico/materialDisplay.py?contribId=108&sessionId=47&materialId=slides&confId=452) presented at the [EGI Technical Forum 2011](https://www.egi.eu/indico/conferenceDisplay.py?confId=452).

The most complete information on the AppPot design, motivation, and architecture is the [arXiv 1203.1466 paper](http://arxiv.org/abs/1203.1466).
