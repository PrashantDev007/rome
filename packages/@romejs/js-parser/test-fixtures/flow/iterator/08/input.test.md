# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > iterator > 08`

```javascript
Program {
  comments: Array []
  corrupt: false
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'module'
  syntax: Array [
    'jsx'
    'flow'
  ]
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 30
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  diagnostics: Array [
    Object {
      origins: Array [Object {category: 'js-parser'}]
      description: Object {
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Invalid identifier @@asyncIterator'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'module'
        end: Object {
          column: 4
          index: 4
          line: 1
        }
        start: Object {
          column: 5
          index: 5
          line: 1
        }
      }
    }
  ]
  body: Array [
    TypeAliasTypeAnnotation {
      id: BindingIdentifier {
        name: '@@asyncIterator'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 20
            index: 20
            line: 1
          }
          start: Object {
            column: 5
            index: 5
            line: 1
          }
        }
      }
      typeParameters: undefined
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 29
          index: 29
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      right: NumberKeywordTypeAnnotation {
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 29
            index: 29
            line: 1
          }
          start: Object {
            column: 23
            index: 23
            line: 1
          }
        }
      }
    }
  ]
}
```