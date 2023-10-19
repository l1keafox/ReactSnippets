# ReactSnippets

##vscode-react-javascript-snippets

file
preferences
use snippets
global snippet file
name the file.
Add snippets as wanted.

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
