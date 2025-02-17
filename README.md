# Try Autoupdate
Experimenting with github autoupdate https://github.com/chinthakagodawita/autoupdate/
See discussion in https://github.com/chinthakagodawita/autoupdate/issues/399

See [.github/build.yml](.github/build.yml) and [.github/autoupdate.yml](.github/autoupdate.yml)

- [.github/build.yml](.github/build.yml) does nothing special, it just runs, immitating some real build.
- [.github/autoupdate.yml](.github/autoupdate.yml) runs on labelled PRs, does autoupdate chinthakagodawita/autoupdate as a first job and then triggers build.yml on open branches with "autoupdate" label as a separate job.

Some fiddeling with repo settings was also necessary.
