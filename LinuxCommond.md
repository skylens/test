

## Linux Command

--------------------------------------------

### whereis

``` # whereis startx
startx: /usr/bin/startx /usr/share/man/man1/startx.1.gz ```

``` # whereis ls
ls: /bin/ls /usr/share/man/man1/ls.1.gz /usr/share/man/man1/ls.1posix.gz ```


### which

``` # which startx
/usr/bin/startx ```

### who

``` # who
tux      tty8         2016-08-14 10:24
tux      pts/0        2016-08-14 10:24 (:0)
tux      pts/1        2016-08-14 10:24 (tmux(3619).%0)
tux      pts/2        2016-08-14 10:45 (192.168.1.1) ```


### whoami

``` # whoami
VM ```

### dpkg

``` # dpkg -S /usr/bin/startx ```
``` # dpkg -S ` which startx ` ```


