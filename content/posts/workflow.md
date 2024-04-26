---
title: "My 2024 workflow"
date: 2024-03-06T22:49:41-05:00
draft: true
toc: false
images:
tags:
  - workflow, tools, shell 
---


# Intro

In this first 2024 blog post, I thought I would share my usual workflow for my development tools and needs


# Tools that I use

## Tools
First the tools I use everyday : 

- [Kitty](https://sw.kovidgoyal.net/kitty/)
- [Tmux](https://github.com/tmux/tmux)
- [Neovim](https://neovim.io/)

Those are the bread and butter for my every day work !

## Steps

As a developer I spend most of my time writing code, or at least I try to cause that's what I enjoy the most.

And to do to so here are the steps I go through :

- Open Kitty to get a new terminal
- Launch my custom `stm` command commuting me to where I need (pun intended with [stm](https://www.stm.info/en))

From there I have a small bash function that uses [fzf](https://github.com/junegunn/fzf/) to let me select the remote machine I want to connect to.

From there I get a list of tmux sessions that I can choose from depending on what I have to work on.

This works rather great for me !

You can have a look at my [dotfiles](https://github.com/victorfleury/dotfiles) and see how this is setup.
