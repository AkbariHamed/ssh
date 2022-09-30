# Secure Shell Protocol (SSH)

### Server

- SSH Server Software : **OpenSSH** (alternatives Dropbear)
- SSH Server runs on: Linux, Adobe SD, MacOS
- There are ways to run SSD Server on windows

### Client

- SSH Client: Linux, Windows & macOS

### SSH Commands

- `ssh-keygen -t rsa -C "[youremail]" -f "[filename]"`
- `ssh-keygen -t rsa -b 4096`
- `ssh-keygen -t ecdsa -b 521`
- `ssh-keygen -t ed25519`
- `ssh-keyscan github.com > known_hosts`
- `eval "$(ssh-agent -s)"`
- `ssh-add ~/.ssh/[keyname]`
- `https://www.ssh.com/academy/ssh/command`

### References:

- [SSH academy](https://www.ssh.com/academy/ssh)
- [Creator of SSH](https://ylonen.org/)
- [SSH keygen](https://en.wikipedia.org/wiki/Ssh-keygen)
- [Secure Shell](https://en.wikipedia.org/wiki/Secure_Shell)
- [The pitfalls of using ssh-agent](https://rabexc.org/posts/pitfalls-of-ssh-agents)
- [Using an ssh-agent](https://rabexc.org/posts/using-ssh-agent)
- [GitHub cli multi account](https://gist.github.com/yermulnik/017837c01879ed3c7489cc7cf749ae47)
- [GitHub multi account](https://www.section.io/engineering-education/using-multiple-ssh-keys-for-multiple-github-accounts/)
