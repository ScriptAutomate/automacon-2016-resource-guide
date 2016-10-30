# AutomaCon Day 3

## [KEYNOTE] Abstractions and Metaphors: Building Better Tools and Processes by Caring About Words
**[Nigel Kersten](https://twitter.com/nigelkersten), CIO & VP of Operations @ [Puppet](https://twitter.com/puppetize)**

*We use a lot of metaphors and abstractions in operations and our automation tooling such as "war room", "technical debt", and "orchestrate". Metaphors have largely been treated as a purely linguistic construction in the Western academic tradition, yet cognitive linguists such as George Lakoff argue that metaphors are in fact conceptual and shape our thoughts whether we’re aware of them or not. In this talk we’ll take a quick tour through some concepts of cognitive linguistic theory and how understanding the impact words have can lead to better tooling and processes.*

* Blog: [Nigel's Blog](http://explanatorygap.net/)
* Blog: [Puppet's Blog](https://puppet.com/blog)
* Recordings/Articles of the presentation
  *  
* Misc Resources
  * [Metaphors We Live By](https://www.amazon.com/gp/product/0226468011?pldnSite=1)

## Operations anti-patterns: how our bad habits harm systems reliability
**[Sam Kottler](https://twitter.com/samkottler), Engineering Manager @ GitHub**

*This talk with go through anti-patterns which harm the health of the systems we're tasked with operating. Some of the things we'll talk about have reached industrial meme status, yet when practically deployed actively harm the goals of those who focus on systems reliability. Others seem logical, but have hard-to-predict implications on the relationship between software and the systems on which that software runs. This brief overview of anti-patterns will go over why seemingly reasonable patterns can harm us and how to avoid them*

* Blog: [GitHub's Blog](https://github.com/blog)
* GitHub: [@skottler](https://github.com/skottler)
* Recordings/Articles of the presentation
  *  
* Misc Resources
  * 

## Don’t Stop Believing: Our Infrastructure as Code Journey at Paperless Post
**[Bethany Erskine](https://twitter.com/skymob), Staff Systems Engineer @ [Paperless Post](https://twitter.com/paperlessdev)**

*Take a walk with me through Paperless Post's journey from a humble startup with no operations team and 12 artisanal servers to 300 servers, 40 developers and 7 operations team members. I'll describe the problems we've solved and lessons we've learned in going from zero to Infrastructure as Code: the patterns and tools we employ, how we're doing it now, and how we could be doing it better as we grow in staff, traffic and sales.*

* Blog: [Bethany's Blog](https://github.com/blog)
* GitHub: [@skottler](https://github.com/skottler)
* Recordings/Articles of the presentation
  *  [Presentation Slides](https://speakerdeck.com/skymob/dont-stop-believing-our-infrastructure-as-code-journey-at-paperless-post)
* Misc Resources
  * 

## Infra as Code: The Organizational Bottleneck and the Shared Service Anti-Pattern
**[Evan Gilman](https://twitter.com/evan2645), Ops Engineer @ [PagerDuty](https://twitter.com/pagerduty)**

*As your company's Engineering team grows, and the rate of infrastructure evolution increases, it becomes increasingly apparent that it is not only your Ops team that needs to manipulate the infrastructure codebase - it's everyone! So tools are built, skills are taught, and before you know it, the infrastructure codebase is the most contentious in the whole organization. This talk chronicles PagerDuty's journey from Ops-driven evolution to distributed evolution, the pains involved and the hard lessons learned*

* Blog: [PagerDuty's Blog](https://www.pagerduty.com/blog/)
* GitHub: [@skottler](https://github.com/skottler)
* Recordings/Articles of the presentation
  *  
* Misc Resources

---


## Scaling A Volunteer Run Internet Exchange, Or: How I Learned to Stop Worrying and Love Automation
**Bronwyn Lewis @ SFMIX**

*An often unknown, and yet critical part of internet infrastructure, internet exchange points (IXPs) range from large commercial operations to a single switch set-up in someone's spare time. But how do you grow from a single point exchange to something bigger and better, with very few resources?*

*This is the ongoing story of the San Francisco Metropolitan Internet Exchange (SFMIX) — a non-profit IXP run by volunteers and crafted with love, git commits, and Ansible. Using devops and netdevops practices, we've learned a lot along the way about what works, what doesn't work, and what still needs work — and most importantly, how it is relevant to any organization or project. As a bonus, you' ll get to learn all about IXPs and how they help the internet.*

* Blog:
* GitHub:
* Recordings/Articles of the presentation
  *  [Presentation Slides](https://speakerdeck.com/bronwyn/scaling-a-volunteer-run-internet-exchange-or-how-i-learned-to-stop-worrying-and-love-automation)
  *  
* Misc Resources
  * 
---
## Code Review for Operations
**Spencer Krum , Engineer @ IBM / OpenStack**

*Code review has been shown to help developers produce better code. It can also help SREs run more reliable systems. Our ops team is fanatic about using code review and representing our infrastructure as code so that code review can be leveraged. In this presentation I will show how we use code review to manage our infrastructure, modify and create systems, administer services, etc. I'll show the path we took to get here, what actions couldn't be piped through code review, and what we're going to next.*

* Blog:
* GitHub:
* Recordings/Articles of the presentation
  *  
* Misc Resources
  * 
---

## MTLS in a Microservices World
**Diogo Monica , Security Lead @ Docker**

*Mutually authenticated TLS is the de facto standard for secure inter-service communication. Unfortunately, setting up a PKI, dealing with certificate issuance, rotation and revocation is hard, leading to only the most sophisticated companies deploying a fully MTLS infrastructure.*

*In this talk, I'll go over the advantages and disadvantages of using MTLS in a microservice architecture, describe how Docker's swarm currently tackles this issue, and give a live demo of how easy it is, and should be, to setup a fully-featured PKI infrastructure for your services.*

* Blog:
* GitHub:
* Recordings/Articles of the presentation
  *  
* Misc Resources
  * 
---

## Metrics are Infra, Metrics are Code: Yelp’s time series data at scale
**Zach Musgrave , Technical Lead @ Yelp**

*It’s 2016, and "measure absolutely everything" is the new normal. Servers are cheap, and data is abundant. Time series data drives engineering and business decisions, and systems enabling such high-scale collection must scale along with the rest of the organization.*

*Over the years, Yelp accumulated many ways of generating metrics, monitoring, doing analytics, and alerting. In the past year, a dedicated metrics team formed to integrate and maintain all the tools as a platform for the wider engineering organization - providing monitoring as a service. To achieve this, prinicples from the Infrastructure as Code movement become essential: ephemeral servers managed within version control, distributed configuration management via CI/CD pipelines, and aggressive containerization of federated resources via PaaS techniques.*

*Join us to hear about auto-scaling stateful aggregation systems that don’t want to auto-scale. Listen in for tools that work across vendors, libraries supporting in-house innovation, and a strong push toward self-service metrics for all our internal users. Check out Yelp’s approaches to redundant alerting, cheap yet resilient storage, and expressive client libraries that actually don’t suck.*

*"Who monitors the monitors?" We do.*

* Blog:
* GitHub:
* Recordings/Articles of the presentation
  *  [Presentation Slides (from this presentation, and others)](https://drive.google.com/drive/folders/0BxaAnWZmhGX6NnVfZjJBdHhXWFE)
* Misc Resources
  * 
---

## Organic, Free-Range Automation: A Release Engineering Story
**Morgan Rhodes , Release Engineer @ Puppet**

*The automation around building and shipping software quickly and easily grows to be very complex, especially when supporting a wide variety of platforms. When this automation grows rapidly and organically, the result is a tangled web of tasks that need some hand-holding to successfully run to completion. To allow these processes to scale, we need to move to consistent and reliable automation that can easily be handed off to others. This talk will focus on issues that have sprung up from organic tooling growth, goals for improving the automation, and how we're trying to move in that direction. I will also discuss approaching process improvements when working with legacy codebases, defeating complacency to build better automation, and channeling sadness into tooling improvements.*

* Blog:
* GitHub:
* Recordings/Articles of the presentation
  *  [Presentation Slides](http://www.slideshare.net/_morgan/organic-free-range-automation-a-release-engineering-story)
* Misc Resources
  * 
---

## Network Infrastructure as Code
**Lori MacVittie , Technical Evangelist @ F5 Networks**

*Software-defined Networking (SDN) may seem to be the One and Only Way for the network to stop being the hold up in continuous deployment but that's just not true. Treating the network infrastructure responsible for providing scale and security "in the network" as code provides for a better integrated and agile environment without the architectural debt required to implement SDN. This presentation will cover emerging trends in network infrastructure to support and enable continuous deployment by adopting an "infrastructure as code" approach.*

* Blog:
* GitHub:
* Recordings/Articles of the presentation
  *  
* Misc Resources
  * 
---

## Reflections on a year of DevOps Transformations -- a.k.a. "Tell me again how you thought this would be easy?"
**George Peden , Practice Lead, Technology Enablement @ Slalom Consulting**

*A reflection on the first year of Slalom's DevOps Transformation practice, including our point of view on DevOps as an organizational transformation effort (what? its more than tools and tech?), and highlights of our experience, learnings, challenges, and successes helping our clients on their DevOps journey.*

* Blog:
* GitHub:
* Recordings/Articles of the presentation
  *  [Presentation Slides](https://speakerdeck.com/gpeden/slalom-devops-automacon-2016)
* Misc Resources
  * 
---

## Improving Customer Experience through Infrastructure Automation
**Brandon Burton , Infrastructure Conductor @ [Travis CI](https://twitter.com/travisci)**

*As many of us know, automation is one of the cornerstones of cultivating a "DevOps culture." We've seen how automation helps improve the lives of operations and development folks. But, a "DevOps culture" is also about seeing the business as a whole and how to make "operations" work be seen as critical and important part of the business value chain. We should be thinking about how to directly link our infrastructure automation initiatives back to large goals and objectives that improve the customer experience.*

*This talk will share some of the key automation objectives the build infrastructure engineering group at Travis CI is doing, the process and challenges we've encountered we figure out how to incorporate the larger focus into work planning, and what's being done to measure the actual customer impact of our new infrastructure automation changes.*

* Blog:
* GitHub:
* Recordings/Articles of the presentation
  *  [Presentation Slides](https://speakerdeck.com/solarce/improving-customer-experience-through-infrastructure-automation)
* Misc Resources
  * 