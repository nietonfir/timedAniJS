# TODOs

* [ ] `suppressTriggers()` on Object and Composition
(and a reenable function of course)
* [ ] every `start()`, `trigger()`, `on()`, `off()`, `wait()` function should be able to take array of events, especially `startAndWaitFor()`
* [ ] we need a `stop()` function for animations or at least a `requestCancel(callback)`
* [ ] add more Animation objects for GSAP, tween.js, etc.
* [ ] split code up in modules
* [ ] implemented build step to minify
* [ ] objects registered to a composition should be targetable by composition/object:in - keep in mind this means they need to trigger the right stuff too once complete
* [ ] `Composition.unregister()`
* [ ] `Object.destroy()`
* [ ] events should send info on what event it is. kind of like `onRegex` does
* [ ] create a describer for animations much like `TATimelineDescriber` to allow something like `d.delay(500, d.repeat(5, d.chain([d.velocity(), d.velocity()])));`
* [ ] implement a `TimelineAnimation` animation class