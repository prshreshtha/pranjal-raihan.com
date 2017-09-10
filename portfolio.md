---
layout: portfolio
title: "Portfolio"
permalink: /portfolio/
---

I have worked on many personal projects over the years. I've learned a lot from experimentation and some of my ideas actually became complete libraries and applications!

### Smartdirect

* A smart URL-shortener written with Ruby on Rails and Ember.js

* Source code at [smartdirecct-backend](https://github.com/prshreshtha/smartdirect-backend) and [smartdirect-web](https://github.com/prshreshtha/smartdirect-web)

* See the READMEs for details
  * [Backend](https://github.com/prshreshtha/smartdirect-backend/blob/master/README.md)
  * [Frontend](https://github.com/prshreshtha/smartdirect-web/blob/master/README.md)

![Demo](https://i.imgur.com/zXVNRFB.gif)

***

### Texart

* An ASCII art generator from images.

* Written in idiomatic C# (works on Windows/OS X)

* Scripting possible in C# through Rosyln API (WIP)

* Source code at [https://github.com/prshreshtha/Texart](https://github.com/prshreshtha/Texart)

![Demo](https://i.imgur.com/qWim2IA.gif)

***

### Slotty

* A (Very) Tiny Library for Event (Signal-Slot)-Driven Models in C++14

* Header-only, idiomatic C++14 with template metaprogramming

* Policy-based implementation.

* Source code at [https://github.com/prshreshtha/slotty](https://github.com/prshreshtha/slotty)

***

### Redpill

* A tiny webapp that solves systems of linear equations

* You type in the variables in the "command window" and hit generate to get the matrix (it will accept two variables with the same name so watch out!)

* You type LaTeX expressions. For example: in `pi/4` will render `π` over `4` (fraction) and a decimal representation. Hit "Solve" to find a solution

* BEWARE! This is very barebones. It helped me with my homework but I pursued it no further

* You can see it live at [https://redpill.pranjal-raihan.com/](https://redpill.pranjal-raihan.com/)

* Source code at [https://github.com/prshreshtha/redpill](https://github.com/prshreshtha/redpill)

***

### jevent

* Simple, modular, extendable events in Java

* The `Event` interface may only be used to add or remove listeners. An `Event`'s interface does not expose any `raise` method

* There are two implementations provided for `Event`.
  * `PublicEvent` – Anyone case `.raise` this event.
  * `PrivilegedEvent` – `.raise` is protected by a precidate provided at construction

* Very old project from high school I used in a game

* Source code at: [https://github.com/prshreshtha/jevents](https://github.com/prshreshtha/jevents)

***

### jconfig

* Configuration manager for Java (useful for application/game configuration)

* Interface allows all JVM primitives + String + BigInteger + BigDecimal

* Uses Ant as a build tool

* Uses `jevent` for event handling on add/remove/update

* Very old project from high school I used in a game

{% highlight java %}
  ConfigManager manager = new JSONConfigManager(); // or XMLConfigManager
  Config config = manager.newConfig();
  config.putString("sample_key", "it works!");
  config.flushState();
        
  System.out.println("\n" + config.toCanonical() + "\n"); // { "sample_key": "it works!" }
{% endhighlight %}

* Source code at: [https://github.com/prshreshtha/jconfig](https://github.com/prshreshtha/jconfig)

***

### Colonel By Library Website

* A website for my high school library created by my friend and I: [http://colonelby.com/teachers/library/](http://colonelby.com/teachers/library/)

* Made to be maintained by <small>(mostly)</small> non-technical people

* Source code at [https://github.com/prshreshtha/cblib.site](https://github.com/prshreshtha/cblib.site)