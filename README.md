# ztg.plus
ztg.plus is a hub for /ztg/-related web projects. It's run by Silverchase.

* Replacement for intro paste
* Archive of important thead texts
  * Anon's honest reviews
  * Zoosona guide
* Links and directory
  * Directory
    * `www` (this site)
    * `silverchase` (party club)
    * future things
  * Links
    * Imported from thread paste
    * TT blog
    * GTT archive
    * Party Club video archive

## Potential future subsites
* Replacement booru (probably expensive)
* Greentext archive (open-ended problem that may need custom work)
* In-house TT archive (fuck Tumblr)
* Hosting static web pages for web-based TT submissions
* Dedicated subsites for individuals or specific projects
* ?

## Attribution
Theme is based on "Friday Theme" by Simon Freytag. See `LICENSE.theme.md`.

# Tech notes
## TODO
* rework posts.html to be archives.html
* sidebar
* css

## TOC sidebar
Add sidebar to a page, with its headers as anchor links
* In `side.html`, include `project-meta.html` for those pages. This adds the sidebar elements.
* Copy the script from the bottom of `project.html` to the bottom of the relevant layout html file. This populates the sidebar with anchor links.
