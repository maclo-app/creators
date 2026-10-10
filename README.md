# Maclo creators

The dashboard page Maclo's creators open with their private link.

It is one static file with no keys in it. A creator's link ends in a secret after
the `#`; the page sends that to Maclo's server and shows the creator their own
totals. Opened without a link, it shows nothing.

The source of truth is `web/creators/index.html` in the main Maclo repository;
this repository only exists to host it. Do not edit here.
