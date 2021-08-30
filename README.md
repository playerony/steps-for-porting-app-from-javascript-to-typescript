# Steps for porting an application from javascript to typescript

# 1. Change file extensions and fixing broken tests

- ### Rename *.js to *.ts, allowing implicit any,
- ### Fix only things that are not type-checking, or causing compile errors,
- ### Get tests passing again,

# 2. Explicit any

- ### "noImplicitAny": true,
- ### Where possible, provide a specific and appropriate type,
- ### Get tests passing again,

# 3. Enable strict mode

- ### "strict": true,
- ### "strictNullChecks": true,
- ### "strictFunctionTypes": true,
- ### "strictBindCallApply": true,
- ### "strictPropertyInitialization": true,
- ### Replace explicit anys with more appropriate types,
- ### Try to avoid unsafe casts,
