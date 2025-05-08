## DeMorgan's Law - NOT of AND

# **`NOT (A AND B) equals (NOT A) OR (NOT B)`**

---

### Boolean Expression

# **`!(A · B) = !A + !B`**

## if A = 1, B = 1

# **`!(1 · 1) = !1 + !1 → 0 = 0`**

## if A = 1, B = 0

# **`!(1 · 0) = !1 + !0 → 1 = 1`**

---

```javascript
!(A && B) === (!A || !B)
```

---

```javascript
let A = true;
let B = true;
console.log(!(A && B) === (!A || !B)); // true

A = true;
B = false;
console.log(!(A && B) === (!A || !B)); // true
```

---

```javascript
function not_and_equals_or_not(A, B)
{
    return !(A && B) === (!A || !B);
}
```

---

//----//

// Dedicated to God the Father  
// All Rights Reserved  Christopher Andrew Topalian Copyright 2000-2025  
// https://github.com/ChristopherTopalian  
// https://github.com/ChristopherAndrewTopalian  
// https://sites.google.com/view/CollegeOfScripting

