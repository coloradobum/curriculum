
## Working with a Rails Back End and API

It's finally time to tie all this juicy Javascript back to what you learned in Rails.  In preparation, reread the [Rails lesson on building an API](/courses/ruby-on-rails/lessons/apis-and-building-your-own) to refresh how to set up a Rails backend that can handle JSON requests.

At this point, you've got all the tools you need, so it's time to practice allowing your front end Javascript to talk to your Rails backend using AJAX.  We'll cover some best practices for how to pass data from one to another, but otherwise it's just putting together those final pieces of the web development puzzle.

### Points to Ponder

* Refresher -- how do you set up a basic Rails app?
* Refresher -- how to you load custom Javascript in a given Rails view page?
* How does "unobtrusive Javascript" work?
* How can you pass data from your Rails app to your Javascript?
* Why would you want to use AJAX to load large batches of data 

### Links

* [Check out "Using Javascript in your Rails App" from Daniel Kehoe](http://railsapps.github.io/rails-javascript-include-external.html).  It is long and covers a lot of ground, but it's got great content.  Some of the stuff on dependencies can be skimmed, but pay attention to the `content_for` stuff at the bottom.
* [Refresh yourself on Rails AJAX from RailsGuides](http://edgeguides.rubyonrails.org/working_with_javascript_in_rails.html) (just skim the top few sections)
*[Bootstrapping JSON data into a Rails View](http://jfire.io/blog/2012/04/30/how-to-securely-bootstrap-json-in-a-rails-view)

### Additional Resources

* [Grabbing your Rails form CSRF token with Javascript so Rails doesn't yell at you with "Warning, can't verify CSRF token authenticity", via SO](http://stackoverflow.com/questions/7203304/warning-cant-verify-csrf-token-authenticity-rails)
* [... and another SO post on the CSRF token](http://stackoverflow.com/questions/8503447/rails-how-to-add-csrf-protection-to-forms-created-in-javascript)