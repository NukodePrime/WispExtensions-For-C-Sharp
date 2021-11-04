# WispExtensions-For-C-Sharp
Extension methods enable you to "add" methods to existing types without creating a new derived type, recompiling, or otherwise modifying the original type.

## String extensions :

**GetStringWithNoCommaAtTheEnd()** : Returns the string with no comma at the end.<br/>
**Unescape_Regex()** : Unescape the string (internally done by using a regular expression).<br/>
**SurroundWithDoubleQuotes()** : Surround the string with double quotes "".<br/>
**SurroundWithCurlyBraces()** : Surround the string curly braces {}.<br/>
**SurroundWithBars()** : Surround the string with bars [].<br/>
**ToInt()** : Convert the string to an integer.<br/>
**ToLong()** : Convert the string to a long integer.<br/>
**ToFloat()** : Convert the string to a float.<br/>
**GetDigitsOnly()** : Extract digits from a string and returns the digits as a string.<br/>
**ToBool()** : Convert the string to a bool (Yes and True return true for example).<br/>
**LevenshteinDistance()** : Return the Levenshtein distance between two strings, the more similar they are the smaller the result.<br/>
**IsSemiColonTerminated()** : Checks if the string ends with a semi-column;<br/>
**UrlEncode()** : URL encode the string.<br/>
**ToBase64()** : Convert the string to Base64.<br/>
**FromBase64()** : Returns a string from a Base64 string.<br/>
**FromBase64_NoFail()** : Returns a string from a Base64 string and/or returns an empty string if any exception occurs.<br/>
