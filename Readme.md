# Readme

### Rename all files to sequential order on linux
`ls | cat -n | while read n f; do mv "$f" `printf "%04d.jpg" $n`; done`