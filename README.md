# Awesome Event Patterns 🚀

Collection of links, videos and things to help with event architecture event patterns.

Contributions welcome!

## Table of Contents

- [Videos](#videos)
- [Written resources](#written-resources)

## Videos
- [DDD Europe 2020 Keynote by Udi Dahan](https://www.youtube.com/watch?v=-iuMjjKQnhg&t=2485s) - Udi Dahan gives a great talk about DDD and also goes into event patterns talking about internal and external events within your domains.

- [Events Everywhere! Different Type of Events in a Distributed System](https://www.youtube.com/watch?v=PJPxdl-1ucg) - Great talk with James Hickey and Derek Comartin as they talk about types of events in distributed systems.

- [Message Naming Guidelines](https://www.youtube.com/watch?v=EmtOB2XexJI&t=478s) - Derek Comartin gives a great video and walkthough on naming guidelines for events.


## Written resources

- [Segreated Event Layers](https://verraes.net/2019/05/patterns-for-decoupling-distsys-segregated-event-layers/) - Mathias Verraes talks about internal events within a domain and using streams to consume them and expose different events.
- [Patterns for Decoupling in Distributed Systems: Fat Event](https://verraes.net/2019/05/patterns-for-decoupling-distsys-fat-event/) - Mathias Verraes goes into what state in an event could look like, the downsides and things to consider.
- [Patterns for Decoupling in Distributed Systems: Passage of Time Event](https://verraes.net/2019/05/patterns-for-decoupling-distsys-passage-of-time-event/) - An interesting event pattern to replace cron jobs and scheduled commands with event to indicate teh passage of time.
- [Patterns for Decoupling in Distributed Systems: Summary Event](https://verraes.net/2019/05/patterns-for-decoupling-distsys-summary-event/) - Rather than emitting a stream of events from a domain why not emit a single summary event at the end? Could you place your events with summary events?

- [The different types of events in event-driven systems](https://blog.frankdejonge.nl/the-different-types-of-events-in-event-driven-systems) - Great read by Frank de Jonge as he goes into three types of events for our EDA applications, the domain event, trigger/signal event and RESTful or "Fat" event.

- [Use a message envelope](https://blog.frankdejonge.nl/use-a-message-envelope/) - Another great read by Frank de Jonge as he goes into message envelopes. Talks about what goes into an event, domain boundaries, decorators and much more.

- [CQRS Documents by Greg Young](https://cqrs.files.wordpress.com/2010/11/cqrs_documents.pdf#page=25) - Very detailed document around CQRS and Greg goes into domain events, events as storage and much more

- [Thin vs Fat Integration Events](https://codeopinion.com/thin-vs-fat-integration-events/) - Derek Comartin has some great content around event-driven architectures, in this blog post he walks though fat vs thin integration events with videos to support. Check out his [YouTube channel](https://www.youtube.com/channel/UC3RKA4vunFAfrfxiJhPEplw) too!

- [The event notification pattern](https://medium.com/geekculture/the-event-notification-pattern-a62d48519107) - Oskar uit de Bos gives us some great insight and thoughts into event notification pattern, recommended read!

- [The Event-Carried State Transfer pattern](https://itnext.io/the-event-carried-state-transfer-pattern-aae49715bb7f) - Another great read by Oskar uit de Bos, as he gives into the ECST pattern and highlights the good, bad and ugly.


- [https://www.gokhan-gokalp.com/en/how-should-my-event-be-designed-some-thoughts-on-event-based-systems/](https://www.gokhan-gokalp.com/en/how-should-my-event-be-designed-some-thoughts-on-event-based-systems/) - Gökhan Gökalp gives us his thoughts on Event-Based systems and designs for our events.


