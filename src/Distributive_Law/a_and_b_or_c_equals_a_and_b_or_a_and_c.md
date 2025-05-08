## Distributive Law - AND over OR

# **`A AND (B OR C) equals (A AND B) OR (A AND C)`**

---

### Boolean Expression

# **`A · (B + C) = (A · B) + (A · C)`**

## if A = 0, B = 1, C = 1

# **`0 · (1 + 1) = (0 · 1) + (0 · 1)` → 0 = 0\`**

## if A = 1, B = 1, C = 0

# **`1 · (1 + 0) = (1 · 1) + (1 · 0)` → 1 = 1\`**

---

```javascript
A && (B || C) === (A && B) || (A && C)
```

---

```javascript
let A = true;
let B = false;
let C = true;
console.log(A && (B || C) === (A && B) || (A && C)); // true

A = false;
B = true;
C = true;
console.log(A && (B || C) === (A && B) || (A && C)); // true
```

---

```javascript
function distributive_and(A, B, C)
{
    return (A && (B || C)) === ((A && B) || (A && C));
}
```

---

//----//

// Dedicated to God the Father  
// All Rights Reserved  Christopher Andrew Topalian Copyright 2000-2025  
// https://github.com/ChristopherTopalian  
// https://github.com/ChristopherAndrewTopalian  
// https://sites.google.com/view/CollegeOfScripting

