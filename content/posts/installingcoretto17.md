---
title: "How to install Coretto JRE 17"
date: 2022-02-15
tags: ["java", "jre"]
---

## What is Amazon Coretto?

Amazon Coretto is a Java runtime environment that is used to run Java applications. It's built on top of OpenJDK and is available for both Linux and Windows for free. Corretto is Open source, you can get it from [here](https://github.com/corretto).

## How to install Coretto JRE 17 on Debian-based Linux

First you need to add the repository to your system:

```bash
wget -O- https://apt.corretto.aws/corretto.key | sudo apt-key add -
sudo add-apt-repository 'deb https://apt.corretto.aws stable main'
```

Then you just need to update the package list and install the Coretto:

```bash
sudo apt-get update && sudo apt-get install -y java-17-amazon-corretto-jdk
```

Now you can run the following command to check if the installation was successful:

```bash
java -version
```

If you see something like this:

```bash
openjdk version "17;" 2021-09-14 LTS
OpenJDK Runtime Environment Corretto-17;.0.0.35.1 (build 17;+35-LTS)
OpenJDK 64-Bit Server VM Corretto-17;.0.0.35.1 (build 17;+35-LTS, mixed mode, sharing)
```

Then you are good to go!

## How to install Coretto JRE 17 on Windows

To install Coretto JRE 17 on Windows you need to download the installer and run it. You can find the installer [here](https://docs.aws.amazon.com/corretto/latest/corretto-17-ug/downloads-list.html).

## Full Documentation

For the full documentation you can visit [here](https://docs.aws.amazon.com/corretto/latest/corretto-17-ug/).
