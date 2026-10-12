# kairos

Kairos is an independent, non-commercial research project that studies how
geopolitical events relate to disruptive activity on the internet.

It keeps a catalogue of **observation points**: events such as elections,
summits, major policy decisions, strikes and attacks on infrastructure that
are likely to attract DDoS attacks, disinformation or other hybrid activity.
Each event has a time window. Kairos compares public internet measurement
data against these windows to see whether, when and how strongly such events
leave a trace.

## Approach

- **Event catalogue:** events are entered by hand or proposed by importers.
  Every event is verified by a person before it enters the catalogue.
- **Network signals:** public measurement sources are used to follow
  reachability, routing and attack traffic for selected countries and
  networks.
- **Null results count:** a checked event with no visible effect is recorded
  as well.

The first retrospective test looked at the drone strikes on Yandex data
centres in Russia in October 2026. Two of the three strikes were clearly
visible in public reachability data. Routing data did not show them.

## Data sources

IODA (Georgia Tech), RIPEstat (RIPE NCC), Cloudflare Radar, GDELT, and
(pending access) ACLED and IFES ElectionGuide. Each source is used under its
own terms. Raw data is not redistributed.

## Status and development

Kairos is an early-stage proof of concept and a personal research project. It
is not affiliated with a university, company or other organisation.

Development happens in a private repository. This public repository describes
the project; code and findings may be published here later.

## Contact

Please open an issue in this repository.

Maintainer: Jussi (V.) Leskinen
