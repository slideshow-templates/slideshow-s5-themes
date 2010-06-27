## Slide Show (S9) Template Pack - S5 Themes (Blue, I18N and Pixel)

The [S5 (Simple Standards-Based Slide Show System)](http://meyerweb.com/eric/tools/s5/)
templates bundled up into 
a Slide Show (S9) template pack including three S5 themes, that is, Blue, I18N and Pixel.

Note, the package is configured to use the following headers in `slides.html.erb`:

    theme: blue    # change as needed values include default|blue|i18n|pixel
    author: Your Name Here
    company: Your Company Here
    title: Your Slide Show Title Here
    subtitle: Your Subtitle Here
    footer: Your Footer Here
    subfooter: Your Subfooter Here

Use the `theme` header to choose your S5 theme. Packaged themes include
`default`, `blue`, `i18n` and `pixel`.

See the original [S5: An Introduction](http://meyerweb.com/eric/tools/s5/s5-intro.html) slides in action or
see the [Slide Show (S9) Tutorial (Blue Theme)](http://slideshow.rubyforge.org/s5/tutorial.blue.html),
[(I18N Theme)](http://slideshow.rubyforge.org/s5/tutorial.i18n.html),
[(Pixel Theme)](http://slideshow.rubyforge.org/s5/tutorial.pixel.html) 
slides generated using this template pack.
 
 
## Try It Yourself - How To Use the Template Pack

If you want to try it yourself, install (fetch) the new template pack. Issue the command:

    $ slideshow -f http://github.com/geraldb/slideshow-s5-themes/raw/master/s5themes.txt

To check if the new template got installed, use the `-l/--list` switch/command:

    $ slideshow -l

Listing something like:

    Installed templates include:
       s5themes.txt (/home/gerald/.slideshow/templates/s5themes/s5themes.txt)

Now you're ready to use it using the `-t/--template` switch. Example:

    $ slideshow -t s5themes.txt tutorial

That's it. 



## Troubleshooting 

Trouble downloading? Do you have a direct internet connection? If not, configure your proxy using
the `HTTP_PROXY` environment variable. Sample:

    HTTP_PROXY=http://234.445.454:4341

Or with user credentials (that is, login and password):

    HTTP_PROXY=http://gerald:topsecret@234.445.454:4341

If all fails, you can always download the template pack on your own (using lets say `git` itself)
and than move the souces into your templates folder (that is, `~/.slideshow/templates`).


## Questions? Comments?

Questions? Comments? Send them along to the [Free Web Slide Show Alternatives (S5, S6, S9, Slidy And Friends) Forum/Mailing List](http://groups.google.com/group/webslideshow).
Thanks!

## Appendix: Sample Slide Show Source in Markdown 

    theme: blue
    author: Your Name Here
    company: Your Company Here
    title: Your Slide Show Title Here
    subtitle: Your Subtitle Here
    footer: Your Footer Here
    subfooter: Your Subfooter Here
    
    
    Slide Title Here
    ================
    
    - Point One Here
    - Point Two Here
    
    Another Slide Title Here
    ========================
    
    Questions? Comments?
    
    Send them along to the
    [Free Web Slide Show Alternatives (S5, S6, S9 And Friends) Forum/Mailing List](http://groups.google.com/group/webslideshow)
    Thanks!
