# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-export-declaration > export-function`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "esprima/es2015-export-declaration/export-function/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array []
	loc: Object {
		filename: "esprima/es2015-export-declaration/export-function/input.js"
		end: Object {
			column: 0
			index: 26
			line: 2
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSExportLocalDeclaration {
			exportKind: "value"
			specifiers: undefined
			loc: Object {
				filename: "esprima/es2015-export-declaration/export-function/input.js"
				end: Object {
					column: 25
					index: 25
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			declaration: JSFunctionDeclaration {
				id: JSBindingIdentifier {
					name: "foo"
					loc: Object {
						filename: "esprima/es2015-export-declaration/export-function/input.js"
						identifierName: "foo"
						end: Object {
							column: 19
							index: 19
							line: 1
						}
						start: Object {
							column: 16
							index: 16
							line: 1
						}
					}
				}
				loc: Object {
					filename: "esprima/es2015-export-declaration/export-function/input.js"
					end: Object {
						column: 25
						index: 25
						line: 1
					}
					start: Object {
						column: 7
						index: 7
						line: 1
					}
				}
				body: JSBlockStatement {
					body: Array []
					directives: Array []
					loc: Object {
						filename: "esprima/es2015-export-declaration/export-function/input.js"
						end: Object {
							column: 25
							index: 25
							line: 1
						}
						start: Object {
							column: 23
							index: 23
							line: 1
						}
					}
				}
				head: JSFunctionHead {
					async: false
					generator: false
					hasHoistedVars: false
					params: Array []
					rest: undefined
					returnType: undefined
					thisType: undefined
					typeParameters: undefined
					loc: Object {
						filename: "esprima/es2015-export-declaration/export-function/input.js"
						end: Object {
							column: 22
							index: 22
							line: 1
						}
						start: Object {
							column: 20
							index: 20
							line: 1
						}
					}
				}
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```