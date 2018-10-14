---
layout: post
title:  Google Summer Of Code 2018
date:   2018-03-15 16:40:16
description: 
---

Google Summer of Code is finally over and I had an amazing 4 months. This blog is meant to document my work in short. Checkout [aima-exercises](http://aimacode.github.io/aima-exercises) and [aima-exercises-api](https://aima-exercises.firebaseapp.com/) to see what I made during the summer of 2018.

# Project
I worked with the organization AIMACode as a part of Google Summer of Code 2018. I was directly supervised by [Peter Norvig](https://en.wikipedia.org/wiki/Peter_Norvig) for the project named "AIMA Exercises". The goal was to design and implement a new platform to host interactive exercises for the fourth edition of the book “Artificial Intelligence: A Modern Approach”. This platform is not only meant to host the questions,  but also serve as a community to engage students and instructors.

# Proposal
My proposal can be found [here](http://)
 
# Work done
Most of the commits I made during GSoC were in the repository [aimacode/aima-exercises](https://github.com/aimacode/aima-exercises). I also made few commits in a helper repository [nalinc/aima-exercises-api](https://github.com/nalinc/aima-exercises-api) which hosted the microservice for API endpoints. In total, I submitted around 80 commits and changed a over 4000 files in both aima-exercises and aima-exercises-api 

Following are the most significant commits I made during this period.

### Milestone 1
- Conversion of Latex to markdown.
    * [@1e961a4](https://github.com/aimacode/aima-exercises/commit/07d7300671b050215bd9d798f36146cf21e961a4)
    , [@07e7f65](https://github.com/aimacode/aima-exercises/commit/674119d13807a418da26dec219cc5847707e7f65)
    , [@73d41cf](https://github.com/aimacode/aima-exercises/commit/37c789c0ce23602786c54bf06784eac6173d41cf)
    , [@3d17b22](https://github.com/aimacode/aima-exercises/commit/13c391ce631acda7dc400c225ff7df48f3d17b22)
- Implemented Table-of-Contents
- Made each question individually addressible by implementing "Exercise mode".
    * [@691a4c5](https://github.com/aimacode/aima-exercises/commit/d191743c8c64383b7b69d764471214089691a4c5)
    , [@b18eb11](https://github.com/aimacode/aima-exercises/commit/839c752db8587d8242ff88fb249fc9471b18eb11)
    , [@2435447](https://github.com/aimacode/aima-exercises/commit/05b317b85542fe2c56eaf000d0de5ef912435447)
    , [@6970f3d](https://github.com/aimacode/aima-exercises/commit/bbb6ccd602746f2699e8ef678cd8ea2096970f3d)
    , [@936a7bf](https://github.com/aimacode/aima-exercises/commit/667c7fb86001cc59a22b140605998ef46936a7bf)
    , [@1be23be](https://github.com/aimacode/aima-exercises/commit/a6db0a8f02204871936f9c72ab158ee641be23be)


### Milestone 2
- Created a microservice based on firebase cloud functions
    * [nalinc/aima-exercises-api](https://github.com/nalinc/aima-exercises-api)

- Implementation of a ranking system for exercises.
    * [@55d12e0](https://github.com/aimacode/aima-exercises/commit/287578c7f13a4c67455461ec22f588bc755d12e0)
    , [@57afafd](https://github.com/aimacode/aima-exercises/commit/e2d2f72276495032dad318a120aff8dc957afafd)
    , [@fabd1ac](https://github.com/aimacode/aima-exercises/commit/6a5e27c65f44cd28b1207b1922032e536fabd1ac)
- Allowing users to edit exercises and their solutions
    * [@c8e3a78](https://github.com/aimacode/aima-exercises/commit/05d25473d666b6d7df0aed0765c2d79abc8e3a78)
    , [@eef2457](https://github.com/aimacode/aima-exercises/commit/299f54004adb083aa316f51bfc21b12b0eef2457)
    , [@541fddb](https://github.com/aimacode/aima-exercises/commit/900682efa151a3f47ccd409739c245f8c541fddb)
- Integrating discussion support.
    * [@42af627](https://github.com/aimacode/aima-exercises/commit/ab366b891251c9c8c5728d2e2b7eb0ed742af627)


### Milestone 3
- Full text search support 
    * [@74269c1](https://github.com/aimacode/aima-exercises/commit/e8bba7050b66ee14a37a7710015b8c28274269c1)
    , [@1ffd091](https://github.com/aimacode/aima-exercises/commit/cc54ca5472f8b536699dc3354ce45e3c51ffd091)
    , [@a79c5ae](https://github.com/aimacode/aima-exercises/commit/cc106533231c36040a0f97679dad49c1ca79c5ae)

# Future Work
Future contributors can work on a number of features to improve AIMA-Exercises. Some of these include:
- Implementing a run-time system to add/edit exercises in the platform (instead of doing this from Github)
- Providing better support for cross-references.


# Acknowledgements
I would like to express my sincere gratitude to my mentor Peter Norvig for the continuous support throughout the project timeline. 

I am very grateful to Google which provided me with this golden opportunity.


