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
							"export interface ${1:$TM_FILENAME_BASE}Props{",
							"}",
							"",
							"export function ${1:$TM_FILENAME_BASE}({}:${1:$TM_FILENAME_BASE}Props) {",
							"	return (",
							"	<>",
							"		<h1>${1:$TM_FILENAME_BASE}</h1>"
							"	</>"
							"	);"
							"}",
						],
		"description": "Creates two exports as interface and function"
	}
```

```
	"console.log shortcut": {
		"scope":"typescriptreact",
		"prefix": "cnslg",
		"body": [
							"console.log(`${1}`);"
						],
		"description": "Creates two exports as interface and function"		
	}
```


```
	"create a sample storybook story.tsx file to connect": {
		"prefix": "story",
		"body": [
		  "import type { Meta, StoryObj } from '@storybook/react';",
		  "",
		  "import $1 from './$1';",
		  "",
		  "const meta: Meta<typeof $1> = {",
		  "  component: $1,",
		  "};",
		  "",
		  "export default meta;",
		  "type Story = StoryObj<typeof $1>;",
		  "",
		  "/*",
		  " *👇 Render functions are a framework specific feature to allow you control on how the component renders.",
		  " * See https://storybook.js.org/docs/react/api/csf",
		  " * to learn how to use render functions.",
		  " */",
		  "export const Primary: Story = {",
		  "  render: () => <$1 />,",
		  "};",
		  ""
		],
		"description": "create a sample story"
  }

```
