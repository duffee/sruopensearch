# NOTICE from IRISS #
This project is no longer maintained by IRISS as we have moved to a newer open source based system, if you would like any help/details with what we built (in drupal) please get in touch the new Learning Exchange is http://lx.iriss.org.uk

Some of the users have picked up the code and are occasionally hacking it for our own needs.

# SRU Open Search #

This project aims to provide a customisable search interface for displaying [SRU](http://www.loc.gov/standards/sru/) formatted XML.

This initial release targets [Intralibrary](http://www.intrallect.com/index.php/intrallect/products) version 2.9, although with a little tweaking it should work with any SRU stream.

If you'd like to discuss any issues or problems please drop by the [intraLibrary users discussion area (Spanish/bilingual)](http://groups.google.com/group/intralibrary), we cant guarantee a reply but we'll do our best to help out.

**We'd also like to hear any ideas you might have to improve the service.**  Checkout the [wishlist](http://groups.google.com/group/sru-open-search/browse_thread/thread/803d35ed1a35bc22/58b862867a178cac#58b862867a178cac) discussion.

http://groups.google.com/group/sru-open-search


---


## Features ##
  * Highly configurable via settings files
  * Customisable look & feel (CSS)
  * XHTML 1.0 Strict doctype
  * Search on record metadata with a single click
  * Send to friend & Notify of a problem functions
  * Bookmarkable pages, so you can share a page of results via email
  * Share items via social bookmarking sites ([Delicious](http://del.icio.us/), [Digg](http://digg.com), [Google](http://www.google.com/bookmarks/))
  * Featured audio highlighting - inline mp3 player via flash
  * Featured content highlighting
  * New & Updated content highlighting
  * Logging of Email sent through system with [Akismet](http://akismet.com/) spam protection
  * Logging of search terms
  * Visualisation of search terms via pie chart, tag cloud & tree map
  * Progressive enhancement via javascript [(jquery)](http://jquery.com/)
  * Spell Checker (via [local service](http://www.aspell.net) or [3rd party](http://developer.yahoo.com/search/web/V1/spellingSuggestion.html))
  * Auto suggest search box
  * Portable version of search so users can add to their own site
  * Browser search plugin for Firefox & Internet Explorer (inc Auto Suggest)
  * Intelligent caching of SRU results
  * Non-intrusive debugging via firefox/firebug
  * Google Analytics support

## System Requirements ##
### Essential ###
  * PHP (min 5.1.6)
### Optional ###
  * MySQL (min 5.0.18) - Only required for logging functionality
  * Apache webserver (optional although you may need to configure your own hosting platform to support mod\_rewrite type functionality)
  * Perl (for local spelling suggestion)
  * Aspell & Aspell perl wrapper(for local spelling suggestion)

#### Notes ####
This was developed, tested & deployed on a Linux Apache web server.  In theory any platform capable of running PHP & MySQL should work.

---

## Produced & maintained by ##
[![](http://www.iriss.ac.uk/themes/SIESWE1/images/logo-iriss.png)](http://www.iriss.ac.uk/)