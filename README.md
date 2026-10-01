# cbrd: Board

Thin composition of Link, Profile, Envelope, Exchange, Search, Groups and Attend. Board is the single member facade reaching the Forum and has no duplicate profile, index, roster or policy engine.

Implementation is in progress. No integration or coverage acceptance is claimed.

Board now holds one Link and delegates same-community local validation and
give-first inspection to their owners. Groups and Attend consumer types are
reexported directly; their runtime adapters remain unavailable. See the
[contract](docs/CONTRACT.md) for implemented and pending boundaries.
