# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > type-annotations > 84`

```javascript
Program {
  comments: Array []
  corrupt: false
  diagnostics: Array []
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: true
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
      column: 16
      index: 16
      line: 1
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    VariableDeclarationStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 16
          index: 16
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
            column: 16
            index: 16
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
              name: 'a'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 16
                  index: 16
                  line: 1
                }
                start: Object {
                  column: 4
                  index: 4
                  line: 1
                }
              }
              meta: PatternMeta {
                definite: undefined
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 16
                    index: 16
                    line: 1
                  }
                  start: Object {
                    column: 4
                    index: 4
                    line: 1
                  }
                }
                typeAnnotation: FlowNullableTypeAnnotation {
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 16
                      index: 16
                      line: 1
                    }
                    start: Object {
                      column: 7
                      index: 7
                      line: 1
                    }
                  }
                  typeAnnotation: FlowArrayTypeAnnotation {
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 16
                        index: 16
                        line: 1
                      }
                      start: Object {
                        column: 8
                        index: 8
                        line: 1
                      }
                    }
                    elementType: StringKeywordTypeAnnotation {
                      loc: Object {
                        filename: 'input.js'
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
                    }
                  }
                }
              }
            }
            init: undefined
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 16
                index: 16
                line: 1
              }
              start: Object {
                column: 4
                index: 4
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