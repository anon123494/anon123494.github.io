---
layout: post
title: A Barely Original Problem
date: '2024-04-13T12:53:00.000-07:00'
author: Banned In Iran
katex: true
---

# {{post.title}}

<p style="text-align: left;">Being able to write is good. I want to get better at it and quite obviously the best way to get better is to write! However my desire to get better at writing is strongly overshadowed by my reluctance to write useless things, the internet is already so full of meaningless crap (at best and harmful crap at worst), and I'd hate to be one adding to it.</p><p style="text-align: left;">The only avenues where I'm capable of writing non-trivial stuff in are math and computer science, but triviality is a matter of perspective and anything I'd be writing about would already be written about considerably better than me by people who consider it trivial. The only way past seems to be to write about the one problem that I managed to come up with and this post is about that problem , it's solution and further generalizations of it</p><h2 style="text-align: left;">Next / Previous Video</h2><p style="text-align: left;">You're probably familiar with the next/previous function of a video players which opens the appropriate video file (most of the time alphabetically) coming after/before the current video. you may also be familiar with the <b>Recent </b>section that is shown when you right click on the video player in the taskbar listing around the 10 most recent files that have been opened by the video player
</p> 


![example of some recent files](/assets/img/Recent.jpg)


looking at this one day I got curious about how many possible permutations (or orderings) these files could get if you could only use the next or previous video function

## Formalizing the problem
imagine you have a folder with  $n$ video files numbered from $1$ to $n$
and a video player with the file number $1$.along with the folder we have a list of recently opened file ordered initially from $1$ to $n$ (here we consider all the files not just the 10 or so most recent) if the current opened file is numbered $i$ then you can open the next video: $i+1$ (if you aren't at video $n$) or you can open the previous video: $i-1$ (if you aren't at video $1$).

upon opening any file $i$ it goes to the top of the recent list and any video between it and the top gets shifted down. 

what are the number of distinct orderings the recent list can take by using an arbitrary (but obviously finite) number of steps (going to the previous or next file is one step)? [^1]

### Example
let $n = 3$. at step one we can only go from video $1$ (which is initially opened) to video $2$  which would transform the recent list to $(2,1,3)$
if we then go to video $3$ we get the list $(3,2,1)$ and further returning $2$ (you can't get from $3$ to $1$) would give us the list $(2,3,1)$.

all of the three orderings above in addition to the initial $(1,2,3)$ ordering which is possible in $0$ steps! are distinct possible orderings and it just so happens that they are the only possible orderings (will be proven later). so the answer to the problem with $n=3$ is $4$






[^1]: there are other possible formalizations but this one suffices (and we will use more general forms laters)