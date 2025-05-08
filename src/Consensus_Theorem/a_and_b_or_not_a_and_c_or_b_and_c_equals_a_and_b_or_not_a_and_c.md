## Consensus Theorem

# **`(A AND B) OR (NOT A AND C) OR (B AND C) = (A AND B) OR (NOT A AND C)`**

The third term `(B AND C)` is **redundant** and can be removed.
This helps simplify logic circuits and code.

---

### Boolean Expression

# **`(A·B) + (!A·C) + (B·C) = (A·B) + (!A·C)`**

We'll test multiple values of A, B, and C to show both expressions give same result.

---

```javascript
function consensusTheoremLeft(A, B, C)
{
    return (A && B) || (!A && C) || (B && C);
}

function consensusTheoremRight(A, B, C)
{
    return (A && B) || (!A && C);
}
```

---

```javascript
let testCases = [
    [false, false, false],
    [false, false, true],
    [false, true, false],
    [false, true, true],
    [true, false, false],
    [true, false, true],
    [true, true, false],
    [true, true, true]
];

for (let i = 0; i < testCases.length; i++)
{
    let A = testCases[i][0];
    let B = testCases[i][1];
    let C = testCases[i][2];

    let left = consensusTheoremLeft(A, B, C);
    let right = consensusTheoremRight(A, B, C);

    console.log('A:', A, 'B:', B, 'C:', C, '| same?', left === right);
}
```

---

Every test prints `true` - proving the consensus term `(B AND C)` is not needed.

---

//----//

// Dedicated to God the Father  
// All Rights Reserved  Christopher Andrew Topalian Copyright 2000-2025  
// https://github.com/ChristopherTopalian  
// https://github.com/ChristopherAndrewTopalian  
// https://sites.google.com/view/CollegeOfScripting

