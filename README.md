# Demo Git Repository

This is the first file in this repo

## Additional text
The Git configuration file contains a number of variables that affect the Git commands' behavior. The files .git/config and optionally config.worktree (see the "CONFIGURATION FILE" section of git-worktree(1)) in each repository are used to store the configuration for that repository, and $HOME/.gitconfig is used to store a per-user configuration as fallback values for the .git/config file. The file /etc/gitconfig can be used to store a system-wide default configuration.

The configuration variables are used by both the Git plumbing and the porcelains. The variables are divided into sections, wherein the fully qualified variable name of the variable itself is the last dot-separated segment and the section name is everything before the last dot. The variable names are case-insensitive, allow only alphanumeric characters and -, and must start with an alphabetic character. Some variables may appear multiple times; we say then that the variable is multivalued.

### More additional text
The syntax is fairly flexible and permissive; whitespaces are mostly ignored. The # and ; characters begin comments to the end of line, blank lines are ignored.

The file consists of sections and variables. A section begins with the name of the section in square brackets and continues until the next section begins. Section names are case-insensitive. Only alphanumeric characters, - and . are allowed in section names. Each variable must belong to some section, which means that there must be a section header before the first setting of a variable.