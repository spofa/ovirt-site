---
title: Develop
category: developer
authors: dneary, jbrooks, ykaplan
wiki_category: Developer
wiki_title: Develop
wiki_revision_count: 8
wiki_last_updated: 2012-11-30
---

# Develop

__NOTOC__

<div class="row">
<div class="span4">
## Projects

oVirt is a [ collection of projects](Architecture) which work together to provide a complete data center virtualization solution.

ovirt-engine  
oVirt Engine allows you to configure your network, storage, nodes and images. oVirt Engine also provides a command line interface tool (ovirt-engine-cli) and a RESTful API (ovirt-engine-api), including a Python wrapper (ovirt-engine-python-sdk) which allow developers to integrate management functionality into shell scripts of third party applications.

VDSM  
The Virtual Desktop and Server Management daemon runs on oVirt managed nodes, and allows oVirt to remotely deploy, start, stop and monitor virtual machines running on the node.

ovirt-node  
oVirt Node is just enough operating system to run virtual machines. It is also possible to convert a standard Linux distribution into a node which can be managed by ovirt-engine by installing VDSM and other dependencies.

dwh and reports  
The reports and data warehouse components for ovirt-engine are optional, and are packaged and developed separately.

*More information on [ oVirt subprojects](subprojects)*

</div>
<div class="span4">
</div>
<div class="span4">
## oVirt Architecture

![oVirt architecture](Overall-arch.png "oVirt architecture")

</div>
</div>
<Category:Developer>