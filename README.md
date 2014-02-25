# ASP Snippets for Sublime

## Install

To install through [Package Control](http://wbond.net/sublime_packages/package_control),
search for **ASP Snippets**. If you still don't have Package Control in Sublime Text, [go get it](http://wbond.net/sublime_packages/package_control/installation).
It's pure awesomeness.

If you insist to not install it, you can download the package and put it manually inside your `Packages` directory. It should work but will not update automatically.


### [if] if

```
if ${1:false} then
	${2}
end if
```

### [ife] if else

```
if ${1:false} then
	${2}
else
	${3}
end if
```

### [dow] do while

```
do while ${1:false}
	${2}
loop
```

### [ifeif] if elseif

```
if ${1:false} then
	${2}
elseif ${3:false} then
	${4}
end if
```

### [set] set

```
set ${1} = ${2}
```

### [dim] dim

```
dim ${1} = ${2}
```

### [rw] response.write
```
response.write ${1}
```

### [rr] response.redirect
```
response.redirect "${1}"
```

### [rc] response.clear
```
response.clear
```

### [re] response.end
```
response.end
```

### [rqs] request.querystring
```
request.querystring("${1}")
```

### [rqf] request.form
```
request.form("${1}")
```

### [sub] sub
```
sub ${1}(${2})
	${3}
end sub
```

### [publ] public function
```
public function ${1}(${2})
	${3}
end function
```

### [func] function
```
function ${1}(${2})
	${3}
end function
```
## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

Check [Release](https://github.com/marcosisocram/asp-snippets/releases) list.

## License

[MIT License](http://mp.mit-license.org/) © Marcos Paulo