## Absorption Law
# **`A AND (A OR B) equals A`**

---

### Boolean Expression

# **`A · (A + B) = A`**

## if A = 0, B = 1

# **`0 · (0 + 1) = 0`**

## if A = 1, B = 0

# **`1 · (1 + 0) = 1`**

## if A = 1, B = 1

# **`1 · (1 + 1) = 1`**

---

```javascript
A && (A || B) === A
```

---

```javascript
let A = true;
let B = false;
console.log(A && (A || B) === A); // true

A = false;
B = true;
console.log(A && (A || B) === A); // true
```

---

```javascript
function absorption_and(A, B)
{
    return A && (A || B);
}
```

---

//----//

// Dedicated to God the Father  
// All Rights Reserved  Christopher Andrew Topalian Copyright 2000-2025  
// https://github.com/ChristopherTopalian  
// https://github.com/ChristopherAndrewTopalian  
// https://sites.google.com/view/CollegeOfScripting

