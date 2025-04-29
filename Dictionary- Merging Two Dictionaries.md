## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
      def dictionairy():
            key_value ={}
      
      key_value[2] = 56
      key_value[1] = 2
      key_value[5] = 12
      key_value[4] = 24
      key_value[6] = 18
      key_value[3] = 323
      
      print ("Keys and Values sorted in alphabetical order by the value")


      print(sorted(key_value.items(), key = lambda kv:(kv[1], kv[0])))


## Output
![image](https://github.com/user-attachments/assets/ca1e66e9-478d-4a68-bcb2-aaf281fd3030)


## Result
Thus,the program has been execueted successfully.
