# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > class > extends-implements`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "typescript/class/extends-implements/input.ts"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array ["ts"]
	loc: Object {
		filename: "typescript/class/extends-implements/input.ts"
		end: Object {
			column: 0
			line: 2
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "C"
				loc: Object {
					filename: "typescript/class/extends-implements/input.ts"
					identifierName: "C"
					end: Object {
						column: 7
						line: 1
					}
					start: Object {
						column: 6
						line: 1
					}
				}
			}
			loc: Object {
				filename: "typescript/class/extends-implements/input.ts"
				end: Object {
					column: 43
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			meta: JSClassHead {
				body: Array []
				typeParameters: undefined
				loc: Object {
					filename: "typescript/class/extends-implements/input.ts"
					end: Object {
						column: 43
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				superClass: JSCallExpression {
					arguments: Array []
					loc: Object {
						filename: "typescript/class/extends-implements/input.ts"
						end: Object {
							column: 19
							line: 1
						}
						start: Object {
							column: 16
							line: 1
						}
					}
					callee: JSReferenceIdentifier {
						name: "f"
						loc: Object {
							filename: "typescript/class/extends-implements/input.ts"
							identifierName: "f"
							end: Object {
								column: 17
								line: 1
							}
							start: Object {
								column: 16
								line: 1
							}
						}
					}
				}
				superTypeParameters: TSTypeParameterInstantiation {
					loc: Object {
						filename: "typescript/class/extends-implements/input.ts"
						end: Object {
							column: 22
							line: 1
						}
						start: Object {
							column: 19
							line: 1
						}
					}
					params: Array [
						TSTypeReference {
							typeParameters: undefined
							loc: Object {
								filename: "typescript/class/extends-implements/input.ts"
								end: Object {
									column: 21
									line: 1
								}
								start: Object {
									column: 20
									line: 1
								}
							}
							typeName: JSReferenceIdentifier {
								name: "T"
								loc: Object {
									filename: "typescript/class/extends-implements/input.ts"
									identifierName: "T"
									end: Object {
										column: 21
										line: 1
									}
									start: Object {
										column: 20
										line: 1
									}
								}
							}
						}
					]
				}
				implements: Array [
					TSExpressionWithTypeArguments {
						loc: Object {
							filename: "typescript/class/extends-implements/input.ts"
							end: Object {
								column: 40
								line: 1
							}
							start: Object {
								column: 34
								line: 1
							}
						}
						expression: TSQualifiedName {
							loc: Object {
								filename: "typescript/class/extends-implements/input.ts"
								end: Object {
									column: 37
									line: 1
								}
								start: Object {
									column: 34
									line: 1
								}
							}
							left: JSReferenceIdentifier {
								name: "X"
								loc: Object {
									filename: "typescript/class/extends-implements/input.ts"
									identifierName: "X"
									end: Object {
										column: 35
										line: 1
									}
									start: Object {
										column: 34
										line: 1
									}
								}
							}
							right: JSIdentifier {
								name: "Y"
								loc: Object {
									filename: "typescript/class/extends-implements/input.ts"
									identifierName: "Y"
									end: Object {
										column: 37
										line: 1
									}
									start: Object {
										column: 36
										line: 1
									}
								}
							}
						}
						typeParameters: TSTypeParameterInstantiation {
							loc: Object {
								filename: "typescript/class/extends-implements/input.ts"
								end: Object {
									column: 40
									line: 1
								}
								start: Object {
									column: 37
									line: 1
								}
							}
							params: Array [
								TSTypeReference {
									typeParameters: undefined
									loc: Object {
										filename: "typescript/class/extends-implements/input.ts"
										end: Object {
											column: 39
											line: 1
										}
										start: Object {
											column: 38
											line: 1
										}
									}
									typeName: JSReferenceIdentifier {
										name: "T"
										loc: Object {
											filename: "typescript/class/extends-implements/input.ts"
											identifierName: "T"
											end: Object {
												column: 39
												line: 1
											}
											start: Object {
												column: 38
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
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```
