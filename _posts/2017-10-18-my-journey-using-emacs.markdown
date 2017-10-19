---
layout: post
title: "My Journey Using Emacs"
date: 2017-10-18 9:23:00 -0700
categories: Tech-Stories
author: David Madrigal-Hernandez
---
This is a story of my history, and current affair, with Emacs.

## Beginnings 

Emacs for me, at least at first, was one of the scariest editors in the room. It wasn't exactly pretty, and though it has many features that I now come to appreciate (dired and compilation capabilities come to mind), I still feared the learning curve. It was a daunting to look at the keyboard shortcuts, and I felt VERY incapable of using Emacs. The ironic thing though is that I was and still considerably do, use Vim as my text-editor; considering the  even more arcane keyboard shortcuts that Vim uses, and the fact that I could not even learn the comands no matter what I did (though I did eventually manage to escape it ;)), I decided to start looking at different options.

## The Search

When I decided to start looking for a different editor, I asked myself, "Hmm, what exactly do I want in an editor?" I came up with a list that ultimately looked like this:`
1. The editor has to load quickly
2. Has to be simple to use, but VERY customizable
3. Any keyboard shortcuts have to be quick to learn.

This is invariably a pretty demanding list, but I was determined to finde and editor that just clicked. Now, that isn't to say I hadn't already tried other options. I was already trying out the likes of **[Atom](https://atom.io "Atom Text Editor")**, **[Sublime 3](htps://www.sublimetext.com/3 "Sublime Text 3 Text Editor")**, and even **[Visual Studio Code](https://code.visualstudio.com "Visual Studio Code Text Editor")**. All of these editors are pretty speedy, have amazing keyboard shortcuts, and are customizable in their own right. And yet, something felt off. I wasn't sure what it was, but I had always felt that the more I used any of them, ,the slower they got. They would load a couple of milliseconds more each time I opened them, the plugins I used for them also seemed sluggish overall. Now, two of those are build on the **[Electron](https://electron.atom.io "Electron Framework")** framework, which is understandably why it was slow. However, for Sublime to become slow was surprising, seeing its reputation. Regardless, I moved on.

I then looked at [Neovim](https://neovim.io "Neovim Text Editor"), I looked at simpler text editors like nano, and Geany and the like. I had looked at Emacs when, in the end, I just didn't like any of the choices. They all had one thing or another that I just did not like. Wether it be the interface, or opening, or the keybindings, I just don't know. Regardless, I decided to try it out, see how it would go.

## Early Days

The first few days of using Emacs was definitely a struggle. I did go through the tutorial (albeit not all the way), and I liked how strightforward alot of the commands were. That isn't top say that they are archaic, quite the opposite actually. But, they do have the philosophy of nerver moving you hands away from the central keyboard position, which is pretty nice. The load times on Linux in a VM are really nice, its snappy, and on Windows builds its quite the same snappiness, surprisingly. And this was just the tip of the iceberg, because little did I know that I would come to love the simplicity of Emacs more and more. 

## Dicsovery

I started to use Emacs as more of a playground soon after deciding to pick it up, testing different commands, editing junk files, among other things. I was also reading up on a lot of the capabilities of Emacs. I found out about its themeing capabilities, it's straightforward approach tp setting up the editor just the way you like it. 

My favorite thing came to be Emacs approach to cusomization. Now, there are two ways tocusomize this program: you can edit the .emacs file directly, or you can go through the menus. The first option, while allowing for the most fine-tweaking, does necessitate you to learn elisp, a variation of the 
[Lisp](https://en.wikipedia.org/wiki/Lisp_(programming_language) "Lisp (Programming Language)") langauge for Emacs. The second option is more suited for either quick changes, or for new users, and involves goring through a defined set of menus to alter pretty much ANYTHING on the editor. The Way to do this is to enter the command: `M-x customize RET`. The `M` here represents Meta, or the Alt key traditionally, in Emacs. Once you hit enter, you can go through the entire menu and explore the various settings of the editor. And all the settings are saved to the aforementioned .emacs file, so there is no need to actually edit it. 

One of the biggest things I have found though, is the ability to install community built packages. This is done through the package system that is built into Emacs by default, and is an AMAZING resources. This is where the editor TRULY shines; if you ever need anything to help your workflow, chances are there is a package for it in Emacs. And while the default package repository is good (yes, it already has a list of available packages by default), you can add other repositories like the popular MELPA repository with a couple of lines in the .emacs file, or with a few seconds of navigating the settings menus. Once you intialy laod the recent packages list (the command for those interested is `M-x list-packages`), you can browse at you leisure for whatever you need/ This is anything from editor themes, to full blown window managers and maybe even operating-systems. Ok, that last one might be a little much, but you get the idea (I hope).

## Summary

All in all, what started as a fear of one of the oldest text-editors around, became what is a love affair that I am sure will last a really long time. And while yes, Emacs does have its flaws (which honestly would be pretty interesting to talk about in a seperate post), I ultimately think that the benefits outwhiegh those costs. It is amazing that what I once thought was a monster of an editor was really something powerful and competely maleable. It really reminded me of a saying that I should have considered from the get-go: *never judge a book by its cover*. I will update what I dicsover as I explore more of this beautiful editor, and will try to document it the best I can as I go along. Wish me luck, everyone, and I really hope to hear from you all soon.
