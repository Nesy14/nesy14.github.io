---
layout: single
title: THIS A TEST
date: 2018-11-18
classes: wide
header:
  teaser: /assets/images/slae32.png
categories:
  - prueba
  - infosec
tags:
  - prueba
  - assembly
  - tcp bind shellcode
---
PRUEBA A bind shellcode listens on a socket, waiting for a connection to be made to the server then executes arbitrary code, typically spawning shell for the connecting user. This post demonstrates a simple TCP bind shellcode that executes a shell.
