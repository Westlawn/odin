#[Welcome to the Westlawn curriculum](https://www.westlawn.org)
The Westlawn web site is based on a fork of The Odin Project. Therefore, the
code remains under the same MIT license as The Odin Project.

The Odin Project (https://www.theodinproject.com) is an open source community
and curriculum for learning web development. Students of The Odin Project build
portfolio projects and complete lessons that are constantly curated and updated
with links to relevant resources.

Odin teaches:
* Ruby programming
* Sinatra
* Ruby on Rails
* SQL
* HTML and CSS
* Javascript and Jquery
* How to go about getting a job in the industry

Westlawn has two schools, the Yacht Design Institute (YDI) and Software
Institute (STI). YDI teaches:
* Yacht Design, the full 4 module course
* Yacht Design Lite, a 1 module course that is a subset of the full course
* Metal Corrosion in Boats

STI teaches:
* Behavior Based Design for Object-Oriented C
* Control Systems using Raspberry Pi

## Complete system consists of two repos and Discourse
This repo contains the main app. A second repo contains the curriculum,
including lesson and project content data. Discourse, a rails based forum,
is run as-is in a Docker container on Digital Ocean.

This repo contains the main app. It is a fork of the repo for the Odin Project
that can be found online at [theodinproject.com](https://www.theodinproject.com).
We expect that modifications to this app will be oriented towards business
logic such as billing, generating reports for accreditation and management.

A second repo, referred to as the curriculum repo, contains the lesson and
project content data. Rake tasks in this Odin repo are used to pull in the
lesson and project content from the appropriate curriculum. For The Odin
Project, the [curriculum repo is](https://github.com/TheOdinProject/curriculum).
The [Westlawn curriculum repo is](https://github.com/Westlawn/curriculum).

The Odin project community can be found on the
[Gitter chat rooms](https://gitter.im/TheOdinProject/theodinproject).

## Prepare your repository
When you first clone the Westlawn/odin repository, you probably need to set the
upstream repository. I am not sure why, because github does know Westlawn/odin
in a fork, yet doing a clone does not (or at the time, did not) set the upstream
repository. I had to do what was documented here:
* https://help.github.com/articles/configuring-a-remote-for-a-fork/
* https://help.github.com/articles/syncing-a-fork/


## Contributing to The Odin Project
[![Build Status](https://travis-ci.org/TheOdinProject/theodinproject.svg?branch=master)](https://travis-ci.org/TheOdinProject/theodinproject)
[![View Performance Data on Skylight](https://badges.skylight.io/status/g0gJSNnzYAws.svg)](https://oss.skylight.io/app/applications/g0gJSNnzYAws)

The Odin Project depends on open source contributions to grow, improve, and thrive.
We welcome contributions from beginners and experienced developers alike.

To find out more about how you can contribute, please read our [contributing guide](https://github.com/TheOdinProject/theodinproject/wiki/Contributing-Guide).

## Significant Contributors to The Odin Project

* [Erik Trautman](https://github.com/eriktrautman)
* [Afshin Moktari](https://github.com/afshinator)
* [Josh Gorchov](https://github.com/gorchov)
* [Joe Sawyer](https://github.com/zkay)
* [Bill Walker](https://github.com/mach1010)
* [Neil Gehani](https://github.com/ngehani)
* [Ian White](http://github.com/Iawhite76)
* [Nathan Hall](http://github.com/dominathan)
* [Abby Jones](http://github.com/AbbyJonesDev)
* [Kevin Mulhern](https://github.com/KevinMulhern)
* [Arun Kumar](https://github.com/arun1595)

---
* Created by [Erik Trautman](http://www.github.com/eriktrautman)
* Westlawn fork created by [David Smyt](http://www.github.com/david-smyth)
