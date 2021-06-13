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

const d: string[] = ['Aibol', 'Zhanerke', 'Erlan', 'Azamat'];

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
```
