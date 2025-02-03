# MERN-Stack
This is my repositery for my learning journey of MERN FSD
<br>
Author-Manoj Aswal
//Which Angled Triangle - JS Assignment
  let [a, b, c] = sides.split(' ').map(Number);
    const maxSide = Math.max(a, b, c);
    const sumSquares = a ** 2 + b ** 2 + c ** 2;
    const twiceMaxSq = 2 * maxSide ** 2;

    if (twiceMaxSq < sumSquares) {
        console.log(1);
    } else if (twiceMaxSq === sumSquares) {
        console.log(2);
    } else {
        console.log(3);
