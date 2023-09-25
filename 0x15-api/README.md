# `0x15. API`

This project was done during **ALX SE Studies** at **ALX School**. The end game is to learn:
* What Bash scripting should not be used for
* What is an API
* What is a REST API
* What are microservices
* What is the CSV format
* What is the JSON format
* Pythonic Package and module name style
* Pythonic Class name style
* Pythonic Variable name style
* Pythonic Function name style
* Pythonic Constant name style
* Significance of CapWords or CamelCase in Python

**Background Context**
Old-school system administrators usually only know Bash and that is what they use to build their scripts. While Bash is perfectly fine for a lot of things, it can quickly get messy and not efficient compared to other programming languages. The new generation of system administrators, usually called SREs, are pretty much regular software engineers but instead of building products, they are managing systems. And one of the big differences with their predecessors is that they know more than just Bash scripting.

One popular way to expose an application and dataset is to use an API. Often, they are the public-facing part of websites and micro-services that allow outsiders to interact with them – access and modify their data. In this project, you will access employee data via an API to organize and export them to different data structures.

This is a perfect example of a task that is not suited for Bash scripting, so let’s build Python scripts.

## `Tech`
### Python Scripts
* Used editors: `vi`, `vim`, and `emacs`
* All files are interpreted/compiled on Ubuntu 20.04 LTS using `python3` (version 3.8.5)
* All files end with a new line
* The first line of all files is exactly `#!/usr/bin/python3`
* **Libraries imported in Python files are organized in alphabetical order**
* A `README.md` file at the root of the folder of the project
* Code use the pycodestyle (version `2.8`.*)
* All files are executable
* Length of files is tested using `wc`
* All modules have a documentation (`python3 -c 'print(__import__("my_module").__doc__)'`)
* `get` was used to access dictionary value by key
* Code not executed when imported (by using `if __name__ == "__main__":`)

## `Files`

| Filename | Description |
| -------- | ----------- |
| `0-gather_data_from_an_API.py` | A Python script that, using this `REST API`, for a given employee ID, returns information about his/her TODO list progress. |
| `1-export_to_CSV.py` | Using what was done in task #0, extend the Python script to export data in the CSV format. |
| `2-export_to_JSON.py` | Using what was done in task #0, extend the Python script to export data in the JSON format. |
| `3-dictionary_of_list_of_dictionaries.py` | Using what was done in task #0, extend the Python script to export data in the JSON format. |

## `Author:`
### Gideon Selorm Attakpah: [GitHub](https://github.com/iamgideonchrist) - [Twitter](https://twitter.com/iamgideonchrist) - [Linkedin](https://www.linkedin.com/in/iamgideonchrist/)
