# lxd-tramp - TRAMP integration for LXD containers

`lxd-tramp.el` offers a TRAMP method for LXD containers.

It uses `lxc` command line tool to login to containers
and list running containers (for completion purpose).

## Usage

Offers the TRAMP method `lxd` to access running containers

    C-x C-f /lxd:user@container:/path/to/file

    where
      user           is the user that you want to use (optional)
      container      is the id or name of the container

---
Thanks to [*montag451*](https://github.com/montag451/lxc-tramp) the author of `lxc-tramp.el` for suggestions.