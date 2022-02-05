# pwnMENU
### >> by stimpz0r (2022)

A simple layout for a HTTPD server that is compatible with my other project [pwnMENU](https://github.com/stimpz0r/pwnMENU), used to host tools needed for penetration testing.

> **NOTE:** The tools provided in this repo are purely intended for use on targets that you have authority to perform a penetration test on (whether it be commercially or for friend/family), for CTFs or testing on your own system. I am not responsible for any misuse of these tools.

## Installation

Simply clone this repo to your system, and if using these with **pwnMENU**, change the `httpd_root_dir` variable to point to where you cloned this repo.

You can also simply download this repo and point your Python HTTPD to use this as the root folder... for example:

```
python3 -m http.server -d /path/to/pwnTOOLS -b <bind-ip> <port>
```
