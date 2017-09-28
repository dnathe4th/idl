
# v3.2.0 (unreleased)

- Fixes a bug where IDL would fail to update the cache repository. (@dnathe4th)


# v3.1.8 (2017-07-24)

- Uses shallow clone and fetch to expedite all IDL commands that interact with
  their IDL registry. (@kriskowal)


# un-numbered release on master

- Filters yab files from IDL lists. (@prashantv)


# v3.1.7

- Fixes a bug when an IDL depends on another IDL that is not in the root of the
  dependency's repository path. (@ankits)


# v3.1.6


# v3.1.5

- Bug fix to address issues with EMFILE errors
  (back-off on depletion of file descriptors).
