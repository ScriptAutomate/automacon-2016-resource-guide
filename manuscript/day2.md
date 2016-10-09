# AutomaCon Day 2

## [KEYNOTE] Infrastructure as Code Might Literally Be Impossible, Part 2
**[Joe Damato](https://twitter.com/joedamato), Founder, CEO @ [Packagecloud.io](https://twitter.com/packagecloudio)**

*This talk will pick up from last year’s talk by continuing to examine some odd bugs in several package managers, the difficulty of trying to tune and configure the Linux kernel, and more.*

* Blog: [Package Cloud Blog](http://blog.packagecloud.io/)
* Recordings/Articles of the presentation
  * [Infrastructure as Code Might Literally Be Impossible, Part 1 (2015)](http://blog.packagecloud.io/eng/2015/09/15/automacon-infrastructure-as-code-might-be-literally-impossible/)
  * [Infrastructure as Code Might Literally Be Impossible, Part 2 (2016)](http://blog.packagecloud.io/eng/2016/09/28/automacon-2016-infrastructure-as-code-might-be-literally-impossible-part2/)
* Misc Resources
  * [A Look in the Mirror: Attacks on Package Managers](https://www.cs.arizona.edu/~jsamuel/papers/cappos-samuel-baker-hartman-ccs08.pdf)
  * [Monitoring and Tuning the Linux Networking Stack: Receiving Data](http://blog.packagecloud.io/eng/2016/06/22/monitoring-tuning-linux-networking-stack-receiving-data/)
  * [Stop Demonizing curl | bash](https://speakerdeck.com/jtimberman/stop-demonizing-curl-bash)
  * [The Problem with Linux Kernel Documentation, and How We're (as in Samsung, is) Fixing It](https://blogs.s-osg.org/problem-linux-kernel-documentation-fixing/)

---

## Automating Kubernetes Cluster Ops at Digital Ocean
**[Dan Norris](https://twitter.com/protochron), Software Engineer @ [Digital Ocean](https://twitter.com/digitalocean)**

*One of the most challenging parts of getting started with Kubernetes or other container orchestration tools is figuring out how to automatically deploy a cluster suitable for production workloads. Provisioning by hand works well the first time, but what about the second time? Third? Thirtieth?*

*In this talk, you'll learn about how infrastructure as code has helped us rethink how we manage the infrastructure that powers DigitalOcean's internal development platform. You will also learn about how we automatically secure our platform by distributing secrets and generating TLS certificates.*

* Blog: [Digital Ocean Blog](https://www.digitalocean.com/company/blog/)
* GitHub: [@protochron](https://github.com/protochron)
* Recordings/Articles of the presentation
  * 

---

## Open Source, Supply Chains, and You!
**[Robyn Bereron](https://twitter.com/robynbergeron), Community Architect @ [Ansible by Red Hat](https://twitter.com/ansible?lang=en)**

*When we talk about DevOps, there are (a minimum of, anyway) two topics that get at least passing mentions: feedback loops, and the concept that "DevOps isn't tools." However, the discussion of feedback loops rarely moves beyond the realm of the loop between dev, ops, and occasionally the end user / customer; and even though DevOps may not be just tools, tools can certainly be considered part of the supply chain that enables a team to, ahem, DevOps their way to delivering on their commitments.*

*But do we have healthy feedback loops with the creators of the software we depend upon — or even find value in such a relationship?*

*In this talk, Robyn Bergeron will share why choosing tools that are open source really matters — and what qualities one should look for, and encourage, in the open source communities that create the infastructure software your team or organization depends upon.*

* Blog: [Robyn's Wordshack](https://robyn.io/)
* GitHub: [@robynbergeron](https://github.com/robynbergeron)
* Recordings/Articles of the presentation
  *  
* Misc Resources
  * [11Foot8 Bridge Crash Compilation](https://www.youtube.com/watch?v=xzkWTcDZFH0)

---

## The Network is Infrastructure Too
**[Pete Lumbis](https://twitter.com/PeteCCDE), Systems Engineer @ [Cumulus Networks](https://twitter.com/CumulusNetworks)**

*Infrastructure as code and automation generally focuses on servers, storage and application deployment and management. This glosses over the critical function the network plays in the environment. This talk will cover automating and testing all infrastructure, including network and compute. This will also show how to tie network changes to CI/CD pipelines.*

* Blog: [Robyn's Wordshack](https://robyn.io/)
* GitHub: [@plumbis](https://github.com/plumbis)
* GitLab: [@plumbis](https://gitlab.com/u/plumbis)
* Recordings/Articles of the presentation
  *  
* Misc Resources
  * [Demo of Continuous Integration for Networks](https://gitlab.com/plumbis/cumulus-ci-cd)
  * [Behave: Behavior-Driven Development w/ Python](http://pythonhosted.org/behave/)

---

## The Psychology of Security Automation
**[Jason Chan](https://twitter.com/chanjbs), Engineering Director @ [Netflix]()**

*How do engineers perceive security and the security teams they work with? How can these perceptions (and realities) be used to optimize investments in security automation? Drawing on his experience in many areas of the security industry, Jason will discuss how tool builders can successfully approach security automation. Various security-related Netflix OSS projects will be used to illustrate.*

* Blog: [Netflix Tech Blog](http://techblog.netflix.com/)
* GitHub: [@netflix](http://netflix.github.io/)
* Recordings/Articles of the presentation
  *  
* Misc Resources
  * [Lemur: Open Source Certificate Manager (Netflix OSS)](https://github.com/Netflix/lemur)
  * [Scumbler: Web App That Kicks Off Workflows Based on Search Results (Netflix OSS)](https://github.com/Netflix/Scumblr)
  * [Gitrob: Putting the Open Source in OSINT](https://github.com/michenriksen/gitrob)

---

Habitat 101, An Introduction to Habitat
**[Joshua Timberman](), Code Cleric @ [Chef]()**

Habitat is an open-source framework that gives modern application teams an application-centric automation platform. Build, deploy, and manage modern and legacy applications with Habitat.

In this talk we will explore:

* Introduction to Habitat
* The problems Habitat solves
* Getting started with Habitat Plans
* Using Habitat in your Chef workflow

---

Achieving continuous deployment on Kubernetes
by Dan Bode , Senior Engineer @ Intel
Wednesday, September 28, 2016 at 2:30 PM

At Intel, we selected Kubernetes as the platform for building a Testing-as-a-Service offering for our internal development teams. In doing so we realized several key benefits: it simplified the deployment model, reduced configuration entropy, and allowed us to easily auto-scale agents to meet peak demand.

While the initial proof of concept was easy, implementing continuous deployment proved to be much more challenging.

This presentation will cover our solution, including the features we used and the role that configuration management played in getting us from: "I’ve seen it work" to having confidence that any individual change won’t result in service downtime.

---

Infrastructure as Code with Terraform
by Seth Vargo , Head of Evangelism @ Hashicorp
Wednesday, September 28, 2016 at 2:50 PM

This talk is aimed at teaching users the internals and externals of Terraform, a free and open source tool for provisioning infrastructure. Terraform truly encapsulates "infrastructure as code" with its declarative DSL, the ability to manage cloud and bare-metal resources, and expanding community support for CDNs, third-party mail providers, and more.

Terraform's graph-based approach allows for maximum parallelization, making it one of the faster infrastructure provisioning tools on the market. With a VCS-friendly format and remote state management, Terraform is also a great tool for working in a team environment.

Come learn about using Terraform to manage your infrastructure!

---

Unikernels: A New Frontier
by John Feminella , Advisor @ Pivotal
Wednesday, September 28, 2016 at 3:30 PM

Unikernels are a powerful new technique for generating compact, isolated containers with minimal surface area. But like all powerful tools, their benefits and disadvantages must be carefully weighed. Are unikernels worth the tradeoffs required?

In this talk, we'll try to answer this question by providing a brief introduction to unikernels, show you how to build your own, and explaining the most important considerations of running them in the real world.

---

State of Infrastructure as Code
by Chris Munns , Business Development Manager -- DevOps @ Amazon Web Services
Wednesday, September 28, 2016 at 3:50 PM

At Amazon Web Services we think about Infrastructure as Code being able to impact not just your low level infrastructure or operating systems but everything from the virtual cement floor of your Amazon Virtual Private Cloud up through the applications your customers interface with.

Come take a tour of the space as we see it. Learn what layers there are to managing your infrastructure as code and what services and tools AWS and its Partners exist across these.

---

Everybody has a plan until... -- Automation Evolution While Scaling
by Pete Cheslock , Sr Director Ops and Support @ Threat Stack
Wednesday, September 28, 2016 at 4:10 PM

Many people dream of the opportunity for a true greenfield deployment opportunity. Where they can join a new or existing company and build things The Right Way™. That idea is all well and good until the plans change. And your plans will always change. There are far too many things outside of your control when it comes to how you design and build your automation tooling. Often times you need to pick something you know will work and promise yourself you will go back and fix it later.

Join me as I talk about the early days of Threat Stack and how we built out our initial automation and software delivery pipeline. Then, hop on board the scale train as I share with you how we evolved our infrastructure delivery to meet our growing needs. I'll share with you some of the tooling we built in house to help us, as well as the OSS tools that we consume