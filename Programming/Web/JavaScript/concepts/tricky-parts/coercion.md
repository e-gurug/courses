---
title: Coercion in Javascript
date: Dec 29, 2023
author: Devendra Vasant Katuke
---

```
[] + [] 		// "" (empty string)
[] + {}	 		// "[object Object]" (string)
{} + [] 		// 0
({} + [])		// "[object Object]"
false +	[] 		// "false" (string)
"123" +	1 		// "1231" (string)
"123" -	1 		// 122 (number)
"123" -	"abc" 	// NaN (number)
```
