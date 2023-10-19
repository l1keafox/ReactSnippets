# ReactSnippets

##vscode-react-javascript-snippets

1.file

2.preferences

3.use snippets

4.global snippet file

5.name the file.

6.Add snippets as wanted.

```
	"React Component W Prop": {
		"scope": "typescriptreact",
		"prefix": "rrfc",
		"body": [
			"",
			"export interface ${1:$TM_FILENAME_BASE}Props{",
			"}",
			"",
			"export function ${1:$TM_FILENAME_BASE}({}:${1:$TM_FILENAME_BASE}Props) {",
  		"	return <div>${1:$TM_FILENAME_BASE}</div>",
			"}",
		],
		"description": "Creates two exports as interface and function"
	}
```
