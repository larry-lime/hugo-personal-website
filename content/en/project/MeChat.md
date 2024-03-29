---
title: "MeChat - Python GUI Desktop Chat App"
date: 2022-08-27
draft: false
ShowToc: true
ShowBreadCrumbs: true
ShowCodeCopyButtons: true
author: ["Lawrence Lim", "Vicky Liu"]
---

## About The Project

{{< youtube id="mXwYOLjKYxg" title="Demo Video" >}}
[Presentation Slides](https://docs.google.com/presentation/d/1VYCY3Z98NmaQVLRU85uHsY7zH3i7-3MLiox6nEphETY/edit#slide=id.g10e271dcd0d_1_401) 

MeChat [(GH Repo)](https://github.com/larry-lime/MeChat) Up is a Python GUI desktop chat app built with Tkinter. This app was also created as the final project for NYU Shanghai's Introduction to Computer Science course. Here we will detail several of its key features and outline its development lifecycle.

### Built With

Our chat application used the following languages and libraries in our development.

* Python
* Tkinter GUI Library
* Ngrok Network Application

## Getting Started

### Prerequisites

This project depends on the python tkinter GUI library and ngrok network app.

* [ngrok](https://ngrok.com/download)
* tkinter
  ```shell
  pip install tkinter
  ```

### Installation

1. Clone the repo
```shell
git clone https://github.com/larry-lime/MeChat
```

## Usage

* Start and run your own chat server
  ```shell
  python3 chat_server.py
  ```
* Start and connect a chat client
  ```shell
  python3 chat_cmdl_client.py
  ```
