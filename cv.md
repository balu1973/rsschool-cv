# Morokhin Aleksey

# Contact information

- **Email -** balurus37@gmail.com 
- **Telegram -** [@noob_iAm](https://t.me/noob_iAm) 
- **GitHub -** [balu1973](https://github.com/balu1973)
- **Discord -** Alex M (@balu1973)

# About me

I really enjoy learning JavaScript, HTML, CSS. It's very cool to learn something new all the time. I want to learn how to work in a team. I really like frontend development and I want to learn everything related to it very well. 

# Skills
- HTML
- CSS
- JavaScript
- Git
- React basics


# Code example

### Count the number of Duplicates

Write a function that will return the count of distinct case-insensitive alphabetic characters and numeric digits that occur more than once in the input string. The input string can be assumed to contain only alphabets (both uppercase and lowercase) and numeric digits.

### Example

```javascript
"abcde" -> 0 # no characters repeats more than once
"aabbcde" -> 2 # 'a' and 'b'
"aabBcde" -> 2 # 'a' occurs twice and 'b' twice (`b` and `B`)
"indivisibility" -> 1 # 'i' occurs six times
"Indivisibilities" -> 2 # 'i' occurs seven times and 's' occurs twice
"aA11" -> 2 # 'a' and '1'
"ABBA" -> 2 # 'A' and 'B' each occur twice
```

### Solution

```javascript
function duplicateCount(text){
  let count = 0;
  while (text) {
    let prevLengthStr = text.length;
    let char = text.charAt(0);
    text = text.replace(new RegExp(`${char}`, 'gi'), "");
    if (prevLengthStr - 1 > text.length) {
      count++;
    }
  }
  return count;
}
```

# Projects
1. <https://github.com/balu1973/rsschool-cv> - My first project under <https://rs.school/>

# Education

1. <https://htmlacademy.ru>
2. <https://strada.one>
3. <https://learn.javascript.ru>
4. <https://www.freecodecamp.org>

# Languages

1. English - google translate
2. Russian - native