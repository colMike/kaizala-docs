---
title: Connectors
description: Article for providing overview of Kaizala connectors
topic: Overview
author: nitinjms
---
# Connectors

## Overview
Kaizala Connectors enable 3rd party developers to integrate Kaizala into their business processes by providing the ability to perform a curated set of actions in Kaizala 
using REST based API calls. The scope of the API is for external systems to call the end-point and perform actions on-demand. That is, this will be a PULL model – where 
individual endpoints need to be called to perform specific actions using Kaizala **[APIs](API.md)**. The PUSH model where Kaizala platform can trigger actions can be configured using **[webhooks](webHooks.md)**.

Kaizala Connectors are currently group-scoped - i.e. each Kaizala Connector needs to explicitly be granted permissions to a Conversation group - and then can perform actions through the API end-points only within the context of the group. However, each Kaizala Connector can be granted access to multiple groups.

* [Setup for using the Kaizala Connectors](setup.md)
* [API Documentation](API.md)
* [Read more about Connectors](https://support.office.com/en-US/article/Kaizala-Connectors-223791c8-718d-4669-8c5e-a76804ae1ddd)
