# String Reverse(文字の順番を入れ替える)

Write a program to display the input string in reverse. The program should create a variable to store the string obtained from the user and then create another variable to store the reversed string.

入力された文字列を反転して表示するプログラムを作成しましょう。プログラムは、ユーザから取得した文字列を格納する変数を作成し、その後、反転した文字列を格納する変数を作成すること。

Expected Input:

```
Input a string: The quick brown fox
```

Expected Output:

表示されるもの:

```
Reverse string: xof nworb kciuq ehT
```

_Themes: strings_

テーマ:文字列

# Middle Character(中間にある文字)

Write a Java method to display the middle character of a string.
Note: 
a. If the length of the string is odd there will be two middle characters.
b. If the length of the string is even there will be one middle character.

文字列の中央の文字を表示するJavaメソッドを作成します。
注意
a.文字列の長さが奇数の場合、中間文字が2つ存在することになる。
b.文字列の長さが偶数であれば、中間の文字は1つである。

Expected Input:

```
Input a string: Hello
```

Expected Output:

できるもの:

```
The middle character in the string: l
```

# Palindrome(回文)

A palindrome is a word which reads the same backward or forward. 'abcba' is a palindrome.
Write a method that detects if a string is a palindrome.
Tip: Use `word.charAt(i)` to get the character at position i.

回文とは、前後で同じ読み方をする単語のことです。abcba'は回文です。
文字列が回文であるかどうかを検出するメソッドを書きましょう。
ヒント: iの位置の文字を取得するには `word.charAt(i)` を使いましょう。

Expected Input 1:

```
Input a string: racecar
```

Expected Output 1:

表示されるもの1:

```
"racecar" is a palindrome
```

Expected Input 2:

```
Input a string: automobile
```

Expected Output 2:

表示されるもの2

```
"automobile" is not a palindrome
```

# Ceasar Cipher(カエサルの暗号)

The Ceasar cipher is a basic encryption technique used by Julius Ceasar to securely communicate with his generals. Each letter is replaced by another letter N positions down the english alphabet. For example, for a rotation of 5, the letter 'c' would be replaced by an 'h'. In case of a 'z', the alphabet rotates and it is transformed into a 'e'.

Implement an encoder and a decoder for the Ceasar cipher where N = 5.

TIP: Use code.toCharArray() to get an array of characters.

シーサー暗号は、ユリウス・シーサーが将軍たちと安全に通信するために用いた基本的な暗号技術である。各文字は、英語のアルファベットのN番目の位置にある別の文字に置き換えられます。例えば、5回転の場合、「c」は「h」に置き換わる。z」の場合は、アルファベットが回転し、「e」に変換される。

N = 5 の場合の Ceasar 暗号のエンコーダとデコーダを実装せよ。

ヒント: code.toCharArray() を使用して文字の配列を取得する。

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

表示されるもの:

```
hello
```

# Transpose(転調)

The musical scale follows the order: A, A#, B, C, C#, D, D#, E, F, F#, G, G#
Implement a transpose method which takes an integer (+ or -) and an input chord sequence and transposes the sequence to the right key.

音階は次のような順序で進みます。a, a#, b, c, c#, d, d#, e, f, f#, g, g#.
整数（+または-）と入力コード列を受け取り、正しいキーに移調するメソッドを実装しましょう。

Expected Input:

```
Chord Sequence: G, E, C, D
Transpose Value: 3
```

Expected Output:

表示されるもの:

```
Transposed Chord Sequence: A#, G, D#, F
```
