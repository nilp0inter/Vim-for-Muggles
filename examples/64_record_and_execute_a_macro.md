### Record and Execute a Macro

Given this text:

```javascript
foo1 = 1
bar1 = 'a'
foobar = foo1 + bar1
foo2 = 2            
bar2 = 'a'          
foobar = foo2 + bar2
foo4 = 3            
bar3 = 'a'          
foobar = foo3 + bar3
foo6 = 4            
bar4 = 'a'          
foobar = foo4 + bar4
```

Start on the first line  
`qa` - start recording your macro in the "a" register  
`A;` - append semicolon at the end of the line  
`Ivar<Space><Esc>` - add "var" to the beginning of the line  
`q` - quit recording the macro  

Inspect what's in register a with `:reg a`

`@{register}` - will replay the macro

`j` - go to next line  
`@a` - replay it on second line  
`j@@` - replay it on the next line  
