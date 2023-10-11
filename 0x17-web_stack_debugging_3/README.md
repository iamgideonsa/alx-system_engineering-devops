# `0x17. Web stack debugging #3`

When debugging, sometimes logs are not enough. Either because the software is breaking in a way that was not expected and the error is not being logged, or because logs are not providing enough information. In this case, you will need to go down the stack, the good news is that this is something Holberton students can do :)

WordPress is a very popular tool, it allows you to run blogs, portfolios, e-commerce, and company websites… It actually powers 26% of the web, so there is a fair chance that you will end up working with it at some point in your career.

WordPress is usually run on LAMP (Linux, Apache, MySQL, and PHP), which is a very widely used set of tools.

The web stack you are debugging today is a WordPress website running on a LAMP stack.

## `Tech`
### `General`
* All files are interpreted on Ubuntu 14.04 LTS
* All files end with a new line
* A `README.md` file at the root of the folder of the project
* Puppet manifests pass `puppet-lint` version 2.1.1 without any errors
* Puppet manifests run without error
* The Puppet manifest's first line is a comment explaining what the Puppet manifest is about
* Puppet manifests files end with the extension `.pp`
* Files are checked with Puppet v3.4

## `Files`

| Filename | Description |
| -------- | ----------- |
| `0-strace_is_your_friend.pp` | Using `strace`, find out why Apache is returning a 500 error. Once you find the issue, fix it and then automate it using Puppet (instead of using Bash as you were previously doing). |

## `Author:`
### Gideon Selorm Attakpah: <attakpahgideon@gmail.com> - [GitHub](https://github.com/iamgideonchrist) - [Twitter](https://twitter.com/iamgideonchrist) - [Linkedin](https://www.linkedin.com/in/iamgideonchrist/)
