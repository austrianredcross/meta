# The Stopp Corona App Covenant

We, the Austrian Red Cross, have Open Sourced our Stopp Corona application with
the intention to both show the inner workings of it but also to share our
experiences with other countries.

We have licensed our code under a very liberal Apache 2.0 license which should
put no restrictions on the ability to both contribute back to it, as well as to
be able to use it in other countries.

We strongly believe in a privacy first approach and have designed it around a
decentralized architecture. It’s our intention to port the core cryptography
layer to [DP-3T](https://github.com/DP-3T/documents/blob/master/DP3T%20White%20Paper.pdf)
or the [Apple/Google tracing
architecture](https://www.apple.com/covid19/contacttracing) once we have found
a way to make the flows envisioned in the application work on that system.

For that reason we’re committing ourselves to these core values:

* **Human Rights and Human Dignity “by Design”:** the Red Cross as an
  international Organisation with a humanitarian purpose considers the
  international and indivisible Human Rights as the basic and common legal
  framework for all its actions. The EU Fundamental Rights Charter (CFREU)
  guarantees in Art 8 the Right to Data Protection. This right is a catalyst for
  the exercise of all rights and freedoms in a digital society and finally aims
  to ensure a life in freedom and dignity for all people. 
* **Transparency:** the version of the app store / play store of the
  application matches the code in this repository. While there will always be
  small differences that are unavoidable (such as signing keys, etc.) we want to
  be able for technically minded users to reproduce the release versions as close
  as possible.
* **Data Minimisation:** we want our application to stay true to the original
  scope. We do not want the application to become the vehicle that allows for
  user surveillance.
* **Decentralized Approach:** as an independent rescue organization we believe in a
  decentralized approach.  We extend this also to how we design the exposure
  notification flows in the application.
* **Voluntariness:** we believe that users should only use contact tracing apps
  out of their free will. We will not stand for a mandatory deployment of
  contact tracing apps.
* **Cooperation and Interoperability**: the virus does not stop a country's
  borders, and neither should tracing efforts. We want to work together with
  other organizations that share our ideals.  If you want to join the effort
  see [Cooperation and Funding](COOPERATION.md) for more information.
* **Global Scalability:** the system must scale favorably for outbreaks or
  countries larger than just one.

## Transparency

Trust in the application is paramount. We have committed us to ensuring that
what users get onto their phones is what is in this repository. We want to play
with open cards in all situations with one exception: security reports are
discussed in private until they are resolved.  To gain early access to security
relevated discussions also see [Cooperation and Funding](COOPERATION.md).

## Data Minimisation

We take great care to record the smallest amount of data necessary for the
operation of the application.  If an attacker runs gains access to the central
infrastructure the data they find must be as worthless as possible to them.

## Decentralized Approach

We believe in a (as much as possible) decentralized contact tracing solution.
We do not want our application to be abused for tracking or other purposes.
This is why we chose an architecture to avoid this, and we’re committed to
following decentralized developments if they strengthen our ambitions of
delivering a privacy-first application. For that matter we are actively working
together with DP-3T, Apple and Google on decentralized approaches to contact
tracing.

## Voluntariness

We condemn attempts to make the use of this application mandatory. The app is
based on voluntary participation and we strongly believe it should only be used
in that manner.
