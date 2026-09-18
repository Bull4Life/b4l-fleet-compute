# b4l-fleet-compute

Compute lane for the Bull4Life engine. Jobs arrive as an **encrypted payload** on the `kit` branch and
are executed by `replay_build.yml`; results come back as run artifacts.

No engine source is readable here. `kit.enc` is AES-256 and the key is a repository secret.
