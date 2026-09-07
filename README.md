# Wakapi for LazyCat

LazyCat LPK packaging for [Wakapi](https://github.com/muety/wakapi), a minimalist self-hosted WakaTime-compatible backend.

The password salt is generated with LazyCat's stable secret function. Trusted-header authentication maps the authenticated LazyCat user ID to a Wakapi account, while Wakapi's `/api` remains available for WakaTime clients using their Wakapi API keys.
