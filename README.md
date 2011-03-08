Internet Init: Human Browsing
=============================

Have an idea of which sites to trust
------------------------------------

If you've heard of it on the news, or is very well known, its probably safe.

You already know that the everyday sites such as [google.com](google.com), [amazon.com](amazon.com), and [nytimes.com](nytimes.com) are safe, and won't serve you content that will
compromise your computer. These are the tier one sites, the big names that would lose a lot of money if they turn malacious.

However, there's a lot more to the internet than these sites...

Almost never download or run an executable
------------------------------------------

In short, you should very rarely download, or run a file ending in `.exe`, `.msi` or `.bat`.

The only times where running executables is acceptable is when:

* You intend to install new software, such as itunes
* You know and trust the source of that software.

Basically, if you're looking to install new software, then you'll definitely have to run an executable. If you're trying to view an image or watch a video, you shouldn't be installing software.

Beware of easily exploited file formats
---------------------------------------

PDFs are a useful way to share read-only documents, but have a long and ugly history of security holes. This is not the most common technique used by internet evil, you're more likely to see this attack through email, because most email readers won't even allow executable file types through anymore.

The way the attacks work is internet evil can create a special document that breaks the reader software and ends up running some code on your machine. [Remember](untrusted-code) that running untrusted code on your machine is the foundation of all attacks.

Be extra careful when attempting to download music, or stream music or movies
-----------------------------------------------------------------------------

Google searches for phrases like "watch the simpsons" are big targets for _internet evil_ for several reasons. One is that there are legitimate sites that allow you to illegally stream TV shows and movies, but since they
are illegal, they usually don't last too long before the networks and movie studios find a way to take them down. Because they don't last long, they have no where near the polish of a legitimate site like [hulu.com](hulu.com).
Internet evil sites typically look amateur and crappy, and these video sites are usually amateur and crappy, so its a lot more difficult to separate the good from the bad. Internet evil exploits this weakness.

The other reason is that many users won't think twice about installing a program to be able to stream a movie, not realizing that this is almost never required.

### Technical

Most video streaming services use Flash. Flash is popular for games ([addictinggames.com](addictinggames.com)) and streaming video ([youtube.com](youtube.com)). Flash is the most commonly installed _browser plugin_, and is actually pretty terrible for streaming video, but the web's design didn't have a much better option until recently.

Since Flash sucks at playing streaming video, many companies have created similar softare that doesn't suck. [Netflix](netflix.com) chose to use Microsoft's "flash killer", named [Silverlight](http://www.silverlight.net/). Netflix is the most common, and frequently the only, legitimate reason to install software to watch videos (Windows does not come with Silverlight installed).

Use a modern, secure browser
----------------------------

Not all web browsers are created equal. [what's a browser?](browser-basics)

Modern, secure browsers are:

* [Google's Chrome](http://www.google.com/chrome)
* [Firefox](http://www.mozilla.com/en-US/firefox/)
* [The _latest_ Internet Explorer](http://www.microsoft.com/windows/internet-explorer/default.aspx)
* [Opera](http://www.opera.com/)

If you're the typical non-technical web user, Chrome is a great choice; its very fast, free, and safe.

Depending on which verion of Windows you're running, your default browser is probably an older version of Internet Explorer. Old versions have _many_ security vunlerabilities, and
do not work well on modern websites.
