importance: 2

---

# Dua fungsi – satu objek

<<<<<<< HEAD
Apakah mungkin untuk membuat fungsi `A` dan fungsi `B` seperti `new A()==new B()`?
=======
Is it possible to create functions `A` and `B` so that `new A() == new B()`?
>>>>>>> c5358c59494b53efb832c81a5338e0a23b22c269

```js no-beautify
function A() { ... }
function B() { ... }

let a = new A;
let b = new B;

alert( a == b ); // true
```

Jika bisa, berikan contoh kodenya.
