# Event Sourcing

- Event Sourcing stores changes to application state as a sequence of events
- Instead of storing only the current state, each important change is recorded as an event
- The current state can be rebuilt by replaying the stored events
- It provides a detailed history of changes and is useful in distributed systems