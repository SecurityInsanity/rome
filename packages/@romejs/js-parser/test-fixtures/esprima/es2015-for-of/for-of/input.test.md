# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-for-of > for-of`

```javascript
Program {
  comments: Array []
  corrupt: false
  diagnostics: Array []
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'script'
  syntax: Array []
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 14
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    ForOfStatement {
      await: false
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 13
          index: 13
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      body: EmptyStatement {
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 13
            index: 13
            line: 1
          }
          start: Object {
            column: 12
            index: 12
            line: 1
          }
        }
      }
      left: AssignmentIdentifier {
        name: 'p'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 6
            index: 6
            line: 1
          }
          start: Object {
            column: 5
            index: 5
            line: 1
          }
        }
      }
      right: ReferenceIdentifier {
        name: 'q'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 11
            index: 11
            line: 1
          }
          start: Object {
            column: 10
            index: 10
            line: 1
          }
        }
      }
    }
  ]
}
```