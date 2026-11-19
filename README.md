# Geofeed

Geo-feed for Spectrum (Charter Communications, Inc.) in RFC 8805 format

Please use the following URL for external publishing:
https://raw.githubusercontent.com/SpectrumGeo/Geofeed/main/spectrum-geofeed.txt

Each entry is `ip_prefix,alpha2code,region,city,postal_code`.

Note to maintainers:
The "stripped" version is identical minus comments. To generate, use a simple `grep -v '^#' spectrum-geofeed.txt > spectrum-geofeed-stripped.txt` or similar.
Both files are regenerated automatically and updated here whenever the feed data changes, so edits made directly in this repository are overwritten by the next update.
