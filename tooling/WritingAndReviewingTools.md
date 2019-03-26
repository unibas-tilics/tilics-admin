# Writing and reviewing tools

To enhance the quality of the articles we need a toolstack which supports the writers and reviewers with an intuitive and easy to use work flow (easy to use for computer scientists). 

In this document we discuss and compare different systems and approaches.



## Requirements

The selected tool or approach has to fulfill the following requirements:

* Versioning of articles 
* Discussion / comments
* Reviewing process
* Labels
* Markdown support
* Support for images
* Support for publishing the articles




## Possible tools or approaches

This section introduces and compares the tools.



### MediaWiki
A well-known wiki system which is also used for Wikipedia.

Advantages:

* Each page has a discussion page
* Versioning
* free to use (GPLv2+)
* File management and support for images


Disadvantages:

* Needs to be setup on a web server
* Independent of the git repository
* Adding a point of failure
* Difficult to modify the design 
* Does not support Markdown



### DokuWiki

Like MediaWiki but more lightweight and easier to setup and maintain. 

The DMI has a instance of DokuWiki running which we might able to use. Due to the fact that this wiki is only reachable from within the internal network makes it unsuitable as solution for publishing the articles.

Advantages:

* Each page has a discussion page
* Versioning
* free to use (GPL2)
* File management and support for images


Disadvantages:

* Needs to be setup on a web server
* Independent of the git repository
* Adding a point of failure
* Does not support Markdown



### GitHub Wiki

Every GitHub repository comes with a simple wiki system. 

Advantages:

* Nothing to setup
* Free to use 
* Support for Markdown
* File management and support for images
* No additional point of failure


Disadvantages:

* No reviewing options
* No commenting options



### GitHub & Pull-Requests

Instead of using a dedicated tool we fully relay GitHub.

Advantages:

* Nothing to setup
* Free to use 
* Support for Markdown
* File management and support for images
* No additional point of failure
* GitHub Pages for publishing 
* CI Pipelines are possible (Hemingway)


Disadvantages:

* Steep learning curve
* No integrated support for labeling




## Conclusion

The tooling group recommends the *GitHub & Pull-Requests* approach. We already have different ideas how to implement the missing support for labeling.


