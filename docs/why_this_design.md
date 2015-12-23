# Why This Design?

*Or...*

**The really, REALLY long-form tutorial**

## Introduction

Most technical documentation explains the "what" or "how" of a
piece of software; this document dives a level deeper to explain
the *why* of Django++'s design.

## Chapter 1: Requests and Responses

Fundamentally, a web service does two things:

1. Receives a request from a client
2. Sends a response back to the client
 
Exactly *what* the web service should do with each request is
determined by the *URL pattern* to which the request is *routed*
by the client.

(E.g., sending the same HTTP request to both `/foo/` and `/bar/`
at `www.foobar.com` could potentially yield two different HTTP
responses)

As such, the core of any application or service written in Django++
is the *routing table*:

**[TODO: Add sample routing table here once "Hello World" demo app is
complete]**
