---
layout: project
type: project
image: images/huffman.png
title: Huffman Encoding
permalink: projects/huffman
# All dates must be YYYY-MM-DD format!
date: 2014-04-12
labels:
  - Java
  - Compression
summary: A program that applies Huffman encoding to a text file as a lossless data compression algorithm.
---

<img class="centered" src="../images/huffman2.png">

Huffman coding is a lossless data compression algorithm. The idea is to assign codes to input characters. The most commonplace characters gets the smallest code and the least frequent character gets the biggest code. The length of the codes are based on the frequencies of  the characters.

There are two major parts in this project. One is being able to build a tree of characters that are the input. Then you have to traverse the tree and assign corresponding codes to those characters. 

What I learned was mainly how nodes work and tree traversal. I also got a very basic understanding of how compression works. I was so fascinated by the fact that something so simple could be so effective and started to wonder what the upper limits of compressions algorithims were and if there are diminishing returns. 



Source: <a href="https://github.com/vialliou/huffman"><i class="large github icon "></i>vialliou/huffman</a>

