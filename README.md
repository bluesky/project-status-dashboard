### The Bluesky Dashboard

This repository is used to generate a dashboard that allows statuses for various
services to be shown for all bluesky-related packages.

The main configuration of the dashboard is done via the ``dashboard.yml`` file,
which can contain several sections with a list of packages, and a list of
services for each section.

## How to Update

1. Edit ``dashboard.yml``.
2. Run ``./make_status``.
3. This generates the artifact ``status.html``. Copy that file into the
   [bluesky/bluesky.github.io](https://github.com/bluesky/bluesky.github.io)
   repository as ``status/index.html``.

The dashboard can be seen at http://blueskyproject.io/status/.
