# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > variable-declarator > definite-assignment-not-allowed`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: true
	directives: Array []
	filename: "typescript/variable-declarator/definite-assignment-not-allowed/input.ts"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array ["ts"]
	loc: Object {
		filename: "typescript/variable-declarator/definite-assignment-not-allowed/input.ts"
		end: Object {
			column: 13
			line: 1
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
				message: MARKUP {parts: Array [RAW_MARKUP {value: "Complex binding patterns require an initialization value"}]}
			}
			location: Object {
				filename: "typescript/variable-declarator/definite-assignment-not-allowed/input.ts"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 6
					line: 1
				}
				start: Object {
					column: 6
					line: 1
				}
			}
		}
	]
	body: Array [
		JSVariableDeclarationStatement {
			loc: Object {
				filename: "typescript/variable-declarator/definite-assignment-not-allowed/input.ts"
				end: Object {
					column: 6
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			declaration: JSVariableDeclaration {
				kind: "let"
				loc: Object {
					filename: "typescript/variable-declarator/definite-assignment-not-allowed/input.ts"
					end: Object {
						column: 6
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				declarations: Array [
					JSVariableDeclarator {
						id: JSBindingObjectPattern {
							properties: Array []
							rest: undefined
							loc: Object {
								filename: "typescript/variable-declarator/definite-assignment-not-allowed/input.ts"
								end: Object {
									column: 6
									line: 1
								}
								start: Object {
									column: 4
									line: 1
								}
							}
						}
						init: undefined
						loc: Object {
							filename: "typescript/variable-declarator/definite-assignment-not-allowed/input.ts"
							end: Object {
								column: 6
								line: 1
							}
							start: Object {
								column: 4
								line: 1
							}
						}
					}
				]
			}
		}
		JSExpressionStatement {
			loc: Object {
				filename: "typescript/variable-declarator/definite-assignment-not-allowed/input.ts"
				end: Object {
					column: 9
					line: 1
				}
				start: Object {
					column: 6
					line: 1
				}
			}
			expression: JSUnaryExpression {
				operator: "!"
				prefix: true
				loc: Object {
					filename: "typescript/variable-declarator/definite-assignment-not-allowed/input.ts"
					end: Object {
						column: 9
						line: 1
					}
					start: Object {
						column: 6
						line: 1
					}
				}
				argument: JSReferenceIdentifier {
					name: "INVALID_PLACEHOLDER"
					loc: Object {
						filename: "typescript/variable-declarator/definite-assignment-not-allowed/input.ts"
						end: Object {
							column: 9
							line: 1
						}
						start: Object {
							column: 8
							line: 1
						}
					}
				}
			}
		}
		JSBlockStatement {
			body: Array []
			directives: Array []
			loc: Object {
				filename: "typescript/variable-declarator/definite-assignment-not-allowed/input.ts"
				end: Object {
					column: 12
					line: 1
				}
				start: Object {
					column: 10
					line: 1
				}
			}
		}
		JSEmptyStatement {
			loc: Object {
				filename: "typescript/variable-declarator/definite-assignment-not-allowed/input.ts"
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
	]
}
```

### `diagnostics`

```

 typescript/variable-declarator/definite-assignment-not-allowed/input.ts:1:6 parse/js ━━━━━━━━━━━━━━

  ✖ Complex binding patterns require an initialization value

    let {}! = {};
          ^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```
