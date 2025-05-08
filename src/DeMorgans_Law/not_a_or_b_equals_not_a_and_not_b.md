## DeMorgan's Law - NOT of OR

# **`NOT (A OR B) equals (NOT A) AND (NOT B)`**

---

### Boolean Expression

# **`!(A + B) = !A · !B`**

## if A = 0, B = 0

# **`!(0 + 0) = !0 · !0 → 1 = 1`**

## if A = 1, B = 0

# **`!(1 + 0) = !1 · !0 → 0 = 0`**

---

```javascript
!(A || B) === (!A && !B)
```

---

```javascript
let A = true;
let B = false;
console.log(!(A || B) === (!A && !B)); // true

A = false;
B = false;
console.log(!(A || B) === (!A && !B)); // true
```

---

```javascript
function not_or_equals_and_not(A, B)
{
    return !(A || B) === (!A && !B);
}
```

---

//----//

// Dedicated to God the Father  
// All Rights Reserved  Christopher Andrew Topalian Copyright 2000-2025  
// https://github.com/ChristopherTopalian  
// https://github.com/ChristopherAndrewTopalian  
// https://sites.google.com/view/CollegeOfScripting

