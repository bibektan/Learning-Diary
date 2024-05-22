# Day 1
- install typescript globally, `npm i typescript -g`
    - now you can use `tsc` command in terminal  

- `tsc filename.ts` will compile typescript to vanilla js
    - `-w` will watch the changes continiously  
- if typescript and compiled js is needed to be in ***different path*** then you can specify that in ***typescript config file*** which you can generate by `tsc --init`  
    - it will generate tsconfig.json, here you can specify `rootDir`, `outDir`, `target`, etc.
