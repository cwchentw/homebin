# Michael's homebin

Some handy scripts.

## Usage

Add the *bin* sub-directory to PATH variable.


## Available Commands

### bitly

Generate short url.  Now use Bitly api ver 3. **BITLY_ACCESS_TOKEN** environment variable is needed to use the command.

### check

Check whether a process is running.  `grep` is excluded.

### body

Execute command except header part.  From Data Science at the Command Line.

### elisp

Use Emacs as an interpreter.  By default, error message is suppressed.

```
# Show stdout only.
$ elisp script.el

# Show stdout and stderr.
$ DEBUG=1 elisp script.el
```

### header

Add, remove and edit header of a CSV file.  From Data Science at the Command Line.

### mailto

Send mail by Mailgun Ruby API.  You need a personal domain and a Mailgun account to use the script.  Besides, set the two environment variable **MAILGUN_API_KEY** and **MAILGUN_DOMAIN**.

### pid

Check the pid of the process by name.  Use `check` internally.

### podweb

Call `podwebserver` if no podwebserver process initiated.  Perl module `Pod-Webserver` needed.

### ruler

Show a ruler on command line.  Example: `ruler; ls -l; ruler`.

### removepkg

Remove pkg package on Mac.

### start

Start a persisting background process.  It changes to home root directory and left log files there.  Use the command `pid` internally.

### stop

Stop a persisting background process.  Use the command `pid` internally.

### weather 

Query weather from the command line.  Use http://wttr.in internally.

```
$ weather taipei
```

### unpack

Decompress various file formats.  It needs 7z, unrar, unzip, and miscellaneous decompressing tools.  From Data Science at the Command Line.


## Reference

Data Science at the Command Line (http://datascienceatthecommandline.com/)
>>>>>>> e4636efbf54719f3562c4f0f46d77dacc3192673


## License

MIT
