# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > uncategorised > 62`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "es2015/uncategorised/62/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2015/uncategorised/62/input.js"
		end: Object {
			column: 15
			line: 1
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "es2015/uncategorised/62/input.js"
				end: Object {
					column: 15
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSAssignmentExpression {
				operator: "="
				loc: Object {
					filename: "es2015/uncategorised/62/input.js"
					end: Object {
						column: 15
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				right: JSArrayExpression {
					loc: Object {
						filename: "es2015/uncategorised/62/input.js"
						end: Object {
							column: 15
							line: 1
						}
						start: Object {
							column: 9
							line: 1
						}
					}
					elements: Array [
						JSReferenceIdentifier {
							name: "b"
							loc: Object {
								filename: "es2015/uncategorised/62/input.js"
								identifierName: "b"
								end: Object {
									column: 11
									line: 1
								}
								start: Object {
									column: 10
									line: 1
								}
							}
						}
						JSReferenceIdentifier {
							name: "a"
							loc: Object {
								filename: "es2015/uncategorised/62/input.js"
								identifierName: "a"
								end: Object {
									column: 14
									line: 1
								}
								start: Object {
									column: 13
									line: 1
								}
							}
						}
					]
				}
				left: JSAssignmentArrayPattern {
					rest: undefined
					loc: Object {
						filename: "es2015/uncategorised/62/input.js"
						end: Object {
							column: 6
							line: 1
						}
						start: Object {
							column: 0
							line: 1
						}
					}
					elements: Array [
						JSAssignmentIdentifier {
							name: "a"
							loc: Object {
								filename: "es2015/uncategorised/62/input.js"
								identifierName: "a"
								end: Object {
									column: 2
									line: 1
								}
								start: Object {
									column: 1
									line: 1
								}
							}
						}
						JSAssignmentIdentifier {
							name: "b"
							loc: Object {
								filename: "es2015/uncategorised/62/input.js"
								identifierName: "b"
								end: Object {
									column: 5
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
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```
