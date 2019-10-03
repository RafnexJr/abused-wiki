# What to Log

This is a list of things that should throw alerts in your SIEM. Start by implementing some things and move on and integrate more and more. Try to minimize the false positives and noise in the alerts as much as possible.

- [What to Log](#what-to-log)
  - [Network](#network)
  - [DNS](#dns)

## Network

- [ ] External IP on blacklist
- [ ] Unexpected protocol on well known ports
- [ ] Client signatures (unique user agent)
- [ ] Unexpected protocol use

## DNS

- [ ] Domain less than 30 days old
- [ ] Amount of sub domains
