# Sub-GHz/NFC Driver Review
## Sub-GHz (CC1101)
- Buffer allocation: Potential overflow risk at high signal rates.
- Modulation: AM650 supported; AM270 not supported, consider adding.
- Memory: Fits within 256KB RAM; monitor stack usage.
## NFC (ST25R3916)
- Missing nfc directory; see issue #X.
