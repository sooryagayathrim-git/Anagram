
🔠 Anagram Checker

This project determines whether two given strings are **anagrams** of each other.  

 📖 What is an Anagram?
Two strings are called *anagrams* if they contain the same characters with the same frequency, but possibly in a different order.  

Examples:
- `listen` → `silent` ✅ Anagram  
- `hello` → `world` ❌ Not an Anagram  

 How It Works
1. Take two strings as input.  
2. Convert both strings to lowercase (to make it case-insensitive).  
3. Sort the characters of each string.  
4. Compare lengths first – if unequal, they are not anagrams.  
5. If the sorted results are the same, the strings are anagrams. Otherwise, they are not.  

