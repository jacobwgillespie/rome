# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > typeapp-call > underscore_is_illegal_param_instantiation_otherwise`

```javascript
Program {
  corrupt: false
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
      column: 0
      index: 31
      line: 3
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  comments: Array [
    CommentLine {
      id: '0'
      value: '@flow'
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 7
          index: 7
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
    }
  ]
  diagnostics: Array [
    Object {
      origins: Array [Object {category: 'js-parser'}]
      description: Object {
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: '`_` is only allowed as a type argument to call or new'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'module'
        end: Object {
          column: 16
          index: 24
          line: 2
        }
        start: Object {
          column: 15
          index: 23
          line: 2
        }
      }
    }
  ]
  body: Array [
    VariableDeclarationStatement {
      leadingComments: Array ['0']
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 22
          index: 30
          line: 2
        }
        start: Object {
          column: 0
          index: 8
          line: 2
        }
      }
      declaration: VariableDeclaration {
        kind: 'var'
        leadingComments: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 22
            index: 30
            line: 2
          }
          start: Object {
            column: 0
            index: 8
            line: 2
          }
        }
        declarations: Array [
          VariableDeclarator {
            id: BindingIdentifier {
              name: 'x'
              leadingComments: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 17
                  index: 25
                  line: 2
                }
                start: Object {
                  column: 4
                  index: 12
                  line: 2
                }
              }
              meta: PatternMeta {
                definite: undefined
                leadingComments: undefined
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 17
                    index: 25
                    line: 2
                  }
                  start: Object {
                    column: 4
                    index: 12
                    line: 2
                  }
                }
                typeAnnotation: FlowGenericTypeAnnotation {
                  id: ReferenceIdentifier {
                    name: 'Generic'
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 14
                        index: 22
                        line: 2
                      }
                      start: Object {
                        column: 7
                        index: 15
                        line: 2
                      }
                    }
                  }
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 17
                      index: 25
                      line: 2
                    }
                    start: Object {
                      column: 7
                      index: 15
                      line: 2
                    }
                  }
                  typeParameters: FlowTypeParameterInstantiation {
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 17
                        index: 25
                        line: 2
                      }
                      start: Object {
                        column: 14
                        index: 22
                        line: 2
                      }
                    }
                    params: Array [
                      FlowGenericTypeAnnotation {
                        id: ReferenceIdentifier {
                          name: '_'
                          loc: Object {
                            filename: 'input.js'
                            end: Object {
                              column: 16
                              index: 24
                              line: 2
                            }
                            start: Object {
                              column: 15
                              index: 23
                              line: 2
                            }
                          }
                        }
                        typeParameters: undefined
                        loc: Object {
                          filename: 'input.js'
                          end: Object {
                            column: 16
                            index: 24
                            line: 2
                          }
                          start: Object {
                            column: 15
                            index: 23
                            line: 2
                          }
                        }
                      }
                    ]
                  }
                }
              }
            }
            leadingComments: undefined
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 21
                index: 29
                line: 2
              }
              start: Object {
                column: 4
                index: 12
                line: 2
              }
            }
            init: NumericLiteral {
              value: 3
              format: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 21
                  index: 29
                  line: 2
                }
                start: Object {
                  column: 20
                  index: 28
                  line: 2
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