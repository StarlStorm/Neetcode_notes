`"".join()` means **merge all the elements with no space at all**

    -`" ".join()` means **still merge, but add a space between two elements**
  
    -`"-".join()` means **add a - between elements**

    - words = ["Hello", "world", "foo"]
    
            -result = " ".join(words)   # "Hello world foo"  (space between each)
            
            -result = "".join(words)    # "Helloworldfoo"    (no separator, just glued together)
            
            -result = "-".join(words)   # "Hello-world-foo"  (dash between each)

