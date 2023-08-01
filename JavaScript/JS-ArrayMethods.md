# **Array Methods:**

1. **`push`**: Adds elements to the end of an array.
   ```javascript
   const numbers = [1, 2];
   numbers.push(3);
   // numbers is now [1, 2, 3]
   ```

2. **`pop`**: Removes the last element from an array.
   ```javascript
   const numbers = [1, 2, 3];
   numbers.pop();
   // numbers is now [1, 2]
   ```

3. **`shift`**: Removes the first element from an array.
   ```javascript
   const numbers = [1, 2, 3];
   numbers.shift();
   // numbers is now [2, 3]
   ```

4. **`unshift`**: Adds elements to the beginning of an array.
   ```javascript
   const numbers = [2, 3];
   numbers.unshift(1);
   // numbers is now [1, 2, 3]
   ```

5. **`splice`**: Changes the array by removing or replacing elements.
   ```javascript
   const numbers = [1, 3, 4];
   numbers.splice(1, 1, 2);
   // numbers is now [1, 2, 4]
   ```

6. **`slice`**: Returns a shallow copy of a part of an array.
   ```javascript
   const numbers = [1, 2, 3];
   const sliced = numbers.slice(1);
   // sliced is now [2, 3]
   ```

7. **`join`**: Joins all elements of an array into a string.
   ```javascript
   const letters = ['a', 'b', 'c'];
   const joined = letters.join('');
   // joined is 'abc'
   ```

8. **`reverse`**: Reverses the elements of an array.
   ```javascript
   const numbers = [1, 2, 3];
   numbers.reverse();
   // numbers is now [3, 2, 1]
   ```

9. **`reduce`**: Reduces the array to a single value using a function.
   ```javascript
   const numbers = [1, 2, 3];
   const sum = numbers.reduce((acc, number) => acc + number, 0);
   // sum is 6
   ```

10. **`filter`**: Creates a new array with elements that pass a test.
    ```javascript
    const numbers = [1, 2, 3, 4];
    const even = numbers.filter(number => number % 2 === 0);
    // even is [2, 4]
    ```

11. **`find`**: Returns the first element that satisfies a testing function.
    ```javascript
    const numbers = [1, 2, 3, 4];
    const found = numbers.find(number => number > 2);
    // found is 3
    ```

12. **`map`**: Creates a new array by transforming each element.
   ```javascript
   const numbers = [1, 2, 3];
   const doubled = numbers.map(number => number * 2);
   // doubled is now [2, 4, 6]
   ```

13. **`forEach`**: Executes a function for each array element (no return value).
   ```javascript
   const numbers = [1, 2, 3];
   numbers.forEach(number => {
     console.log(number * 2);
   });
   // Output: 2, 4, 6
   ```

