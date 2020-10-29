# Cookie Manager

- IE11 compatible
- Four different blocking methods
- Multilingual
- Mobile ready

Currently it can block all the bad cookie monsters in 4 ways.

### Dynamic script tags

Some services insert dynamically created script tags to the HEAD at page load. These can be intercepted and blocked.

### Script tag blocking

Some third party services require you to insert a script tag into your HTML pages. These can be inactivated until the user allowes them.

### Script wrapping

Some services are not inserted in a SCRIPT tag and are obscured by layers of other code. Thats why this script creates a global wrapper function what you can use to wrap and blovk any JS code.

### Local cookies

Finally the local cookies set on your domain can be also filtered by overriding the bowsers COOKIE SET method.
