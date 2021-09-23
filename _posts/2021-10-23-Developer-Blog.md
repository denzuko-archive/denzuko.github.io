---
title: Developer Blog - Week 38 2021
desc: |
  Developer Blog for the week of 38, 2021.
layout: post
excerpt_separator: <!--more-->
categories: Updates
---

Hoi \#DevOpsFam,

Been a long time since we've seen or heard from each other. Its the week of the Autumn Equinox, traditionally a time of reapping what one has 
sewn earlier in the year. Well this year we've visited Defcon, aquired a few positions in some major tech firms, and pushed forward 
in developing solutions for you the DevOps Community.

Overall though this year has been a lot of spring cleaning as well.

<!--more-->

## Projects

### XMCore BBS
If one has been looking to access XM Core BBS. The downside is the main vm is up but access to doors is offline while we migrate to a new platform
and move the CTF side of things into its own project. Good news is we've launched [hack the gibson](https://hackgibson.sh) an ARG CTF for cypherpunks 
and normies a like. With a lot of the haxor/phreaker themes and concepts one saw in the old XM Core has been moved to hack the gibson so it 
can take a life of its own there. Join us on [reddit](https://reddit.com/r/2600) to keep up to date on the developemnt and get early access. 
Its our hope to see Hack The Gibson at Defcon 30.

### AIMS, CommunityGrid, and you..

When AIMS started out there was only text files or semephore. Since then several offerings have come along and AXW is the version adopted 
by the community. This means AIMS will be moving in a new direction and becoming apart of the CommunityGrid project. While the internet is a buzz
with Kubernetes and a lot of tooling has popped up around it. Docker swarm is still here to stay and with the simplicty it brings we'll still continue
to support it fully. Future releases will see in house built toolkits to replace aging community projects orbiter, v2tec/watchtower, and shepard. 
While these projects are great in thier own right they miss functionality that are needed, auto roll over on failed image deployment, job scheduling,
and cluster maintence.

Further more the future of cloud commputing is not retrofuturism via ssh/tui, nor fancy react based dashboard/control panels. Its AI powered IPC 
via IoT and NUI. Thus future services would be designed around headless microservices that nodered, tensorflow, and dialogflow can interact with.
Any sort of ui element should be WebXR enabled but secondary.

### Ansible and Terraform

Hashicorp has finally found a killer product outside of vagrent. Terraform. But where terraform tends to be the 'ITOps programming language of Cloud -aaS' aka
infrastructure-as-code. Ansible still is a large player here; community.general.terraform allows one to manage terraform via ansible. Doing the next Quarter
We'll be bundling up existing terraform code we've worked on and wrapping it into ansible playbooks as container images.

### r2600 / DFW2600

Still going strong, We're getting more members and a lot are leaving the toxicity of 2600net. While there is no animosity towards the guys behind 2600net 
and any one is welcome to still visit the irc server. We're glad to be welcoming community that allows for incusivity without the typical bastard operator 
from 'ell type curmudgeons. Monthly events is in the works with live streams on discord.

## Supported Clouds and other platforms

After being an AWS user for ages, this year we've tried google cloud. While yes [dmsvintagecomputers](https://dmsvintagecomputers.com/) is using gcloud. Outside
of hack the gibson's cluster. All projects and services in google cloud will be discontinued this year. AWS does offer a lot of what we need but even this will
take a back burner for anything that's not an undercloud service. OVH, DigitalOcean, TurnkeyLinuxHub are still on the radar but are considered end of life 
support as well. As for Azure; well they need to 
[fix thier shit](https://media.defcon.org/DEF%20CON%2029/DEF%20CON%2029%20presentations/Jenko%20Hwong%20-%20New%20Phishing%20Attacks%20Exploiting%20OAuth%20Authentication%20Flows.pdf) first.

Going forward we're migrating individual projects back to heroku while leverging cloudflare workers and IPFS where possible. If one thinks this means that zapier, 
ifttt, or simular is going to be the norm for api usage then suprise. Flow.dapla.net is our go to for automated workflows and as 
[outlined](https://github.com/denzuko/denzuko.github.io/wiki/Heroku-Usage-with-apps-and-github-actions) github actions with ansible and terraform are being used 
to orchistrate our deployments.

As for other techs, [hypriot](https://blog.hypriot.com/) is still a strong player in our tech stack, [shadow pc](https://shadow.tech) has been an amazing platform 
to work with and given we're now rocking new [CB4](https://www.walmart.com/ip/SAMSUNG-CB4-11-6-Intel-Celeron-4GB-32GB-Chromebook-XE310XBA-K01US-Google-Classroom-Ready/558190726?athbdg=L1300) 
by Samsung as the main flagship around the labs. Shadow has been a large help for testing on windows machines or doing Design/GPU intenstive work.

Zerotier is still a strong goto as well but going to be less leveraged as of late since using IoT, Chatops, and IPFS as our main systems.

Odoo, Grav, nextcloud, and killbill is going to be deprecated this year, it fits well within a selfhosted workflow but been a pain to 
maintain without a dedicated team. We'll be moving all of that over to hubspot, namely, stripe, google workplace, and workers.dev.

The studio is also being overhalled massively.

## Nonprofit work

### enablingthefuture.org

Been an intersting adventure trying to setup printers for them. Went with Creately Ender Pro and never could get the bed to level nor prints to work.
Going to move these into the renovated studio but putting this on the back burner

### Dallasmakerspace.org

Fun times, still politically driven, still lower priority.

### AFL-CIO, Southern Poverty Law, Girlstart

Yep, you got my support still.

### Unesco and Kadampa Meditation Center

Thinking about this one.

### Others (including FOSS development)

Not taking on any more non profit work at this time.

## Next sprint's goals
  - Migrate apps to heroku pipelines
  - Build WebXR frontend and deploy to ipfs
  - Intrergrate Nodered and Dialogflow
  - Downsize on tech and lean in further with majordomo.fund
