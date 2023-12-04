> # Lecture 12
>
> ![](./1_moJeTvW97yShLB7URRj5Kg.png)
>
> # Table of content;

## 1.Introducing TypeScript

## 2.difference TS and JS

## 3.TS Data Types and Functions

## 4.Interfaces in TS

> # What is Type script?

## type script sboni updateshudai js ast ki mo metavonem dar type script hama variablehoe ki menavisem dar nazdi onho type onhoro niz navisem typescript soli 2012 az tarafi micrasoft peshkash shudaast; tahiagari typescript Anders Hejlsberg ast; agar projecti shumo khurd boshad typescrpt-ro istifoda nabared; TypeScript extends JavaScript and improves the developer experience. It enables developers to add type safety to their projects.

> # how to install ts?

## first istall : npm install -g typescript; after check the version of ts : tsc -v; after install node of ts: npm i -g ts-node; you can run your ts file : ts-node main.ts;

> # type in type script?

## type dar type script ba 2 guruh gudo meshavad : primitive and number;

>## Primitive :

## 1.number : type( number );

```
let a: number = 6
log.a ----> 6
```

## 2.string : type( sting );

```
let a: string = "Hello"
log.a ---> hello
```

## 3.boolean : type( boolean : true or false )

```
let a: boolean = true
log.a --->true
```

## 4.voin : funksiai be return voin kabul meknad

```
function main(name : string): void {
    log."Hello
}
```

## 5.null;

## 6.underfined;

## 7.never : that never work

```
function main(a: number): never {
    throw new Error(a)
}
```

## any : dont use any;

>## Object;
## 1.array : type array thn can hold some value and can not hold different value
```
let arr: number[] = [1,2,3,4,5]
log.arr ---> [1,2,3,4,5]
```
## 2.class;
## 3.interface;
```
interface user {
    id : number,
    name : string
}
let newUser: user = {
    id : 2,
    name : "John",
}
```
## 4.tuple;
## 5.enum;
## 6.function
```
function(n: number) returnType {
    ///...
}
```
>## passing the object type : 
```
function get(user : { id : number , name : string}): void{
    log.user.name
}
get({id: 1,name : "Bilol}) ---> Bilol;
```