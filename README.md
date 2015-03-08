# A Database for MMO virtual space

Basic idea.

- Stores points
  - point has a name and a value
  - Uses [Geohash](http://en.wikipedia.org/wiki/Geohash) for it
- Provides box viewport to send changes in the box(like pubsub) to clients
- Supports replication
