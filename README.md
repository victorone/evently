# Evently
## Making your jQuery apps DRYer since 2010

There is extensive documentation about [Evently on the CouchApp wiki.](http://couchapp.org/page/evently)

There is [a screencast here.](http://www.youtube.com/watch?v=Xk5gaUURdJI)

## This Version

This version is currently maintained by David Bergman, of Victor1 LLC, and adds some features to the original Evently, such as:

* one can map events to *distinct* target events when `connect`:ing events of two elements
* the actual object is passed to the event handler for `_changes`; this is crucial so no extra access is needed; whether to pass the document or not is decided via regular CouchApp ways
* it works with CoffeeApp, i.e., you can code the widget events in CoffeeScript, with some caveats. See current issues.

## License & Copyright

Apache 2.0 License

Copyright Chris Anderson 2010