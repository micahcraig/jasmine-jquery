# History

This is an overview and may be incomplete. https://github.com/velesin/jasmine-jquery/commits/master is where to see everything.

## v1.5.9 (Sept 25, 2013)
  - fix throw error when loading a fixture that doesn't exist (#146)
  - fix toHaveCss() to support expecting a css property be auto (#147)
  - fix toExist() for objects outside of the DOM (#64, #148)

## v1.5.1 (April 26, 2013)
  - adds matcher for jQuery's event.stopPropagation()
  - adds toHaveLength matcher
  - adds toContainText matcher
  - adds toHaveBeenTriggeredOnAndWith
  - stop toHaveValue from coercing types
  - fix ajax call that was breaking JSONFixture
  - fix loadStyleFixtures in IE8
  - makes toBeFocused compatible with PhantomJS
  - updates jQuery to 1.9
  - performance improvements
  - other minor fixes
