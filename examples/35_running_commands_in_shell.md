### Running commands in shell


1. Sort the content of this text:

```
first name, last name, email
john,smith,john@example.com
drew,neil,drew@vimcast.org
jane,doe,jane@example.com
```

Visual highlight the lines to be sorted  
`:'<,'>!sort -t',' -k2` - the sort shell command is used to sort the lines  

2. Pull up command history in vim

`q:` will show normal mode history  
`q/` will show search history  
