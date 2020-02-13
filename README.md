# A very simple to-do app

### Installation
For now, clone the repo, then link it to either `/usr/bin` or `$HOME/bin` with:
`$ ln -s path/to/todo/todo ~/bin/todo`

You probably will have to make it executable:
`$ chmod +x path/to/todo/todo`

Then make a directory called "todo" in `$HOME/todo`:
`$ mkdir ~/todo`

### Getting Started
Type `todo` in the command line. Hopefully it works.

`todo d` accepts most commands that `date -d` will, such as:
`$ todo d "next Friday"`
