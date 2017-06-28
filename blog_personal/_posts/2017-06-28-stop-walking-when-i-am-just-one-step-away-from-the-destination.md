---
layout: post
title: Stop Walking when I am just One Step away from the Destination
date: 2017-06-28 21:09:00 +0800
---

I struggled in writing a wait-free (and so lock-free) single-producer single-consumer queue with a linked list. An idea came out when I was struggling: I can use a useless element to seperate the producer and the consumer. However, again, I thought that it was so troublesome and so stop following this line of thought. After a day, I came up with the same idea again and noticed that this is a correct and simple solution. A day wasted. Sigh...

