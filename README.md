Gobble
======

Gobbles up media from all around the internet.

At heart, it's similar to [youtube-dl](https://github.com/rg3/youtube-dl), with a few key differences:

* **It's aimed at developers, not end users.**
  
  If you just want to download some Youtube videos to your desktop, you want youtube-dl.
  
  If you want programmatic access to media at a given URL, and you don't want to care about what service it's hosted on, and you'd rather not invoke youtube-dl (with its rather hefty startup time and RAM cost) in a subprocess for every request, Gobble just may be what you want.
  
* **It tries to use official APIs wherever possible.**
  
  This means you have to provide API keys for a few key services.
  
  It also takes a good chunk of overhead out of the program, by not having to scrape HTML and keep up with changes.
  
  It also means better performance, by saving on both bandwidth and processing time.
