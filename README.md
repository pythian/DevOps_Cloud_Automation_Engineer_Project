# DevOps Cloud Automation Engineer Project

## Overview

This project is an opportunity to have some fun and show off your technical skills.  The reason we offer it to new job candidates is because we want to see how people think and solve problems.  You'll probably need to Google a few things while you work on this project and that's fine.  We don't expect that everyone will be experts in every technology, but we do look for people that are curious.  Curious people don't let small hurdles stop them.  They look for solutions to problems and find ways to move projects forward.

Feel free to ask questions about this project, but know that 50 people might complete it 50 different ways.  We're looking to see how you work and what solutions you come up with.

## What You'll Be Building

The goal of this project is to use Vagrant to build a VM that is configured automatically.  Your automation should fully patch the VM, install git; mysql; and apache, and then automatically test if each application is installed.  After this check, your automation should clone a git repository of your choice to the Vagrant VM in the /opt/code directory.  The owner and group of the cloned files should be pythian:pythian.

## Other Details

The /opt/code ownership and permissions should match the state below.

```
drwxr-x--- 0 pythian pythian 512 Jul 14 08:03 code
```

When testing if the applications are installed, your automation should produce output consistent with the following example

```
git... Installed
mysql... Not Installed!
apache... Installed
```
## Solution Submission

We prefer that final solutions be delivered via a public GitHub repository.  Please note that due to the nature of public GitHub repositories, your solution will be publicly available for as long as you keep the repository.

Other arrangements can be made for circumstances in which candidates are not comfortable releasing their code via a publicly accessible repository.  Please let us know if you would prefer an alternate method of sending your solution.  It's preferred that the version control history be maintained so that it may be reviewed.

