# Welcome to the Jazz Community!

> write some nice intro to welcome people and explain the goals

Visit our website: [http://jazz-community.org](http://jazz-community.org)

## Key Goals
**Increase Efficiency & Productivity**
From our experience, many companies try to solve challenges that are not (yet) addressed by IBM. They often solve this by implementing extension to address these issues. Usually, they are not the only onces, so other companies facing the same challenges could benefit from the experience and work done by other companies. By sharing your extensions with the community, you can help anyone to make Jazz even better and you can benefit from other peoples work in return. 

**Know How Sharing**
For a long time, [Ralph Schoon's Blog](https://rsjazz.wordpress.com) and his extension workshop was the only public resource to learn Jazz Extension Development. The [Jazz Wiki](https://jazz.net/wiki) wiki holds also many useful information, but some of it is outdated for ages. All these resources focus on _text_, whereas we want to focus on *source code* and _deployable artifacts_ addressing a specific need.

## Contributing to any of our projects

> List what is required (e.g. GitHub account) and who can do what (anyone can fork, create pull requests and file issues)
> How to join the organization

## What is already available
The number of repositories has grown significantly over the last months. We aim to help you to find interesting repositories by grouping them into different sections.

### Rational Team Concert
We have created a bunch of extension for RTC. They are grouped by the following topics:
- Work Item 
- Git* Integration
- Dashboard Widgets

#### Work Item
Work Items build the core of RTC. Hence, there are also endless possibilities to improve the workflow and usability when working with them:
- Work Item Bulk Mover ([UI](https://github.com/jazz-community/rtc-workitem-bulk-mover-ui) and [Service](https://github.com/jazz-community/rtc-workitem-bulk-mover-service)) - Move a bunch of work items from one project area to another. Useful if you split/merge project areas or if you want to migrate to another process template. 
- [Status History Presentation](https://github.com/jazz-community/rtc-statushistory-presentation) - Allow to follow the status of of a Work Item over time.
- [Work Item Command Line](https://github.com/jazz-community/work-item-command-line) - Many useful work item automation tasks
- [Create Child Work Item](https://github.com/jazz-community/rtc-create-child-item-plugin) - Create a child Work Item out of the Work Item Editor with a single click!

#### Git Integration
Git has become the leading Version Control System over the last years, especially when it comes to open source software. One of its key success factors are great tools like GitHub that are based on Git. Companies that are operating RTC are more and more faced with the challenge to couple git based VCS like GitLab or GitHub with the Jazz Platform. 
The following extensions aim to fill or shrink the burdens for users that use both RTC and git based VCS tools:
- [Git Commit Picker](https://github.com/jazz-community/rtc-git-commit-picker) - Link Git Commits with RTC Work Items out of the Work Item Editor
- [Secure Property Store](https://github.com/jazz-community/rtc-secure-user-property-store) - Used to store Access Tokens (e.g. for GitLab) in RTC 
- An enhanced, web hook based GitLab integration will follow soon...

#### Dashboard Widgets
Project and team dashboards help you to have all your necessary information at a glance. RTC and JRS deliver many useful widgets and reports, but for some specific use cases, custom widgets are needed. The following are provided by us:
- [Timebox Planning](https://github.com/jazz-community/rtc-timeboxplanning) - Timeboxing is a widely used planning technique. The timebox planning widget is a feature rich widget which simplifies sprint planning, for both Scrum and SAFe based projects
- [Absence Widget](https://github.com/jazz-community/rtc-absence-widget) - Display scheduled absences of one or multiple teams in a compact way

### Doors Next Generation
The [DNG Client Extensions](https://github.com/jazz-community/dng-client-extensions) repository contains a few open social gadgets for DNG, you can find more details in the repository itself.

### Development and boiler plates
In order to get started with your own projects, the below repositories help you to get started more easily and should help you to improve your development workflow:
- [Jazz Debug Environment](https://github.com/jazz-community/jazz-debug-environment) - Command line based ready-to-go environment for extending and debugging jazz extensions. You can use your favorite Editor or IDE and attach a remote debugger to it.
- [Jazz Plugin Bootstrapper](https://github.com/jazz-community/jazz-plugin-maven-archetype) - Bootstrap a new jazz service with only a few commands! Uses a shared [Base Service](https://github.com/jazz-community/jazz-plugin-maven-archetype) to encapsulate code for generating services.
- [P2 Repository Converter](https://github.com/jazz-community/jazz-p2-repository-converter) - Create a _p2_ complaint package of the RTC SDK. This should be soon obsolete once IBM officially provides a p2 package of the SDK.

### Organizational 
Those are the repositories that are used to organize and deliver content specifically related to the _jazz-community_ organization on GitHub:
- [Jazz Community Website](https://github.com/jazz-community/jazz-community.github.io) - We have a simple website that is available under [http://http://jazz-community.org/](http://http://jazz-community.org/) to act as an entry point for people that are not familiar with GitHub
- This repository - Contains guidance and information on how we work together in the _jazz-community_ organization