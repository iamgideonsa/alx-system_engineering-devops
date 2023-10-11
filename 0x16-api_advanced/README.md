# `0x16. API advanced`

This project was done during **ALX SE Studies** at **ALX School**. The end game is to learn:
* How to read API documentation to find the endpoints you’re looking for
* How to use an API with pagination
* How to parse JSON results from an API
* How to make a recursive API call
* How to sort a dictionary by value

## `Tech`
### `General`
* Used editors: `vi`, `vim`, and `emacs`
* All files are interpreted/compiled on Ubuntu 20.04 LTS using `python3` (version 3.4.3)
* All files end with a new line
* The first line of all files are exactly `#!/usr/bin/python3`
* Libraries imported in Python files are organized in alphabetical order
* A `README.md` file at the root of the folder of the project
* Codes use the `PEP 8` style
* All files are executable
* The length of files is tested using `wc`
* All your modules should have a documentation (`python3 -c 'print(__import__("my_module").__doc__)'`)
* Requests module was used for sending HTTP requests to the Reddit API

## `Files`

| Filename | Description |
| -------- | ----------- |
| `0-subs.py` | A function that queries the `Reddit API` and returns the number of subscribers (not active users, total subscribers) for a given subreddit. If an invalid subreddit is given, the function should return 0. |
| `1-top_ten.py` | A function that queries the `Reddit API` and prints the titles of the first 10 hot posts listed for a given subreddit. |
| `2-recurse.py` | A recursive function that queries the `Reddit API` and returns a list containing the titles of all hot articles for a given subreddit. If no results are found for the given subreddit, the function should return None. |
| `100-count.py` | A recursive function that queries the `Reddit API`, parses the title of all hot articles, and prints a sorted count of given keywords (case-insensitive, delimited by spaces. `Javascript` should count as `javascript`, but `java` should not). |

## `Author:`
### Gideon Selorm Attakpah: <attakpahgideon@gmail.com> [GitHub](https://github.com/iamgideonchrist) - [Twitter](https://twitter.com/iamgideonchrist) - [Linkedin](https://www.linkedin.com/in/iamgideonchrist/)
