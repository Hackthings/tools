# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > export > export-type-declaration`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: true
	directives: Array []
	filename: "typescript/export/export-type-declaration/input.ts"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array ["ts"]
	loc: Object {
		filename: "typescript/export/export-type-declaration/input.ts"
		end: Object {
			column: 0
			line: 5
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	diagnostics: Array [
		Object {
			origins: Array [Object {category: "parse/js"}]
			description: Object {
				advice: Array []
				category: "parse/js"
				message: MARKUP {
					parts: Array [
						RAW_MARKUP {value: "Unexpected token, expected "}
						"("
					]
				}
			}
			location: Object {
				filename: "typescript/export/export-type-declaration/input.ts"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 25
					line: 3
				}
				start: Object {
					column: 24
					line: 3
				}
			}
		}
	]
	body: Array [
		JSExportLocalDeclaration {
			exportKind: "type"
			specifiers: undefined
			loc: Object {
				filename: "typescript/export/export-type-declaration/input.ts"
				end: Object {
					column: 18
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			declaration: TSTypeAlias {
				id: JSBindingIdentifier {
					name: "A"
					loc: Object {
						filename: "typescript/export/export-type-declaration/input.ts"
						identifierName: "A"
						end: Object {
							column: 13
							line: 1
						}
						start: Object {
							column: 12
							line: 1
						}
					}
				}
				typeParameters: undefined
				loc: Object {
					filename: "typescript/export/export-type-declaration/input.ts"
					end: Object {
						column: 18
						line: 1
					}
					start: Object {
						column: 7
						line: 1
					}
				}
				right: TSNumericLiteralTypeAnnotation {
					value: 2
					format: undefined
					loc: Object {
						filename: "typescript/export/export-type-declaration/input.ts"
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
		}
		JSExportLocalDeclaration {
			exportKind: "type"
			specifiers: undefined
			loc: Object {
				filename: "typescript/export/export-type-declaration/input.ts"
				end: Object {
					column: 21
					line: 2
				}
				start: Object {
					column: 0
					line: 2
				}
			}
			declaration: TSInterfaceDeclaration {
				id: JSBindingIdentifier {
					name: "B"
					loc: Object {
						filename: "typescript/export/export-type-declaration/input.ts"
						identifierName: "B"
						end: Object {
							column: 18
							line: 2
						}
						start: Object {
							column: 17
							line: 2
						}
					}
				}
				extends: undefined
				typeParameters: undefined
				loc: Object {
					filename: "typescript/export/export-type-declaration/input.ts"
					end: Object {
						column: 21
						line: 2
					}
					start: Object {
						column: 7
						line: 2
					}
				}
				body: TSInterfaceBody {
					body: Array []
					loc: Object {
						filename: "typescript/export/export-type-declaration/input.ts"
						end: Object {
							column: 21
							line: 2
						}
						start: Object {
							column: 19
							line: 2
						}
					}
				}
			}
		}
		JSExportLocalDeclaration {
			exportKind: "value"
			specifiers: undefined
			loc: Object {
				filename: "typescript/export/export-type-declaration/input.ts"
				end: Object {
					column: 29
					line: 4
				}
				start: Object {
					column: 0
					line: 3
				}
			}
			declaration: JSFunctionDeclaration {
				id: JSBindingIdentifier {
					name: "function"
					loc: Object {
						filename: "typescript/export/export-type-declaration/input.ts"
						identifierName: "function"
						end: Object {
							column: 23
							line: 3
						}
						start: Object {
							column: 15
							line: 3
						}
					}
				}
				declare: true
				loc: Object {
					filename: "typescript/export/export-type-declaration/input.ts"
					end: Object {
						column: 29
						line: 4
					}
					start: Object {
						column: 7
						line: 3
					}
				}
				head: JSFunctionHead {
					async: false
					generator: false
					hasHoistedVars: true
					rest: undefined
					returnType: undefined
					thisType: undefined
					typeParameters: undefined
					loc: Object {
						filename: "typescript/export/export-type-declaration/input.ts"
						end: Object {
							column: 25
							line: 3
						}
						start: Object {
							column: 24
							line: 3
						}
					}
					params: Array [
						JSBindingIdentifier {
							name: "a"
							loc: Object {
								filename: "typescript/export/export-type-declaration/input.ts"
								identifierName: "a"
								end: Object {
									column: 25
									line: 3
								}
								start: Object {
									column: 24
									line: 3
								}
							}
							meta: JSPatternMeta {
								optional: undefined
								typeAnnotation: undefined
								loc: Object {
									filename: "typescript/export/export-type-declaration/input.ts"
									end: Object {
										column: 25
										line: 3
									}
									start: Object {
										column: 24
										line: 3
									}
								}
							}
						}
					]
				}
				body: JSBlockStatement {
					directives: Array []
					loc: Object {
						filename: "typescript/export/export-type-declaration/input.ts"
						end: Object {
							column: 29
							line: 4
						}
						start: Object {
							column: 25
							line: 3
						}
					}
					body: Array [
						JSExpressionStatement {
							loc: Object {
								filename: "typescript/export/export-type-declaration/input.ts"
								end: Object {
									column: 27
									line: 3
								}
								start: Object {
									column: 25
									line: 3
								}
							}
							expression: JSReferenceIdentifier {
								name: "INVALID_PLACEHOLDER"
								loc: Object {
									filename: "typescript/export/export-type-declaration/input.ts"
									end: Object {
										column: 26
										line: 3
									}
									start: Object {
										column: 26
										line: 3
									}
								}
							}
						}
						JSExpressionStatement {
							loc: Object {
								filename: "typescript/export/export-type-declaration/input.ts"
								end: Object {
									column: 28
									line: 3
								}
								start: Object {
									column: 27
									line: 3
								}
							}
							expression: JSReferenceIdentifier {
								name: "INVALID_PLACEHOLDER"
								loc: Object {
									filename: "typescript/export/export-type-declaration/input.ts"
									end: Object {
										column: 28
										line: 3
									}
									start: Object {
										column: 27
										line: 3
									}
								}
							}
						}
						JSExpressionStatement {
							loc: Object {
								filename: "typescript/export/export-type-declaration/input.ts"
								end: Object {
									column: 36
									line: 3
								}
								start: Object {
									column: 29
									line: 3
								}
							}
							expression: JSReferenceIdentifier {
								name: "string"
								loc: Object {
									filename: "typescript/export/export-type-declaration/input.ts"
									identifierName: "string"
									end: Object {
										column: 35
										line: 3
									}
									start: Object {
										column: 29
										line: 3
									}
								}
							}
						}
						JSExportLocalDeclaration {
							exportKind: "value"
							specifiers: undefined
							loc: Object {
								filename: "typescript/export/export-type-declaration/input.ts"
								end: Object {
									column: 29
									line: 4
								}
								start: Object {
									column: 0
									line: 4
								}
							}
							declaration: JSVariableDeclarationStatement {
								declare: true
								loc: Object {
									filename: "typescript/export/export-type-declaration/input.ts"
									end: Object {
										column: 29
										line: 4
									}
									start: Object {
										column: 7
										line: 4
									}
								}
								declaration: JSVariableDeclaration {
									kind: "var"
									loc: Object {
										filename: "typescript/export/export-type-declaration/input.ts"
										end: Object {
											column: 29
											line: 4
										}
										start: Object {
											column: 7
											line: 4
										}
									}
									declarations: Array [
										JSVariableDeclarator {
											id: JSBindingIdentifier {
												name: "b"
												loc: Object {
													filename: "typescript/export/export-type-declaration/input.ts"
													end: Object {
														column: 28
														line: 4
													}
													start: Object {
														column: 19
														line: 4
													}
												}
												meta: JSPatternMeta {
													definite: undefined
													loc: Object {
														filename: "typescript/export/export-type-declaration/input.ts"
														end: Object {
															column: 28
															line: 4
														}
														start: Object {
															column: 19
															line: 4
														}
													}
													typeAnnotation: TSStringKeywordTypeAnnotation {
														loc: Object {
															filename: "typescript/export/export-type-declaration/input.ts"
															end: Object {
																column: 28
																line: 4
															}
															start: Object {
																column: 22
																line: 4
															}
														}
													}
												}
											}
											init: undefined
											loc: Object {
												filename: "typescript/export/export-type-declaration/input.ts"
												end: Object {
													column: 28
													line: 4
												}
												start: Object {
													column: 19
													line: 4
												}
											}
										}
									]
								}
							}
						}
					]
				}
			}
		}
	]
}
```

### `diagnostics`

```

 typescript/export/export-type-declaration/input.ts:3:24 parse/js ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Unexpected token, expected (

    1 │ export type A = 2;
    2 │ export interface B {}
  > 3 │ export declare function a(): string;
      │                         ^
    4 │ export declare var b: string;

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```