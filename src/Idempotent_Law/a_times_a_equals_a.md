# Idempotent Law  
# **`A AND A equals A`**

---

### Boolean Expression  
# **`A * A = A`**

## if A = 0  
# **`0 * 0 = 0`**

## if A = 1  
# **`1 * 1 = 1`**

---

```javascript
Number(A) * Number(A) === Number(A)
```

---

```javascript
let A = true;
console.log(Number(A) * Number(A) === Number(A)); // true

A = false;
console.log(Number(A) * Number(A) === Number(A)); // true
```

---

```javascript
function a_times_a_equals_a(A)
{
    return Number(A) * Number(A) === Number(A);
}
```

---

//----//

// Dedicated to God the Father  
// All Rights Reserved  Christopher Andrew Topalian Copyright 2000-2025  
// https://github.com/ChristopherTopalian  
// https://github.com/ChristopherAndrewTopalian  
// https://sites.google.com/view/CollegeOfScripting

