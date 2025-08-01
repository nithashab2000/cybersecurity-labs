# cybersecurity-labs
This repository documents hands-on learning through the OverTheWire Bandit wargame, focused on Linux command-line usage and fundamental security concepts.

---

## OverTheWire – Bandit Wargame (Levels 0–20)

- Practiced Linux commands such as `ls`, `cat`, `cd`, `file`, `find`, `grep`, `base64`, `xxd`, `cut`, `strings`, `gzip`, and `bzip2`
- Worked with hidden files, unusual filenames, symbolic links, and hexdump-encoded files
- Explored file permissions, redirection, and decoding layers (e.g., Base64 → gzip → bzip2)
- Used shell tools to inspect, decode, and reconstruct binary and encoded content
- Gained practical experience in navigating and analyzing file systems securely
- Used a private SSH key to authenticate without a password  
- Connected to the next level via `ssh` using the `-i` option for key-based authentication  
- Understood the use of `localhost` to connect to services running on the same machine
- Retrieved password data through socket communication over the specified port using netcat(nc)command
- Used `openssl s_client` to securely transmit the password over a TLS-encrypted connection to a specific port
- Retrieved a SSH private key obtained via TLS-encrypted netcat communication to authenticate to the next level
- Compared file differences using 'diff' command to identify the updated password to the next level from the similiar content files
- Bypassed forced logout by remotely executing a command via SSH to read the password without triggering '.bashrc'
- Used a SUID binary to safely execute a privileged command and retrieve the next level's password
- Used a TCP socket listener to deliver the password to a local binary that validates input over a specified port
---

## Skills Acquired

- Linux file system navigation  
- Command-line based security tasks  
- File decoding and multi-step extraction techniques  
- Working with file permissions, symbolic links, and encodings  
- Hexdump reversal and binary file reconstruction  
- Identifying and reading hidden or protected files
- Used SSH key-based authentication
- Practiced basic TCP communication using 'netcat'
- Performed SSL/TLS-encrypted data transmission with `openssl`
- Performed secure port scanning, SSL communication, and private key-based SSH authentication
- Used the 'diff' command to efficiently compare the similiar files and extract the particular change
- Remotely executing shell commands via SSH to bypass login-shell restrictions
- Executed SUID binaries to temporarily gain elevated permissions for secure file access
- Set up a TCP listener to simulate client-server password exchange using nc and validated it through a local binary
---

## In Progress

- Continuing Bandit Levels 21+ to build deeper understanding of CLI security, scripting, and advanced permission handling

---

## Contact

- nithashababuraj2000@gmail.com  
- [LinkedIn](https://www.linkedin.com/in/nithasha-babu-raj-477a351b9/)  
- [GitHub](https://github.com/nithashab2000)
