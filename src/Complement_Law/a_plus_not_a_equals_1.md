# Complement Law
# **`A OR NOT A equals 1`**

---

### Boolean Expression  
# **`A + !A = 1`**

## if A = 0  
# **`0 + !0 = 1`**

## if A = 1
# **`1 + !1 = 1`**

---

```javascript
Number(A) + Number(!A) === 1
```

---

```javascript
let A = true;
console.log(Number(A) + Number(!A) === 1); // true

A = false;
console.log(Number(A) + Number(!A) === 1); // true
```

---

```javascript
function a_plus_not_a_equals_1(A)
{
    return Number(A) + Number(!A);
}
```

---

//----//

// Dedicated to God the Father  
// All Rights Reserved  Christopher Andrew Topalian Copyright 2000-2025  
// https://github.com/ChristopherTopalian  
// https://github.com/ChristopherAndrewTopalian  
// https://sites.google.com/view/CollegeOfScripting

