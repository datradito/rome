# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `core > regression > 2591`

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
      index: 34
      line: 5
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    FunctionDeclaration {
      id: BindingIdentifier {
        name: 'x'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 10
            index: 10
            line: 1
          }
          start: Object {
            column: 9
            index: 9
            line: 1
          }
        }
      }
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 1
          index: 33
          line: 4
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      head: FunctionHead {
        async: false
        generator: false
        hasHoistedVars: false
        params: Array []
        predicate: undefined
        rest: undefined
        returnType: undefined
        thisType: undefined
        typeParameters: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 13
            index: 13
            line: 1
          }
          start: Object {
            column: 10
            index: 10
            line: 1
          }
        }
      }
      body: BlockStatement {
        directives: Array []
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 1
            index: 33
            line: 4
          }
          start: Object {
            column: 13
            index: 13
            line: 1
          }
        }
        body: Array [
          VariableDeclarationStatement {
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 7
                index: 22
                line: 2
              }
              start: Object {
                column: 2
                index: 17
                line: 2
              }
            }
            declaration: VariableDeclaration {
              kind: 'let'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 7
                  index: 22
                  line: 2
                }
                start: Object {
                  column: 2
                  index: 17
                  line: 2
                }
              }
              declarations: Array [
                VariableDeclarator {
                  id: BindingIdentifier {
                    name: 'x'
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 7
                        index: 22
                        line: 2
                      }
                      start: Object {
                        column: 6
                        index: 21
                        line: 2
                      }
                    }
                  }
                  init: undefined
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 7
                      index: 22
                      line: 2
                    }
                    start: Object {
                      column: 6
                      index: 21
                      line: 2
                    }
                  }
                }
              ]
            }
          }
          ExpressionStatement {
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 8
                index: 31
                line: 3
              }
              start: Object {
                column: 2
                index: 25
                line: 3
              }
            }
            expression: RegExpLiteral {
              global: false
              insensitive: false
              multiline: false
              noDotNewline: false
              sticky: false
              unicode: false
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 7
                  index: 30
                  line: 3
                }
                start: Object {
                  column: 2
                  index: 25
                  line: 3
                }
              }
              expression: RegExpSubExpression {
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 6
                    index: 29
                    line: 3
                  }
                  start: Object {
                    column: 3
                    index: 26
                    line: 3
                  }
                }
                body: Array [
                  RegExpCharacter {
                    value: 'w'
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 4
                        index: 27
                        line: 3
                      }
                      start: Object {
                        column: 3
                        index: 26
                        line: 3
                      }
                    }
                  }
                  RegExpCharacter {
                    value: 'o'
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 5
                        index: 28
                        line: 3
                      }
                      start: Object {
                        column: 4
                        index: 27
                        line: 3
                      }
                    }
                  }
                  RegExpCharacter {
                    value: 'w'
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 6
                        index: 29
                        line: 3
                      }
                      start: Object {
                        column: 5
                        index: 28
                        line: 3
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
  ]
}
```