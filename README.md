# *pexpect* module for Package Control

This is the *[pexpect](https://pexpect.readthedocs.io/en/stable/)* module
bundled for usage with [Package Control](http://packagecontrol.io/),
a package manager
for the [Sublime Text](http://sublimetext.com/) text editor.


## How to use *pexpect* as a dependency

In order to tell Package Control
that you are using the *pexpect* module
in your ST package,
create a `dependencies.json` file
in your package root
with the following contents:

```js
{
   "*": {
      ">3000": [
         "pexpect"
      ]
   }
}
```

If the file exists already,
add `"pexpect"` to the every dependency list.

Then run the **Package Control: Satisfy Dependencies** command
to make Package Control
install the module for you locally
(if you don't have it already).

After all this
you can use `import pexpect`
in any of your Python plugins.

See also:
[Documentation on Dependencies](https://packagecontrol.io/docs/dependencies)


## How to update this repository (for contributors)

1. Download the latest tarball
   from [pypi](https://pypi.python.org).
2. Delete everything inside the `st3/` folder.
3. Copy the `pexpect/` folder
   and everything related to copyright/licensing
   from the tarball
   to the `st3/` folder.
4. Commit changes
   and either create a pull request
   or create a tag directly
   in the format `v<version>`
   (in case you have push access).


## License

The contents of the root folder
in this repository
are released
under the *public domain*.
The contents of the `st3/` folder
fall under *their own bundled licenses*.

## Links

- [pexpect](https://pexpect.readthedocs.io/en/stable/)
- [Package Control](http://packagecontrol.io/)
- [Sublime Text](http://sublimetext.com/)
- [pypi](https://pypi.python.org/pypi/pexpect)
