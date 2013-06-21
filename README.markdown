# S5 Themes (Blue, I18N and Pixel) - Slide Show (S9) Template Pack

## What's Slide Show (S9)?

A Ruby gem that lets you create slide shows and author slides in plain text
using a wiki-style markup language that's easy-to-write and easy-to-read.
More [Slide Show (S9) Project Site »](http://slideshow-s9.github.io)


## Intro

The [S5 (Simple Standards-Based Slide Show System)](http://meyerweb.com/eric/tools/s5/)
templates bundled up into 
a Slide Show (S9) template pack including
three S5 themes, that is, Blue, I18N and Pixel.



Note, the S5 Themes package is configured to use the
following headers in `slides.html.erb`:

    theme: blue    # change as needed values include default|blue|i18n|pixel
    author: Your Name Here
    company: Your Company Here
    title: Your Slide Show Title Here
    subtitle: Your Subtitle Here
    footer: Your Footer Here
    subfooter: Your Subfooter Here

Use the `theme` header to choose your S5 theme. Packaged themes include
`default`, `blue`, `i18n` and `pixel`.
 
 
## Try It Yourself - How To Use the S5 Themes Template Pack

If you want to try it yourself, install (fetch) the new template pack. Issue the command:

    $ slideshow install s5themes

Or as an alternative clone the template pack using `git`. Issue the commands:

    $ cd ~/.slideshow/templates
    $ git clone git://github.com/slideshow-s9/slideshow-s5-themes.git

To check if the new template got installed, use the `list` command:

    $ slideshow list

Listing something like:

    Installed templates include:
       s5themes (~/.slideshow/templates/s5themes/s5themes.txt)

Tip: To get started use the welcome quick starter sample. Issue the command:

    $ slideshow new

Now you will have a copy of the `welcome.text` Quick Starter sample
in Markdown in your working folder.

```
%%%%%%%%%%%%%%%%%%
%% Some Headers

Title: Slide Show (S9) 10-Minute Tutorial


%%%%%%%%%%%%%%
%% Let's go.

# Slide Show (S9) 10-Minute Tutorial

Agenda

* What's Slide Show (S9)? 
* Wiki-Style Markup Language - Markdown, Textile
* How it works - Just press F11! 
* What's S5? What's S6?
* Gradient Themes Using "Loss-Free" Vector Graphics in S9 


# What's Slide Show (S9)?

### What? 

A Free Web Alternative to PowerPoint and KeyNote in Ruby


### Getting Started in 1-2-3 Easy Steps

* Step 1: Author your slides in plain text using a wiki-style markup language
* Step 2: Build your slide show using the `slideshow` gem
* Step 3: Open up your slide show in your browser and hit the space bar to flip through your slides
* That's it. Showtime!
```

Showtime! Let's use the `-t/--template` switch to build the
sample slide show. Example:

    $ slideshow build welcome.text -t s5themes

Open up the generated `welcome.html` page in your browser. Voila. That's it.

## Questions? Comments?

Questions? Comments?
Send them along to the [Free Web Slide Show Alternatives (S5, S6, S9, Slidy And Friends) Forum/Mailing List](http://groups.google.com/group/webslideshow).
Thanks!
