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

