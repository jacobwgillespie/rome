# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > identifiers > invalid-escape-seq-const`

```javascript
Program {
  comments: Array []
  corrupt: false
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: true
  interpreter: undefined
  mtime: undefined
  sourceType: 'script'
  syntax: Array []
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 22
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
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Escape sequence in keyword const'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 6
          index: 6
          line: 1
        }
        start: Object {
          column: 6
          index: 6
          line: 1
        }
      }
    }
  ]
  body: Array [
    VariableDeclarationStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 21
          index: 21
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      declaration: VariableDeclaration {
        kind: 'var'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 21
            index: 21
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        declarations: Array [
          VariableDeclarator {
            id: BindingIdentifier {
              name: 'const'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 14
                  index: 14
                  line: 1
                }
                start: Object {
                  column: 4
                  index: 4
                  line: 1
                }
              }
            }
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 20
                index: 20
                line: 1
              }
              start: Object {
                column: 4
                index: 4
                line: 1
              }
            }
            init: NumericLiteral {
              value: 123
              format: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 20
                  index: 20
                  line: 1
                }
                start: Object {
                  column: 17
                  index: 17
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
```