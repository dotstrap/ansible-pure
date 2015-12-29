pure
==================
<!-- [![Build Status](https://travis-ci.org/mkwmms/ansible-pure.svg)](https://travis-ci.org/mkwmms/pure) -->

Install & configure the [pure] prompt for bash, [zsh] & [fish] shells.

Requirements
------------

None.

Role Variables
--------------

See [default variables] & [variables].

Dependencies
------------

None.

Example Playbook
----------------

```
    - hosts: servers
      roles:
         - { role: mkwmms.pure }
```

Notes
-----

__Warning__: This role modifies your default shell configuration file, eg.
`~/.bash_profile`, `~/.zshrc` or `~/.config/fish/config.fish`.

License
-------

GPLv3

Author Information
------------------

[@mkwmms]

[@mkwmms]: https://github.com/mkwmms
[aura]: https://github.com/aurapm/aura
[default variables]: defaults/main.yml
[dotstrap]: https://github.com/mkwmms/dotstrap
[fasd]: https://github.com/clvv/fasd
[files]: files/
[fish]: http://fishshell.com/
[homebrew]: https://github.com/Homebrew/homebrew
[pure]: https://github.com/sindresorhus/pure
[variables]: vars/main.yml
[variables]: vars/main.yml
[yaourt]: https://github.com/archlinuxfr/yaourt
[z]: https://github.com/rupa/z
[zsh]: http://zsh.sourceforge.net
