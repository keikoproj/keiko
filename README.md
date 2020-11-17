# Keiko - Enable Kubernetes at scale

![Keiko Image](Keiko-Final-Small.png)

*Read this in other languages: [简体中文](README.zh-cn.md).*

## News

Keiko Project has moved from the CLA to the DCO.
* https://github.com/apps/dco/

Please signoff your contributions by doing ONE of the following:
* Use `git commit -s ...` with each commit to add the signoff or
* Manually add a `Signed-off-by: Your Name <your.email@example.com>` to each commit message.

The email address must match your primary GitHub email. You do NOT need cryptographic (e.g. gpg) signing.
* Use `git commit -s --amend ...` to add a signoff to the latest commit, if you forgot.

To automatically signoff on every commit, copy the `community/dco-signoff-hook/prepare-commit-msg` file to the `.git/hooks` directory in your repo or if you already have such a hook, merge the contents into your existing hook.

## What is Keiko?

Keiko is a set of independent open source declarative tools for orchestration and management of multi-tenant, reliable, secure and efficient Kubernetes clusters in production.


## Why Keiko?
Keiko solves the following common problems faced when running and managing Kubernetes clusters at scale and at all stages of their lifecycle.

* How do I bootstrap and manage worker nodes for my cluster?
* How do I mitigate spurious pod/node failures as well as maintain SLAs and compliance?
* How do I manage critical cluster services required across all apps on clusters?
* How do I optimize cost of my cluster?
* How do I do forensic dumps?

## Keiko Components
* [Instance-manager](https://github.com/keikoproj/instance-manager)
* [Upgrade-manager](https://github.com/keikoproj/upgrade-manager)
* [Addon-manager](https://github.com/keikoproj/addon-manager)
* [Governor](https://github.com/keikoproj/governor)
* [Lifecycle-Manager](https://github.com/keikoproj/lifecycle-manager)
* [Minion-manager](https://github.com/keikoproj/minion-manager)
* [Kube-forensics](https://github.com/keikoproj/kube-forensics)
* [Active-monitor](https://github.com/keikoproj/active-monitor)

## Demos

* Instance-manager demo

[![Instance-Manager](http://img.youtube.com/vi/-HZokimmSxQ/0.jpg)](https://www.youtube.com/watch?v=-HZokimmSxQ "instance-manager demo")
  
## Who uses Keiko?
As the Keiko Community grows, we'd like to keep track of our users. Please send a PR with your organization name.

Currently **officially** using Keiko:

1. [Intuit](https://www.intuit.com/)

## Community Blogs and Presentations
* [CNCF End User Sig](https://github.com/keikoproj/keiko/blob/master/presentations/Keiko.pdf)
* [AWS Community Day](https://www.youtube.com/watch?v=kdSE8r7uzXc&feature=youtu.be&t=1)
* [Bayarea Kubernetes Meetup Slides](https://github.com/keikoproj/keiko/blob/master/presentations/Keikoproj%20Instance%20and%20Addon%20Management%20Bayarea%20Kubernetes%20meetup.pdf)

## Resources
* [Keiko Slack](https://join.slack.com/t/orkaproj/shared_invite/enQtNzM3MTM1MDA5MjcxLWU4NTc5Nzc5OTVjOWI1NzA5NWNmNGExMDBmNjU2MDE1ZmZiOGU3ZGZkYmY0N2UzMzQ5MDEyMzQwY2UyMjdhOGI)
* [@keikoproj](https://twitter.com/KeikoProj)
