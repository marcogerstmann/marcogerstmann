I build backend systems that have to stay correct when things go wrong: messages
delivered twice, partial failures, retries that make it worse. Most of that work
is event-driven.

I have been doing this professionally since 2014. Most of my day is Java and
Spring Boot. A lot of what I know about keeping systems simple comes from years
in Go, and my current side project is in Node.js. Comparing how the three solve
the same problems is where most of my writing comes from.

**Currently building** [portionium](https://github.com/marcogerstmann/portionium),
a self-hosted food and weight journal that replaces calorie counting with a three-colour
energy-density scale. Node.js backend with idempotent writes, strict per-user isolation 
and backups that are restored in CI on every push.

**Recent writing**

- [A Queue Moves Work. A Bus Announces Facts.](https://marcogerstmann.com/posts/work-queue-vs-event-bus/)
- [Your Queue Will Deliver That Message Twice. Be Ready.](https://marcogerstmann.com/posts/idempotency-event-driven/)
- [Not Every Error Deserves a Retry: Permanent vs. Transient Failures](https://marcogerstmann.com/posts/permanent-vs-transient-errors/)

More at [marcogerstmann.com](https://marcogerstmann.com) and on
[LinkedIn](https://www.linkedin.com/in/marcogerstmann).
