---
title: "What is NetDevOps"
date: 2021-10-26T00:00:00+00:00
author: Reza Rezaei
layout: post
permalink: /what-is-netdevops/
categories: Theory
tags: [netdevops,devops]
---
![Netdevops]({{ site.baseurl }}/assets/images/whatisnetdevops.jpg "netdevops")

DevOps is a culture.

It is a mindset with a foundation in the [Agile Manifesto](http://agilemanifesto.org/).

Bridging the [gap between Dev and Ops](http://blog.datapath.io/devops-and-the-role-of-network-monitoring), while providing better software, more efficiently, through automation and replication.

There is also continuous delivery. DevOps is many things, but what is still on the horizon is bringing networking into the fold.

**This is NetDevOps.**

Bringing the DevOps principles to networking, and networking into the DevOps team.

[Cumulus networks has provided a great start to the NetDevOps movement](https://cumulusnetworks.com/blog/netdevops-networking-methods-with-a-devops-mindset/). The tools you are already using are incorporating it as well. Ansible, Chef, Puppet, and Red Hat are beginning to [incorporate DevOps into networking](https://www.ansible.com/press/red-hat-brings-devops-to-the-network-with-new-ansible-capabilities).

This brings us to NetDevOps. The intersection of networking and DevOps.

## **What is NetDevOps?**

NetDevOps
 is infrastructure as code. It is network automation. It is open 
communication. Similar to DevOps, the NetDevOps goals are as follows:

- Prevent fat fingers
- Repetitive tasks
- Reproduce and dispose things
- Deliver code

The result is network scalability and a replicable process.

## **Infrastructure as Code**

If NetDevOps is infrastructure as code, it makes sense to provide a definition:

“[Infrastructure as Code (IaC)](https://en.wikipedia.org/wiki/Infrastructure_as_Code)
 is the process of managing and provisioning computing infrastructure 
(processes, bare-metal servers, virtual servers, etc.) and their 
configuration through machine-processable definition files, rather than 
physical hardware configuration or the use of interactive configuration 
tools.”

What this provides is the ability to apply and deploy changes at scale, with the removal of manual configurations.

Traditionally,
 network changes had to be done on physical servers; manually and 
individually. With the application of infrastructure as code, this is 
accomplished remotely with the use of code. The code is then replicable 
and can be scaled. A benefit to this process is the ability repeat the 
processes that work particularly well.

The result is network automation.

## **Network Automation**

Network
 automation is the result of the NetDevOps approach. As DevOps places a 
large emphasis on automating processes, NetDevOps looks to share this 
goal. This is accomplished through a number of tools, [Datapath.io](http://datapath.io/) being one of them.

Network
 automation is setting parameters around network requirements, and 
implementing a set of code to replicate the process. The tools in your 
current stack of IT automation already allow you to accomplish this for 
other IT related functions, so let’s bring this to networking.

## **How Do I Incorporate NetDevOps?**

The
 first step in a NetDevOps approach is to pick an infrastructure which 
allows for the deployment of infrastructure as code for your network.

Two approaches are as follows:

**White-box Switches and Linux**

NetDevOps, in its current form, is done by setting up [White-box Switches](http://www.networkcomputing.com/networking/white-box-switches-are-you-ready/1465296666),
 installing Linux, and then utilizing your current DevOps IT stack. The 
White-box switches provide the ability to run code for your network.

**NetDevOps Through a Cloud Provider**

Making the transition to a cloud provider, such as AWS, provides infrastructure as code services through [AWS CloudFormation](https://aws.amazon.com/cloudformation/).
 As the rest of the DevOps team may already be employing tools that 
allow for automation in the cloud environment, applying this to 
networking is the next logical step.

The
 goal of NetDevOps is to find tools that allow you to monitor and 
automate your network. Whether this is to gain improved network speeds 
and performance, or to diagnose issues, NetDevOps brings the DevOps and 
networking team together.

---

## References

*Article originally posted on the [Datapath.io Blog](http://blog.datapath.io/what-is-netdevops).*