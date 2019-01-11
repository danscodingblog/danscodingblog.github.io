---
layout: post
title: "Python: The best scripting language"
date: 2019-01-10
---

Python is my favorite scripting language. I use it for almost all of my high-level programming. The only time I don't use it is when I need bits of code to run ultra-fast, then I'll use java.

Python is great for all sorts of tasks. You can make simple command line utilities with no trouble at all. You can use the variety of web frameworks that python offers to build websites. You can make GUI applications with tk inter.

For the most part, I use python to build websites. My favorite technology stack is tornado with nginx, using supervisor to manage the tornado processes. Tornado is an event-loop driven framework designed by facebook to solve the 10k current connections problem. By keeping the same process alive and using callbacks for IO, tornado runs very efficiently. I used to mostly use apache, with mod_python, but had trouble scaling up my web applications. Once I switched to nginx and tornado, it was easy!

Python is a great language for scraping. You can use a library called BeautifulSoup to parse html files. It's really easy!

The guiding principle of python is that, there should be one clear and obvious way to do everything. Compare this to ruby, which aims to be expressive and let the programmer write code however they want. Ruby allows for some very "beautiful" code, but it can be hard to read depending on who wrote it! With python you're much more likely to be able to read other people's code easily.

If you're interested in learning python, I recommend checking out https://www.python.org/about/gettingstarted/. Remember, it's always best to have a project you're working on in order to learn a language! I recommend building a simple web app with tornado. Try making a rock paper scissors game that two players can play!

That's all I've got for you today, stay tuned for more!

![Coding in python is fun!](/assets/ai-artificial-intelligence-blur-546819.jpg){:class="img-responsive"}
