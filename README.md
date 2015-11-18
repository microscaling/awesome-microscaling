# Awesome Microscaling [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of Microscaling related principles and technologies inspired by [awesome-microservices](https://github.com/mfornos/awesome-microservices). Microscaling.org redirects here.

## What is Microscaling?

Microscaling is scaling containers in real time based on current demand. It leverages the much faster startup and shutdown times of containers. The term is used to differentiate it from traditional auto scaling where you scale Virtual Machines, but it takes minutes.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [Schedulers](#schedulers)
- [Frameworks](#frameworks)
- [Demos](#demos)
- [Theory](#theory)
  - [Articles](#articles)
  - [Papers](#papers)
  - [Talks](#talks)
- [License](#license)
- [Contributing](#contributing)
- [Acknowledgments](#acknowledgments)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Schedulers

- [Kubernetes](https://github.com/kubernetes/kubernetes/blob/cf8c2105028719b309e2bdc15ad93067247f08ba/docs/design/horizontal-pod-autoscaler.md#horizontal-pod-autoscaling) - Horizontal Pod autoscaling (under development).

## Frameworks

- [Fenzo](https://github.com/Netflix/Fenzo) - Netflix framework for Mesos that autoscales both containers and host VMs.

## Demos

- [Microscaling-in-a-Box](https://app.force12.io) - simple demo of microscaling that runs on Docker on your local machine.

## Theory

### Articles

- [InfoQ interview](http://www.infoq.com/news/2015/09/force12io-microscaling-mesos) - interview on microscaling with Ross Fairbanks by Daniel Bryant.
- [Microscaling with load balancing in ECS](http://circle-theory.blogspot.co.uk/2015/11/microscaling-with-load-balancing-in.html) - blog post by Adam Christie.

### Papers

- [Borg](http://research.google.com/pubs/pub43438.html) - Large-scale cluster management at Google with Borg.
- [Omega](http://research.google.com/pubs/pub41684.html) - Omega: flexible, scalable schedulers for large compute clusters.

### Talks

- [Game of Hosts: Containers vs VMs](https://www.youtube.com/watch?v=LaeQnlf2U84&index=1&list=PLDbVx7MrElf2VxfaOhNGAHgStgVaILlr4) - talk by Anne Currie at DevOps Exchange London meetup.
- [Netflix Titan platform](https://www.youtube.com/watch?v=V3OfAATYksM) - talk by Diptanu Choudhury at DockerCon 2015.

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

## Contributing

Please, read the [Contribution Guidelines](https://github.com/force12io/awesome-microscaling/blob/master/CONTRIBUTING.md) before submitting your suggestion.

Feel free to [open an issue](https://github.com/force12io/awesome-microscaling/issues) or [create a pull request](https://github.com/force12io/awesome-microscaling/pulls) with your additions.

:star2: Thank you!

## Acknowledgments

Table of contents generated with [DocToc](https://github.com/thlorenz/doctoc)
