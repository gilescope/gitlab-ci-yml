# gitlab-ci-parser

Parses a .gitlab-ci.yml file and makes a semantic model from it.
(E.g. Jobs are linked to their parents.)

**ALPHA**

PRs wellcome - currently it only parses what I need.

  * .extends is now supported.
  * yaml merge << and anchors should work.
  * remote includes are assumed to be checked out in a sister directory.

Dual licensed: MIT + Apache 2.