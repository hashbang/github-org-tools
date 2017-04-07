# `github-org-tools` -- Managing repository settings in Github organisations

This tool applies settings on repositories of a given Github
organisation, described in a configuration file.

In particular, this can set:
- collaborators and teams with read or write access;
- protected branches, including
  - required status hooks (e.g. “CI must pass before merging”);
  - restrictions on which users may push to the branch;
  - whether “force pushes” are allowed on that branch;
- issue labels.
