# TODO

This is the list of tasks that need to be figured out before we can switch from
Drupal to Jekyll for the project.


* *Community Ratings*

    Currently under the `/rate/` path in the tree, runs some simple PHP stuff

* *Changelog*

    Dynamically generated on the main web host, we could probably just have the
    template generation code read the files in directly.

* Pages and stories are mixed up

    Pages (such as mailing lists) are converted as posts, so while redirections
    are in place, their eventual URL is pretty ugly. This should be fixed.

* Author info is lost

* Every post is getting `.html` extension

    See http://blog.jvc26.org/2011/09/13/clean-urls-in-jekyll for a relevant info
