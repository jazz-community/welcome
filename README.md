# Welcome to the Jazz Community!
Visit our website: [http://jazz-community.org](http://jazz-community.org)

## About
Founded in May 2017 by [Siemens BT](https://siemens.com), we wanted to share our knowledge and work with other companies and individuals that are interested in extending [IBM Jazz](https://jazz.net/). We believe that an open minded open source community is the best way to address all the needs of users and organizations that may not be covered quickly enough by the official Jazz products. **We want to encourage _you_ to join the community and help us to make Jazz even better!**

## Key Goals
**Increase Efficiency & Productivity**<br>
From our experience, many companies try to solve challenges that are not (yet) addressed by IBM. They often solve this by implementing extensions to address these issues. Often multiple companies are facing the same challenges and could benefit from the experience and work done by other companies. By sharing your extensions with the community, you can help anyone to make Jazz even better and you can benefit from other people's work in return.

**Know How Sharing**<br>
For a long time, [Ralph Schoon's Blog](https://rsjazz.wordpress.com) and his extension workshop was the only public resource to learn Jazz Extension Development. The [Jazz Wiki](https://jazz.net/wiki) also contains a great deal of useful information, but some of it has been outdated for ages. All these resources focus on _text_, whereas we want to focus on *source code* and _deployable artifacts_ addressing specific needs.

## Contributing to any of our projects
Please refer to our general [Contributing Guide](CONTRIBUTING.md) to learn how to get started with contributing to any of our projects. Please note that some repositories may contain additional contributing information, e.g. about unit test coverage or code style guides.

## Events
We organize regular events, both on-site and web sessions. Have a look at the [Event Calendar](EVENTS.md) to see what's coming up next.

## What is already available
The number of repositories has grown significantly over the last months. To help you find interesting repositories, we've grouped them by topic.

### Rational Team Concert
We have created a bunch of extensions for RTC. They are grouped by the following topics:
- Work Item
- Git* Integration
- Dashboard Widgets

#### Work Item
Work Items are the core of RTC. Hence, there are also endless possibilities to improve the workflow and usability when working with them:
- Work Item Bulk Mover ([UI](https://github.com/jazz-community/rtc-workitem-bulk-mover-ui) and [Service](https://github.com/jazz-community/rtc-workitem-bulk-mover-service)) - Move a bunch of work items from one project area to another. Useful if you split/merge project areas or if you want to migrate to another process template.
- [Status History Presentation](https://github.com/jazz-community/rtc-statushistory-presentation) - Allows following the status of a Work Item over time.
- [Work Item Command Line](https://github.com/jazz-community/work-item-command-line) - Many useful work item automation tasks
- [Create Child Work Item](https://github.com/jazz-community/rtc-create-child-item-plugin) - Create a child Work Item out of the Work Item Editor with a single click!

#### Git Integration
Git has become the leading Version Control System over the last years, especially when it comes to open source software. One of its key success factors are great tools like GitHub that are based on Git. Companies that are operating RTC are more and more faced with the challenge to couple git based VCS like GitLab or GitHub with the Jazz Platform.
The following extensions aim to fill or shrink the burdens for users that use both RTC and git based VCS tools:
- [Git Commit Picker](https://github.com/jazz-community/rtc-git-commit-picker) - Link Git Commits with RTC Work Items out of the Work Item Editor
- [Secure Property Store](https://github.com/jazz-community/rtc-secure-user-property-store) - Used to store Access Tokens (e.g. for GitLab) in RTC
- An enhanced Version of the GIT Commit Picker, allowing "picking" GIT Issues and merge Requests will follow soon...

#### Dashboard Widgets
Project and team dashboards help you to see all your necessary information at a glance. RTC and JRS deliver many useful widgets and reports, but for some specific use cases, custom widgets are needed. The following are provided by us:
- [Timebox Planning](https://github.com/jazz-community/rtc-timeboxplanning) - _Timeboxing_ is a widely used planning technique. The Timebox Planning widget is a feature rich widget which simplifies sprint planning, for both Scrum and SAFe based projects
- [Absence Widget](https://github.com/jazz-community/rtc-absence-widget) - Display scheduled absences of one or multiple teams in a compact way
- A SAFe Program Board widget will be released in January 2018 time frame to support virtual SAFe PI planning.

### Doors Next Generation
The [DNG Client Extensions](https://github.com/jazz-community/dng-client-extensions) repository contains a few open social gadgets for DNG, you can find more details in the repository itself.

### Development and boiler plates
The below repositories help you to get started with your own projects and also help to improve your development workflow:
- [Jazz Debug Environment](https://github.com/jazz-community/jazz-debug-environment) - Command line based ready-to-go environment for extending and debugging jazz extensions. You can use your favorite Editor or IDE and attach a remote debugger to it.
- [Jazz Plugin Bootstrapper](https://github.com/jazz-community/jazz-plugin-maven-archetype) - Bootstrap a new jazz service with only a few commands! Uses a shared [Base Service](https://github.com/jazz-community/jazz-plugin-maven-archetype) to encapsulate code for generating services.
- [P2 Repository Converter](https://github.com/jazz-community/jazz-p2-repository-converter) - Create a _p2_ compliant package of the RTC SDK. This should soon be obsolete once IBM officially provides a p2 package of the SDK.

### Organizational
Those are the repositories that are used to organize and deliver content specifically related to the _jazz-community_ organization on GitHub:
- [Jazz Community Website](https://github.com/jazz-community/jazz-community.github.io) - We have a simple website that is available under [http://jazz-community.org/](http://jazz-community.org/) to act as an entry point for people that are not familiar with GitHub
- [This repository](https://github.com/jazz-community/welcome) - Contains guidance and information on how we work together in the _jazz-community_ organization

## Other useful repositories
The repositories listed in this section are not part of the _jazz-community_ organization, but might still be useful to know about.
### Webpack
- [Jazz update-site packaging](https://github.com/innerjoin/jazz-update-site-webpack-plugin) - Package IBM Jazz Extensions into a valid update-site format
