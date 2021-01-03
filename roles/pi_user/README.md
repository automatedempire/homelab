# Important

This role requires an SSH public key for the active user to be present in the target system user's `~/.ssh/authorized_keys` file. The role will figure out which user to use based on the gathered facts, but to gather those facts, we need to be able to log in.
