# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > declaration-const > migrated_0002`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "input.js"
		end: Object {
			column: 0
			index: 34
			line: 2
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSBlockStatement {
			directives: Array []
			loc: Object {
				filename: "input.js"
				end: Object {
					column: 33
					index: 33
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			body: Array [
				JSVariableDeclarationStatement {
					loc: Object {
						filename: "input.js"
						end: Object {
							column: 31
							index: 31
							line: 1
						}
						start: Object {
							column: 2
							index: 2
							line: 1
						}
					}
					declaration: JSVariableDeclaration {
						kind: "const"
						loc: Object {
							filename: "input.js"
							end: Object {
								column: 31
								index: 31
								line: 1
							}
							start: Object {
								column: 2
								index: 2
								line: 1
							}
						}
						declarations: Array [
							JSVariableDeclarator {
								id: JSBindingIdentifier {
									name: "x"
									loc: Object {
										filename: "input.js"
										identifierName: "x"
										end: Object {
											column: 9
											index: 9
											line: 1
										}
										start: Object {
											column: 8
											index: 8
											line: 1
										}
									}
								}
								loc: Object {
									filename: "input.js"
									end: Object {
										column: 14
										index: 14
										line: 1
									}
									start: Object {
										column: 8
										index: 8
										line: 1
									}
								}
								init: JSNumericLiteral {
									value: 14
									format: undefined
									loc: Object {
										filename: "input.js"
										end: Object {
											column: 14
											index: 14
											line: 1
										}
										start: Object {
											column: 12
											index: 12
											line: 1
										}
									}
								}
							}
							JSVariableDeclarator {
								id: JSBindingIdentifier {
									name: "y"
									loc: Object {
										filename: "input.js"
										identifierName: "y"
										end: Object {
											column: 17
											index: 17
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
									filename: "input.js"
									end: Object {
										column: 21
										index: 21
										line: 1
									}
									start: Object {
										column: 16
										index: 16
										line: 1
									}
								}
								init: JSNumericLiteral {
									value: 3
									format: undefined
									loc: Object {
										filename: "input.js"
										end: Object {
											column: 21
											index: 21
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
							JSVariableDeclarator {
								id: JSBindingIdentifier {
									name: "z"
									loc: Object {
										filename: "input.js"
										identifierName: "z"
										end: Object {
											column: 24
											index: 24
											line: 1
										}
										start: Object {
											column: 23
											index: 23
											line: 1
										}
									}
								}
								loc: Object {
									filename: "input.js"
									end: Object {
										column: 31
										index: 31
										line: 1
									}
									start: Object {
										column: 23
										index: 23
										line: 1
									}
								}
								init: JSNumericLiteral {
									value: 1_977
									format: undefined
									loc: Object {
										filename: "input.js"
										end: Object {
											column: 31
											index: 31
											line: 1
										}
										start: Object {
											column: 27
											index: 27
											line: 1
										}
									}
								}
							}
						]
					}
				}
			]
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```