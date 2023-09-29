Assume ```:``` in front of all commands in Vim

Change all instances of 'foo' to 'bar'
```BASH
%s/foo/bar/g
```

Change specific line number instances of 'foo' to 'bar' relative to current line
```BASH
+13s/foo/bar/g
```

Change all instances of 'foo' to 'foo /dev/null 2>&1' - with escape character '\\' (backslash)
What's /dev/null 2>&1 you ask? Decent REF: https://stackoverflow[.]com/questions/10508843/what-is-dev-null-21
```BASH
%s/foo/foo >\/dev\/null 2>\&1/g
```

Change all instances of 'foo' to 'foo /dev/null 2>&1' - specifying a different delimiter, e.g., '@'
```BASH
%s@foo@foo >/dev/null 2>\&1@g
```

Horizontal Split with another file
```BASH
split <FILE-PATH>
```

Vertical Split with another file
```BASH
vsplit <FILE-PATH>
```

Move between split windows in a specific direction

CTRL+w (then) \<{h,j,k,l}>

---
#
#