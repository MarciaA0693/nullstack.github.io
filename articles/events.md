TODO:
- events are called like normal html attributes
- events receive a function reference
- the function receives the context
- the context has a copy of the event
- the default behaviour is prevented by default
- the default behaviour can be kept with default=true
- the event receives props from the target as context arguments
- events can be an object as shortcut
- object events have an implicit source
- object events can declare a source
- object events can be used alongside bind