# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > type-annotations > 31`

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
      column: 32
      index: 32
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
          column: 32
          index: 32
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
            column: 32
            index: 32
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
              name: 'numVal'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 17
                  index: 17
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
                    column: 17
                    index: 17
                    line: 1
                  }
                  start: Object {
                    column: 4
                    index: 4
                    line: 1
                  }
                }
                typeAnnotation: NumberKeywordTypeAnnotation {
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 17
                      index: 17
                      line: 1
                    }
                    start: Object {
                      column: 11
                      index: 11
                      line: 1
                    }
                  }
                }
              }
            }
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 31
                index: 31
                line: 1
              }
              start: Object {
                column: 4
                index: 4
                line: 1
              }
            }
            init: ReferenceIdentifier {
              name: 'otherNumVal'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 31
                  index: 31
                  line: 1
                }
                start: Object {
                  column: 20
                  index: 20
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