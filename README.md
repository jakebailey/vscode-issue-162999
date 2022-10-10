To reproduce, set `"git.mergeEditor": true`, then:


```
$ git switch branch-2-copy
$ git cherry-pick branch-1
```

Open `example.txt` from the explorer; note that the file is CRLF at the bottom right.

Click "Open in Merge Editor"; note that now the file is LF at the bottom right.

Switch tabs back to `example.txt`; note that the file is LF here too.
