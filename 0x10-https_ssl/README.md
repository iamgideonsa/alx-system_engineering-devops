# 0x10. HTTPS SSL

This project was done during **ALX SE Studies** at **ALX School**. The end game is to know:
* What is HTTPS SSL 2 main roles
* What is the purpose of encrypting traffic
* What SSL termination means

## Tech
* Used editors: `vi`, `vim`, and `emacs`
* All files are interpreted on Ubuntu 16.04 LTS
* All files end with a new line
* A `README.md` file at the root of the folder of the project
* All Bash scripts are executable
* Bash script passes `Shellcheck`(version `0.3.7`) without any error
* The first line of Bash scripts are exactly `#!/usr/bin/env bash`
* The second line of Bash scripts is a comment explaining what is the script doing

## Files

| Filename | Description |
| -------- | ----------- |
| `0-world_wide_web` | Configure your domain zone so that the subdomain `www` points to your load-balancer IP (`lb-01`). Let’s also add other subdomains to make our life easier, and write a Bash script that will display information about subdomains. |
| `1-haproxy_ssl_termination` | “Terminating SSL on HAproxy” means that HAproxy is configured to handle encrypted traffic, unencrypt it, and pass it on to its destination.
Create a certificate using `certbot` and configure `HAproxy` to accept encrypted traffic for your subdomain `www.`. |
| `100-redirect_http_to_https` | A good habit is to enforce HTTPS traffic so that no unencrypted traffic is possible. Configure HAproxy to automatically redirect HTTP traffic to HTTPS. |

## Author:
### Gideon Selorm Attakpah: [GitHub](https://github.com/iamgideonchrist) - [Twitter](https://twitter.com/iamgideonchrist) - [Linkedin](https://www.linkedin.com/in/iamgideonchrist/)
