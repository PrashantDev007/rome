# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2017 > trailing-function-commas > 5`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: true
	directives: Array []
	filename: "es2017/trailing-function-commas/5/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2017/trailing-function-commas/5/input.js"
		end: Object {
			column: 7
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
				message: MARKUP {
					parts: Array [
						RAW_MARKUP {value: "Unknown start to an "}
						"call expression argument"
					]
				}
			}
			location: Object {
				filename: "es2017/trailing-function-commas/5/input.js"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 4
					line: 1
				}
				start: Object {
					column: 4
					line: 1
				}
			}
		}
	]
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "es2017/trailing-function-commas/5/input.js"
				end: Object {
					column: 7
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSCallExpression {
				loc: Object {
					filename: "es2017/trailing-function-commas/5/input.js"
					end: Object {
						column: 6
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				callee: JSReferenceIdentifier {
					name: "log"
					loc: Object {
						filename: "es2017/trailing-function-commas/5/input.js"
						identifierName: "log"
						end: Object {
							column: 3
							line: 1
						}
						start: Object {
							column: 0
							line: 1
						}
					}
				}
				arguments: Array [
					JSReferenceIdentifier {
						name: "INVALID_PLACEHOLDER"
						loc: Object {
							filename: "es2017/trailing-function-commas/5/input.js"
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
	]
}
```

### `diagnostics`

```

 es2017/trailing-function-commas/5/input.js:1:4 parse/js ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Unknown start to an call expression argument

    log(,);
        ^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```
