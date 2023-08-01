# String Methods:

1. **`charAt`**: Returns the character at the specified index.
   ```javascript
   const str = 'Hello';
   const char = str.charAt(1);
   // char is 'e'
   ```

2. **`concat`**: Concatenates two or more strings.
   ```javascript
   const str1 = 'Hello, ';
   const str2 = 'World!';
   const combined = str1.concat(str2);
   // combined is 'Hello, World!'
   ```

3. **`includes`**: Checks if a string includes another string.
   ```javascript
   const str = 'JavaScript';
   const includes = str.includes('Script');
   // includes is true
   ```

4. **`indexOf`**: Returns the index of the first occurrence of a specified value.
   ```javascript
   const str = 'Hello, World!';
   const index = str.indexOf('World');
   // index is 7
   ```

5. **`lastIndexOf`**: Returns the last occurrence of a specified value.
   ```javascript
   const str = 'apple, banana, apple';
   const index = str.lastIndexOf('apple');
   // index is 14
   ```

6. **`repeat`**: Returns a new string with a specified number of copies.
   ```javascript
   const str = 'Ho';
   const repeated = str.repeat(3);
   // repeated is 'HoHoHo'
   ```

7. **`replace`**: Replaces a specified value with another value.
   ```javascript
   const str = 'Hello, World!';
   const replaced = str.replace('World', 'Amar');
   // replaced is 'Hello, Amar!'
   ```

8. **`slice`**: Extracts a part of a string and returns a new string.
   ```javascript
   const str = 'Hello, World!';
   const sliced = str.slice(7, 13);
   // sliced is 'World'
   ```

9. **`split`**: Splits a string into an array of substrings.
   ```javascript
   const str = 'apple,banana,cherry';
   const split = str.split(',');
   // split is ['apple', 'banana', 'cherry']
   ```

10. **`toLowerCase`**: Converts the string to lowercase letters.
    ```javascript
    const str = 'Hello, World!';
    const lower = str.toLowerCase();
    // lower is 'hello, world!'
    ```

11. **`toUpperCase`**: Converts the string to uppercase letters.
    ```javascript
    const str = 'Hello, World!';
    const upper = str.toUpperCase();
    // upper is 'HELLO, WORLD!'
    ```

12. **`trim`**: Removes whitespace from both ends of a string.
    ```javascript
    const str = '   Hello, World!   ';
    const trimmed = str.trim();
    // trimmed is 'Hello, World!'
    ```

13. **`substring`**: Returns the part of the string between the start and end indexes.
    ```javascript
    const str = 'JavaScript';
    const substr = str.substring(4, 10);
    // substr is 'Script'
    ```

