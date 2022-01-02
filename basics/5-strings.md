# String Reverse

Write a program to display the input string in reverse. The program should create a variable to store the string obtained from the user and then create another variable to store the reversed string.

Expected Input:

```
Input a string: The quick brown fox
```

Expected Output:

```
Reverse string: xof nworb kciuq ehT
```

_Themes: strings_

# Middle Character

Write a Java method to display the middle character of a string.
Note: 
a. If the length of the string is odd there will be two middle characters.
b. If the length of the string is even there will be one middle character.

Expected Input:

```
Input a string: Hello
```

Expected Output:

```
The middle character in the string: l
```

# Palindrome

A palindrome is a word which reads the same backward or forward. 'abcba' is a palindrome.
Write a method that detects if a string is a palindrome.
Tip: Use `word.charAt(i)` to get the character at position i.

Expected Input 1:

```
Input a string: racecar
```

Expected Output 1:

```
"racecar" is a palindrome
```

Expected Input 2:

```
Input a string: automobile
```

Expected Output 2:

```
"automobile" is not a palindrome
```

# Ceasar Cipher

The Ceasar cipher is a basic encryption technique used by Julius Ceasar to securely communicate with his generals. Each letter is replaced by another letter N positions down the english alphabet. For example, for a rotation of 5, the letter 'c' would be replaced by an 'h'. In case of a 'z', the alphabet rotates and it is transformed into a 'e'.

Implement an encoder and a decoder for the Ceasar cipher where N = 5.

TIP: Use code.toCharArray() to get an array of characters.

## Encoder

Expected Input:

```
Input a string: hello
```

Expected Output:

```
mjqqt
```

## Decoder

Expected Input:

```
Input a string: mjqqt
```

Expected Output:

```
hello
```

# Transpose

The musical scale follows the order: A, A#, B, C, C#, D, D#, E, F, F#, G, G#
Implement a transpose method which takes an integer (+ or -) and an input chord sequence and transposes the sequence to the right key.

Expected Input:

```
Chord Sequence: G, E, C, D
Transpose Value: 3
```

Expected Output:

```
Transposed Chord Sequence: A#, G, D#, F
```