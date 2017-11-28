@title[Contracts Test]
## Contracts Test
##### <span style="font-family:Helvetica Neue; font-weight:bold"><span style="color:#e49436">Deploy</span> with confidence</span>

---
@title[Simple Scenario]

## Simple Scenario
<span style="font-size:0.6em; color:gray">Weekend.</span> |
<span style="font-size:0.6em; color:gray">3AM</span>

+++
@title[Go Fullscreen]

## Support called the on-call person!
Problem in *PHP API*   
On-call deployed a **Hotfix** affecting the API output.

+++

## Disaster!
<span style="font-size:0.6em; color:red">iOS app not retreiving ads.</span>

+++
@title[How]

#### How ?

<br>

Each *Consumer* expect a response in a specific format from   
**Provider** and it changed without any notice.

---

## Dico
<span style="font-size:0.6em; color:gray">Consumer ?</span> |
<span style="font-size:0.6em; color:gray">Provider ?</span>

+++
@title[Definiton]

#### Definiton

**Provider** : Represents a Micro Service, API, Third party API, Database.
<br>
**Consumer** : Front-end, Mobile app, Hardware consuming our API

---
@title[How our Producers are working]

### How our Producers are working
<span style="font-size:0.6em; color:gray">Single Provider</span> |
<span style="font-size:0.6em; color:gray">Different Consumers</span>

+++
@title[Many consumers rely on provider]
#### Many Consumers rely on a single Provider

+++?image=assets/current-services.png&size=auto 60%
<!-- .slide: data-background-transition="none" -->
+++?image=assets/current-services1.png&size=auto 60%
<!-- .slide: data-background-transition="none" -->
+++?image=assets/current-services2.png&size=auto 60%
<!-- .slide: data-background-transition="none" -->
+++?image=assets/current-services3.png&size=auto 60%
<!-- .slide: data-background-transition="none" -->

+++
@title[Another Example]

![Another-Example](assets/consumer-drivern-contracts.png)

---
@title[Pact.IO]

## Let's Discover
## Pact.IO
<span style="font-size:0.6em; color:gray">Contracts testing.</span> |
<span style="font-size:0.6em; color:gray">Just a Spec.</span>

+++
@title[Definition]

#### What is Pact

The **Pact** family of frameworks provide support for Consumer Driven Contracts testing.

+++
@title[Consumer Driven Contracts]

#### Consumer Driven Contracts

A Contract is a collection of agreements between a client (Consumer) and an API (Provider) that describes the interactions that can take place between them.

Consumer Driven Contracts is a pattern that drives the development of the Provider from its Consumer's point of view. It is TDD for services.

Pact is a testing tool that helps you write Contracts, and guarantees those Contracts are satisfied.

+++
@title[After Pact]

## After Pact

![After-Pact](assets/consumer-drivern-contracts-pact.png)

+++
@title[Consumer Expectations]

<span style="color:gray; font-size:0.7em">Define <b>Consumer Expectations</b></span>

![Consumer-Expectations](assets/step1.png)

+++
@title[Verify Expectations]

<span style="color:gray; font-size:0.7em">Verify expecations on <b>Provider</b></span>

![Verify-Expectations](assets/step2.png)

+++
@title[Matching]

#### Pact Matching

* Matching Header
* Matching Bodies

![Matching](assets/match.png)

+++
@title[Steps]
## Steps

* Set up mock server
* Set up expectations
* Act & Assert
* Setup Test Data
* Verify Failure / Success


---
@title[Pact Allows]

## Pact Allows you to :
* Modify components with agility and quick feedback on breakages
* Have confidence that all services in your system will communicate together
* Throw away integration tests

+++

#### References

* Pact Spec : https://github.com/pact-foundation/pact-specification/
* Testing Stratigies in Microservices : https://martinfowler.com/articles/microservice-testing/

---
@title[The End]

<br>
#### Thank You!

![Gopher](https://i.pinimg.com/originals/de/4d/af/de4daf20b7e43fc4bca3450d86a1a32c.png)