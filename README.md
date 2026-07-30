# Klout

Klout was a San Francisco social-analytics company, founded in 2008 by Joe Fernandez and Binh Tran, that scored individuals on their online social influence. The "Klout Score" was a single number from 1 to 100 derived from the size of a person's social network and how other people engaged with the content they published across connected accounts such as Twitter, Facebook, LinkedIn, Instagram, and Google+.

Klout operated a public REST API — the Klout API v2 at `api.klout.com` — that let developers resolve a social handle to a Klout identity, look up a user's score and score history, and retrieve influence graphs and topic affinities. A large community of third-party client libraries grew up around it in Ruby, Node.js, Python, and PHP.

## Status: defunct

Lithium Technologies acquired Klout on 27 March 2014 for approximately $200 million, and retired Klout as a standalone service on **25 May 2018** — the day the EU General Data Protection Regulation took effect. The Klout API was shut down with the service. Lithium has since been rebranded as Khoros, and `klout.com` now redirects into the Khoros website.

`api.klout.com` and `developer.klout.com` no longer resolve. This profile is retained as a historical provider record in the API Evangelist network.

## Artifacts

- `lifecycle/klout-lifecycle.yml` — retirement, sunset, and acquisition record, with live host probes
- `packages/klout-packages.yml` — the historical community SDK ecosystem (no first-party SDK ever shipped)
- `security/klout-domain-security.yml` — probed DNS/TLS posture of the surviving domain

Backed by: kleiner-perkins
