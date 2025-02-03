# MERN-Stack
This is my repository for my learning journey of MERN FSD
<br>
Author-Manoj Aswal
<br>
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
<br>
        <H1>Quadrants</H1>
<P>Four friends are in a mystery room and they aim to get out of the mystery room by cracking the final trail. The mystery room is divided into four chambers and each chamber will have two boxes storing balls. Now if both the boxes have blue balls, it must belong to chamber 1. Similarly if the first box has red balls and second box has blue balls, they must belong to chamber 2. If both the boxes have red balls, they must belong to chamber 3. Finally if the first box has blue balls and second box has red balls, it must belong to chamber 4.

You are given number of balls in each box and if the number has a negative sign it means the balls are red else the balls are blue if the sign is positive. Determine the chamber the two boxes belong to given the number and type of balls in each box.

Note: Assume there will always be non-zero number of balls in each box.</P>
