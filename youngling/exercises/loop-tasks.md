# Loop exercises

<details>
<summary>
### count
</summary>
<p>
Create a `count` function that prints each number from 0 to 10 in ascending order

You can test your function with the following code:
```js
console.log(count()) // => [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
```
</p>
</details>

<details>
<summary>
### reverseCount
</summary>
<p>
Create a `reverseCount` function that prints each number from 0 to 10 in descending order

You can test your function with the following code:
```js
console.log(reverseCount()) // => [10, 9, 8, 7, 6, 5, 4, 3, 2, 1, 0]
```
</p>
</details>

<details>
<summary>
### negativeCount
</summary>
<p>
Create a `negativeCount` function that prints each number from 0 to (-10) in descending order

You can test your function with the following code:
```js
console.log(negativeCount()) // => [0, -1, -2, -3, -4, -5, -6, -7, -8, -9, -10]
```
</p>
</details>

<details>
<summary>
### stepCount
</summary>
<p>
Create a `stepCount` function that prints the numbers [0, 2, 4, 6, 8, 10]

You can test your function with the following code:
```js
console.log(stepCount()) // => [0, 2, 4, 6, 8, 10]
```
</p>
</details>

<details>
<summary>
### repeat
</summary>
<p>
Create a function named `repeat(symbol, count)` that has 2 arguments - (symbol:string, count:number) and
returns a string with the `symbol` repeated `count` times:

You can test your function with the following code:
```js
console.log(repeat('*', 5)) // => '*****'
```
</p>
</details>

<details>
<summary>
6. Create a staircase
</summary>
<p>
6.1 Create a function named `staircase(size)` that has 1 argument (size:number),
which is the length of the last row and prints:
<pre>
"*    "
"**   "
"***  "
"**** "
"*****"
</pre>
6.2 Create a function named `reverseStaircase(size)` that has 1 argument (size:number),
which is the length of the last row and prints:
<pre>
"    *"
"   **"
"  ***"
" ****"
"*****"
</pre>
</p>
</details>

<details>
<summary>
7. Create a function `pyramid(size)` that has 1 argument (size:number),
which is the length of the last row and prints a pyramid:
</summary>
<p>
*Sub tasks:
- one task creates 1 line of the pyramid
- one task combines all the lines of the pyramid
*Total number of symbols per row is (2 * size - 1)
7.1 Pyramid
<pre>
"    *    "
"   ***   "
"  *****  "
" ******* "
"*********"
</pre>
7.2 Reverse pyramid `reversePyramid(size)`
<pre>
"*********"
" ******* "
"  *****  "
"   ***   "
"    *    "
</pre>
7.3 Christmas tree with an angel on top `christmasTree(size)`.
<pre>
"    _    "
"  {\o/}  "
"   /_\   "
"    *    "
"   o*o   "
"  *****  "
" o*****o "
"*********"
</pre>
The Christmas Tree should also have Christmas balls every second row, after the first and without the last one.
</p>
</details>