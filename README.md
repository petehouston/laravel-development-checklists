# Laravel development checklist

My personal checklist for Laravel development to if there is anything wrong.

## Table of contents

* [Events](#events)


## Checklists

### Events

* [ ] Events are created properly? (check namespace, class name, copy-cat problem...)
* [ ] Listeners are created/generated properly?
* [ ] Events are defined in `EventServiceProvider` or similar?
* [ ] Listeners are bound to events in `EventServiceProvider`?
* [ ] Events are fired any where?
* [ ] If using queue, listeners implemented `ShouldQueue`?
* [ ] Any error while calling events and executing listeners? (check the `laravel.log` also)