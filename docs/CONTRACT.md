# Board contract

Thin composition of Link, Profile, Envelope, Exchange, Search, Groups and Attend. Board is the single member facade reaching the Forum and has no duplicate profile, index, roster or policy engine.

All work and inputs are bounded and community scoped. Missing or stale owner
authority fails closed. Candidate effects are persisted before external output;
ambiguous persistence must reconcile, never publish speculatively.

Native and executed wasm vectors, exact reachable line and branch coverage,
and independent review are required before acceptance.
