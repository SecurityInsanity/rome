# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `es2018 > regexp-named-capture-group > 4`

```javascript
Program {
  comments: Array []
  corrupt: false
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
      column: 45
      index: 45
      line: 1
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
        category: 'parse/regex'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Invalid named capture referenced'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 38
          index: 38
          line: 1
        }
        start: Object {
          column: 31
          index: 31
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
          column: 45
          index: 45
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      declaration: VariableDeclaration {
        kind: 'let'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 45
            index: 45
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
              name: 'triplicate'
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
                column: 44
                index: 44
                line: 1
              }
              start: Object {
                column: 4
                index: 4
                line: 1
              }
            }
            init: RegExpLiteral {
              global: false
              insensitive: false
              multiline: false
              noDotNewline: false
              sticky: false
              unicode: true
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 44
                  index: 44
                  line: 1
                }
                start: Object {
                  column: 17
                  index: 17
                  line: 1
                }
              }
              expression: RegExpSubExpression {
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 42
                    index: 42
                    line: 1
                  }
                  start: Object {
                    column: 18
                    index: 18
                    line: 1
                  }
                }
                body: Array [
                  RegExpStartCharacter {
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 19
                        index: 19
                        line: 1
                      }
                      start: Object {
                        column: 18
                        index: 18
                        line: 1
                      }
                    }
                  }
                  RegExpGroupCapture {
                    name: 'part'
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 30
                        index: 30
                        line: 1
                      }
                      start: Object {
                        column: 19
                        index: 19
                        line: 1
                      }
                    }
                    expression: RegExpSubExpression {
                      loc: Object {
                        filename: 'input.js'
                        end: Object {
                          column: 29
                          index: 29
                          line: 1
                        }
                        start: Object {
                          column: 27
                          index: 27
                          line: 1
                        }
                      }
                      body: Array [
                        RegExpQuantified {
                          lazy: false
                          max: undefined
                          min: 0
                          loc: Object {
                            filename: 'input.js'
                            end: Object {
                              column: 29
                              index: 29
                              line: 1
                            }
                            start: Object {
                              column: 27
                              index: 27
                              line: 1
                            }
                          }
                          target: RegExpAnyCharacter {
                            loc: Object {
                              filename: 'input.js'
                              end: Object {
                                column: 28
                                index: 28
                                line: 1
                              }
                              start: Object {
                                column: 27
                                index: 27
                                line: 1
                              }
                            }
                          }
                        }
                      ]
                    }
                  }
                  RegExpAnyCharacter {
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 31
                        index: 31
                        line: 1
                      }
                      start: Object {
                        column: 30
                        index: 30
                        line: 1
                      }
                    }
                  }
                  RegExpNamedBackReference {
                    name: 'par'
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 38
                        index: 38
                        line: 1
                      }
                      start: Object {
                        column: 31
                        index: 31
                        line: 1
                      }
                    }
                  }
                  RegExpAnyCharacter {
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 39
                        index: 39
                        line: 1
                      }
                      start: Object {
                        column: 38
                        index: 38
                        line: 1
                      }
                    }
                  }
                  RegExpCharacter {
                    value: '\x01'
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 41
                        index: 41
                        line: 1
                      }
                      start: Object {
                        column: 39
                        index: 39
                        line: 1
                      }
                    }
                  }
                  RegExpEndCharacter {
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 42
                        index: 42
                        line: 1
                      }
                      start: Object {
                        column: 41
                        index: 41
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
    }
  ]
}
```