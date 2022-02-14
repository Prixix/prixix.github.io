---
title: What is Dastebin?
date: 2022-02-14
tags: ["nodejs", "javascript"]
---

## Description

[Dastebin](https://dastebin.prixix.com) is a service that allows you to paste code snippets in a simple and
easy way. This is done by using the IPFS network, that will allow you to store your code snippets in a decentralized way.

## Features

- [x] Share your code snippets with others
- [x] Get your code snippets back
- [x] Show your code snippets raw

## Using the Rest API

You can post a code snippet with the following command:

```bash
curl -X POST -H "Content-Type: application/json" -d '{"code": "console.log(\"Hello World!\")"}' https://dastebin.prixix.com/new
```

## What is IPFS?

IPFS is a peer-to-peer hypermedia protocol that enables the sharing of content in the Internet. It is a protocol that allows you to store and retrieve data in a decentralized way.

## Get the source

Source code can be found [here](https://github.com/Prixix/DasteBin).
