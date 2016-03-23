Ansible role: ffmpeg - https://galaxy.ansible.com/hedii/ffmpeg/
===============================================================

[![Build Status](https://travis-ci.org/hedii/ansible-role-ffmpeg.svg?branch=master)](https://travis-ci.org/hedii/ansible-role-ffmpeg)

Installs ffmpeg build by [John Van Sickle](http://johnvansickle.com/) on any Linux or UNIX system.

Requirements
------------

None.

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`)

```yml
# The path where temp installation files will be stored
ffmpeg_temp_path: "/tmp/ffmpeg"

# The final path of ffmpeg executable
ffmpeg_executable_path: "/usr/bin/ffmpeg"

# The final path of ffprobe executable
ffprobe_executable_path: "/usr/bin/ffprobe"
```

Dependencies
------------

None.

Example Playbook
----------------
```yml
  - hosts: servers
  roles:
    - { role: hedii.ffmpeg }
```

License
-------

MIT

Author Information
------------------

[Hedi Chaibi](https://hedichaibi.com)