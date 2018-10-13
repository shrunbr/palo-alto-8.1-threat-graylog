# palo-alto-8.1-threat-graylog

This is a content pack for Graylog that analyzes threat logs from PanOS 8.1

Syslog listens on 10002 UDP, just create your log forwarder and point it to your server.

This comes with:
- Input for firewall (10002 - UDP)
- All extractors attacted to input
- Threat stream
