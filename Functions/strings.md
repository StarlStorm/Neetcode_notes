`"".join()` means **merge all the elements with no space at all**

    -`" ".join()` means **still merge, but add a space between two elements**
  
    -`"-".join()` means **add a - between elements**

    - ***Example:*** words = ["Hello", "world", "foo"]
    
            -result = " ".join(words)   # "Hello world foo"  (space between each)
            
            -result = "".join(words)    # "Helloworldfoo"    (no separator, just glued together)
            
            -result = "-".join(words)   # "Hello-world-foo"  (dash between each)



`.strip()` means **Only remove whitespace from the *beginning* and *ending* of a string**

        -s = "  hello world  "
        
        -s.strip()          # "hello world"   (removes leading/trailing spaces only)
        
        -s2 = "xxhelloxx"
        
        -s2.strip("x")       # "hello"        (removes leading/trailing 'x' characters)

Key difference
"".join() — takes a collection of strings → produces one combined string. Used to build.
.strip() — takes one string → produces a trimmed version of that same string. Used to clean.


`s.replace("!", "")` means **Get rid of !** **The first argument could be variable as well**

```python
import re
s = "Hello, World! 123."
clean = re.sub(r'[^a-zA-Z0-9\s]', '', s)
# "Hello World 123"
```







`.isalpha()`	check if all characters are letters only

`.isdigit()`	check if all characters are digits only

`.isalnum()`	check if all characters are letters or digits

`.isspace()`	check if all characters are whitespace

`.islower()`	check if all letters are lowercase

`.isupper()`	check if all letters are uppercase

