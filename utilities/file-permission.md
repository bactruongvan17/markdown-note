# File permission

### Symbols

| Permission | Meaning          | Number |
| ---------- | -------          | ------ |
| rwx        | Full permissions | 7      |
| rw-        | Read + Write     | 6      |
| r-x        | Read + Execute   | 5      |
| r--        | Read             | 4      |
| -wx        | Write + Execute  | 3      |
| -w-        | Write            | 2      |
| --x        | Execute          | 1      |
| ---        | No permissions   | 0      |


### Structures

> Owner - Group - Other

> Example:\
> 765: \
> + __Owner__: _read + write + execute_
> + __Group__: _read + write_
> + __Other__: _read + execute_
