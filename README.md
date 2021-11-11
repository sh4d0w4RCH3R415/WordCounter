## WordCounter
### Description
A Java package that can be used to count the number of words in a string, or get the first letter of each word in a string.

### How To Use
Code
```java

/*
    WordCounter_Example.java
    
    Author: sh4d0w4RCH3R415
      Date: November 10, 2021
*/

import lexz.wordCounter.WordCounter;

public class WordCounter_Example
{
    public static void main(String[] args)
    {
        String sentence = "'; The quick BROWN FOX jUmPeD over the LAZY dOg;.";
        
        System.out.println(sentence);
        System.out.println("");
        System.out.println(WordCounter.countWords(sentence) + " Words");
        System.out.println("");
        System.out.println("Word Beginnings");
        System.out.println(WordCounter.getWordBeginnings(sentence));
    }
}

```
Output
```

'; The quick BROWN FOX jUmPeD over the LAZY dOg;.

9 Words

Word Beginnings:
T, q, B, F, j, o, t, L, d

```

### Download
[WordCounter.jar](https://github.com/sh4d0w4RCH3R415/WordCounter/releases/download/word-counter/WordCounter.jar)
