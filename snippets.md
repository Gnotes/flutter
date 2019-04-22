# 自定义代码片段

在 VSCode 中可以自定义提示代码片段

`Cmd + Shift + P` 打开命令面板，输入 `snippets` 选择 `首选项：配置用户代码片段`，然后选择要配置语言，如 `dart`  
根据提示配置片段，`$1 ...`  是要插入光标的位置，保存后即可.

```js
{
	// Place your snippets for dart here. Each snippet is defined under a snippet name and has a prefix, body and 
	// description. The prefix is what is used to trigger the snippet and the body will be expanded and inserted. Possible variables are:
	// $1, $2 for tab stops, $0 for the final cursor position, and ${1:label}, ${2:another} for placeholders. Placeholders with the 
	// same ids are connected.
	// Example:
	// "Print to console": {
	// 	"prefix": "log",
	// 	"body": [
	// 		"console.log('$1');",
	// 		"$2"
	// 	],
	// 	"description": "Log output to console"
	// }
}
````