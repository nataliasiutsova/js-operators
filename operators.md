## Basic Math operators

1. binary \+

```
console.log(1+2); //3
console.log('user'+'Name';); //userName
console.log(1+'2'); //'12'
```

2. unary \+

```
//No effect on numbers
let x=1;
console.log(+x); //1

// Converts non-numbers
console.log(+'2'); //2
console.log(+true); //1
console.log(+''); //0
```

3. unary and binary \-

```
let a=1;
a=-a;
console.log(a); //-1

let s=5,d=3;
console.log(s-d); //2
```

4. Multiplication \*
5. Division \/
6. Remainder \%

`console.log(5%2); //1`

7. Exponentiation \*\*

`console.log(2**2); //4`

8. Assignment \=

```
let y=2*3+1;
console.log(y); //7
```

9. Increment \+\+

```
let counter=2;
counter++;
console.log(counter); //3
```

10. Decrement \-\-

```
let counter=2;
counter--;
console.log(counter); //1
```

## Comparisons

1. Greater\/less than \>,\<

```
console.log(2>1); //true
console.log('Z'<'A'); //false
console.log('5'<6); //true
```

2. Greater/less than or equals \>\=,\<\=
3. Equals \=\=

```
console.log(2==1); //false
console.log(true==1); //true
```

4. Not equals \!\=

`console.log(false!=0); //false`

5.  Strict equality \=\=\=

`console.log(0===false); //false`

6. Strict non-equality \!\=\=

## Logical operators

1. \|\| (OR)

` console.log(null||0||1); //1`

2. \&\& (AND)

```
console.log(1&&5); //5
console.log(null&&5);//5
```

3. \! (NOT)

```
console.log(!true); //false
console.log(!0); //true
```

> При динамической типизации данных переменная принимает тип в момент
> присвоения ей значения, а не в момент ее объявления(т.е мы один тип
> данных можем превратить в другой тип данных)

```
let pens='10';
console.log(typeof (pens)); //string
console.log(typeof(+pens)); //number
console.log(pens); //10
```
