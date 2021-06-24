# Установка TypeScript
```
npm i -g typescript
```
# Инициализация TypeScript Compiler
```
tsc --init
```
# Типизация переменных
```
let a: number = 42;
let b: string = 'Aibol';
let c: boolean = true;

let d: string[] = ['Aibol', 'Zhanerke', 'Erlan', 'Azamat'];

d = d.map((x: string) => x.toUpperCase())

let e: any = 'Zhanerke';
e = 21;
```
# Типизация функций
```
function test(a: string): string | number {
   return 'hello'
}

const test = (a: number): number => {
   return a * 2
}

function test(a: string){
   console.log(a.toUpperCase())
}

function test(a: string | number){
   if(typeof a === 'string'){
      ......
   } else if(typeof a === 'number'){
      ......
   }
}

```
