## 6: Configuring the TypeScript Compiler.

npx tsc -> May bring an error, typescript config error
npx tsc with-typescript (was a potential solution)

You want to mind how the TS complier behaves

npx tsc --init (adds a TS config json file, but with Angular, that TS config file is out the box. DO NOT change unless you know what you are doing!)

"Strict mode" is set to true, by default