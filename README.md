# Project-AnuPIs4848
A Project for building DIY audio interface like MergingAnubis/NeumannMT48

## Introduction

Just like the title, this project is for building a DIY audio interface like MergingAnubis/NeumannMT48.

The main purpose is to build a audio interface for my own need, without software limits from  manufacturer.

I have a lot of ideas about this project, but I don't know if I can finish it. So this project is just for fun.You can use for reference, but I won't provide any support.

This project contains some reverse engineering work about Ravenna protocol, but I won't provide any document about it since I don't know if it's allowed.

## Background

I just bought a Neumann MT48, It's build with high quality, but the software is very limited:

* EQ is limited to 4 bands
* Not support surround sound (yet, but they promise to support in someday of the future).
* USB only support UAC in IOS/MAC, need install driver in Windows, and not support Linux/Android at all.
* You can't add any additional effects since it's firmware is closed source.

I like AoIP, it can make you audio interface a lot more flexible. But at current, any AoIP standard, even AES67, is claimed to be a open standard but need to pay (a lot) to get the standard document.

But hey, I just got a Neumann MT48, it's a Ravenna audio interface. Capture the network packets and reverse engineer is not a hard work. So I decided to build a DIY audio interface based on the reverse engineering on RAVENNA protocol.

So This is it. I will build a DIY audio interface based on RAVENNA protocol, and I will try to make it as good as possible.

