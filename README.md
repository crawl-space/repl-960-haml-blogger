A Blogger Prototype Template in HAML and SASS
=============================================

This is the template I use for http://blog.repl.ca
It uses:
 * compass
 * 960.gs
 * SASS
 * HAML
 * Viewers Like You

template.haml is a pretty bare haml formatted blogger template; just enough to
have a single sidebar and blog content. sass/layout.scss is where you'd put
your own stylings.

To compile the template, run rake. This will create a template.html file.
Upload this to blogger by navigating to Template -> Backup/Restore under your
blog's admin page.

Note: My widget orders seem to flip-flop around whenever I upload a new
template version. Keep this in mind, and make sure to reorder after you update.
