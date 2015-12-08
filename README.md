<!--
---
lang: american
---
-->

[![Build Status](https://travis-ci.org/cw-ansible/cw.mmonit.svg?branch=master)](https://travis-ci.org/cw-ansible/cw.mmonit)
[![Tweet this](https://img.shields.io/twitter/url/http/shields.io.svg)](https://twitter.com/intent/tweet?tw_p=tweetbutton&via=renard_0&url=https%3A%2F%2Fgithub.com%2Fcw-ansible%2Fcw.mmonit&text=Install%20and%20configure%20M%2F%23Monit%20using%20%23Ansible.)
[![Follow me on twitter](http://img.shields.io/badge/Twitter-Follow-00aced.svg)](https://twitter.com/intent/follow?region=follow_link&screen_name=renard_0&tw_p=followbutton)

# M/Monit

This roles ensures the [M/Monit](http://mmonit.com/) dashboard is installed and
configured.
 
## Usage

Include the `cw.mmonit` role to your playbook.

## Description

This role downloads the precompiled binaries from M/Monit
[website](http://mmonit.com/download) and installs the dashboard in the `mmonit`
user directory.

For convenience this is then linked to `/etc/mmonit` and `/var/log/mmonit`.

## Configuration

A default trial license is provided, the exact same as the one shipped with the
tarball. You may consider using your own. If you have any licensing issue
please contact [Tildeslash](http://mmonit.com/contact/).

Currently only the *sqlite* database is provided. Some additional features will
come later.

## Copyright

Author: Sébastien Gross `<seb•ɑƬ•chezwam•ɖɵʈ•org>` [@renard_0](https://twitter.com/renard_0)

License: WTFPL, grab your copy here: http://www.wtfpl.net
