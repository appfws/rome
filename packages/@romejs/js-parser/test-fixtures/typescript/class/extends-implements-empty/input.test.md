# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > class > extends-implements-empty`

```javascript
Program {
  comments: Array []
  corrupt: false
  directives: Array []
  filename: 'input.ts'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'module'
  syntax: Array ['ts']
  loc: Object {
    filename: 'input.ts'
    end: Object {
      column: 0
      index: 37
      line: 3
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
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'implements list cannot be empty'}
      }
      location: Object {
        filename: 'input.ts'
        mtime: undefined
        sourceType: 'module'
        end: Object {
          column: 33
          index: 33
          line: 1
        }
        start: Object {
          column: 33
          index: 33
          line: 1
        }
      }
    }
  ]
  body: Array [
    ClassDeclaration {
      id: BindingIdentifier {
        name: 'Foo'
        loc: Object {
          filename: 'input.ts'
          end: Object {
            column: 9
            index: 9
            line: 1
          }
          start: Object {
            column: 6
            index: 6
            line: 1
          }
        }
      }
      loc: Object {
        filename: 'input.ts'
        end: Object {
          column: 1
          index: 36
          line: 2
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      meta: ClassHead {
        body: Array []
        implements: Array []
        superTypeParameters: undefined
        typeParameters: undefined
        loc: Object {
          filename: 'input.ts'
          end: Object {
            column: 1
            index: 36
            line: 2
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        superClass: ReferenceIdentifier {
          name: 'Bar'
          loc: Object {
            filename: 'input.ts'
            end: Object {
              column: 21
              index: 21
              line: 1
            }
            start: Object {
              column: 18
              index: 18
              line: 1
            }
          }
        }
      }
    }
  ]
}
```