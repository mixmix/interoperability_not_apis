# Interoperability

# not APIs


_The capability of a system to interact and function with others._

---

## Roll back, roll forward

1. Prior art using APIs
2. The foundations of APIs
3. New solutions to interoperability

---

## Interfacing with my bank

![client server at a bank](client_server_analogy.jpg)

???

## What is an api?

An interface between two parties ... here the interface is that little window which you can ask questions through.
e.g. Can I have my statements, open a new account.

Some requests you might make are "not legal" e.g. give me all the money

---

## (Robot) Interfacing with my bank

![client server at a bank hardware](client_server_components.jpg)

???

A digital version of the same thing is played out with robots.
If we can program the robots to interface, we have a programmeable interface.

e.g. Kiwibank has a server my phone talks to, then displays results

---

## Better interfaces!

![](kiwibank_without_api.jpg)

???

here's my boring bank account page. I'm try to get a sense of how I'm managing my wellbeing spending

---

## Hooray accessibility!

![](kiwibank_with_api.jpg)

???

If Kiwibank had an API that was open to customers, I could easily build something like this.
I did build something like this, and made it a free tool. But it's crappier than it needs to be


---

## Dream bigger

![](asb_kiwibank.jpg)

???

I don't care about bank account though, I care about stability, and building a more awesome future. LET ME DO IT

---

## Interoperable

![](asb_kiwibank_api.jpg)

???

I could see bigger trends, understand my context more.
Coordinate mundane details easily.

---

## The Problem

![](asb_kiwibank_castles.jpg)

???

- No APIs
- wrong incentives
- even with APIs building interoperability is a pain in the arse

---

## Filing cabinets

![](asb_kiwibank_filing.jpg)

???

As long as filing cabinets exist, we're predisposed to hoarding and then having to try and build interfaces.

One major problem is dealing with duplication of data... 
e.g. identity - which is the Actual Me ... when there are copies of data about me held by multiple parties

---

## Content bound to a location

![](content_centric_0.jpg)

---

## Content-centric

![](content_centric_1.jpg)

---

## Content in multiple locations

![](content_centric_2.jpg)

---

## Navigating a range of filing cabinets

![](content_centric_3.jpg)

User Journeys: e.g. "applying for superannuation", "applying for student allowance"

Look forward to: siloing, resolving duplication data, debating formats, complex authorisation

---

## _Content-centric_ pattern emerges from the assumption:

> # Data is bound to location

You have to go to a place to read / write some data


???

What if it was different?

---

## Rumpelstiltskin & the magic of _True Names_

![](rumpelstiltskin.jpg)

- People : _public-private key cryptography_
- Objects : _hashing algorithms_

???

We don't need to be dependent on locations.

You might not know this but Rumpelstiltskin is a parable about key security.
By knowing Rumpelstiltskin's True Name, the princes has power over him (the contract they wrote together)

There's another common trope in fantasy writing about True Names, where if you know the True Name of a thing, you can call it to you.
Turns out this also exists (thanks cryptography!)

---

## I declare I'm applying for Superannuation

![](conversation_centric_0.jpg)

---

## WINZ is listening and responds

![](conversation_centric_1.jpg)

Note no filing cabinets, just a conversation with True Names

---

## .

![](conversation_centric_3.jpg)

---

## .

![](conversation_centric_4.jpg)

---

## .

![](conversation_centric_5.jpg)

---

