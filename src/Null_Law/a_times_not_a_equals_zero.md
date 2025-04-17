# Null Law  
# **`A AND NOT A equals 0`**

---

### Boolean Expression  
# **`A * !A = 0`**

## if A = 0  
# **`0 * !0 = 0`**

## if A = 1  
# **`1 * !1 = 0`**

---

```javascript
Number(A) * Number(!A) === 0
```

---

```javascript
let A = true;
console.log(Number(A) * Number(!A) === 0); // true

A = false;
console.log(Number(A) * Number(!A) === 0); // true
```

---

```javascript
function a_times_not_a_equals_0(A)
{
    return Number(A) * Number(!A) === 0;
}
```


//----//

// Dedicated to God the Father  
// All Rights Reserved  Christopher Andrew Topalian Copyright 2000-2025  
// https://github.com/ChristopherTopalian  
// https://github.com/ChristopherAndrewTopalian  
// https://sites.google.com/view/CollegeOfScripting

