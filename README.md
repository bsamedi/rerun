# Rerun
Command line tool to rerun a command upon files changed on disk.<br>
Implements subset of [Ruby rerun](https://github.com/alexch/rerun) command options

## Installation
Copy files `rerun` and `wait-for-file-changed` into  one of your $PATH locations

## Usage
`rerun [options] [--] command`<br>
Options:<br>
`--clear` or `-c`: clear screen before each launch of the `command`<br>
`--dir dirname` or `-d dirname`: track changes<br>
