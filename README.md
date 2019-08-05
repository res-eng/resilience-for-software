<!-- prettier-ignore-start -->

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Resilience engineering for software: a FAQ](#resilience-engineering-for-software-a-faq)
  - [What is resilience engineering?](#what-is-resilience-engineering)
  - [What is the relationship between resilience engineering and DevOps/SRE?](#what-is-the-relationship-between-resilience-engineering-and-devopssre)
  - [I’m intrigued, what are my next steps?](#im-intrigued-what-are-my-next-steps)
  - [What should I do if I have other questions?](#what-should-i-do-if-i-have-other-questions)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

<!-- prettier-ignore-end -->

# Resilience engineering for software: a FAQ

## What is resilience engineering?

Resilience engineering can be viewed as a set of high-leverage approaches to managing
failures in complex socio-technical systems -- which makes it a domain relevant to many
technology companies.

Failure in complex systems is itself a complex subject. The paper
[How Complex Systems Fail](https://how.complexsystems.fail) by Richard Cook is an
excellent short introduction. For a higher fidelity definition, see John Allspaw’s talk
[Resilience Engineering: The What and How](https://www.youtube.com/watch?v=9f4-Z8Tasa8).

Complex systems have bounded resources and you probably have limited time. Expect
resilience engineering to be highest leverage when failures (e.g., incidents) are
substantially impacting the sustainability of your systems, the happiness of your
engineers, your ability to meet business needs, and/or the happiness of your customers
([framing borrowed from Honeycomb](https://www.honeycomb.io/framework-for-an-observability-maturity-model-using-observability-to-advance-your-engineering-product/)).

## What is the relationship between resilience engineering and DevOps/SRE?

DevOps’ approach to safety focuses on mitigating the impact of known modes of failure --
“known unknowns” like bad deploys, host failures, etc. Resilience engineering is
concerned with the ability to adapt to unknown unknowns -- for example, how did your
organization respond to the decades old latent flaw that became Spectre/Meltdown?

For further insight you can read the preface and conclusion chapters (of course, more if
you're inspired) of [Accelerate](https://itrevolution.com/book/accelerate/) by Nicole
Forsgren PhD, Jez Humble, and Gene Kim and
[Sustainable Operations in Complex Systems with Production Excellence](https://www.infoq.com/articles/production-excellence-sustainable-operations-complex-systems/)
by Liz Fong-Jones, and comparing the perspectives there with those of Cook and Allspaw
expressed in the resources linked above.

## I’m intrigued, what are my next steps?

For most software organizations, the low hanging fruit of resilience engineering will be
learning more from incidents by improving the postmortem process. Etsy has an
[excellent guide](https://extfiles.etsy.com/DebriefingFacilitationGuide.pdf).

Beyond that, if you want to learn more about the domain and enjoy reading academic
papers, see Lorin Hochstein’s
[paper-centric introduction](https://github.com/lorin/resilience-engineering/blob/master/intro.md).
If you prefer conference talks, John Allspaw has curated a
[YouTube playlist](https://www.youtube.com/playlist?list=PLb1aZTnPf3-OMChMkrr6WsokRI6LOnuem).
Nora Jones also runs a resilience engineering focused Slack Community,
[Learning From Incidents in Software](https://github.com/norajones/LFI-Slack/blob/master/README.md).

## What should I do if I have other questions?

Your options include

1. Open an issue on this repo
1. Reaching out to [Lorin Hochstein](https://twitter.com/lhochstein),
   [Jacob Scott](https://twitter.com/jhscott), or others in the resilience engineering
   community on Twitter
1. Contacting Allspaw, Cook, and Wood’s consultancy,
   [Adaptive Capacity Labs](https://www.adaptivecapacitylabs.com/), if you want to work
   with subject matter experts in a professional/contractual setting
