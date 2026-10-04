# Slug
A toy language implemented in rust. It's stack based and pretty darn ugly, I
hate it and so should you. The file extension is whatever you want it to be,
I've been using `.slug` for my test and example files.

Example:
```slug
5
8
add
-- Outputs 13
```

# "Features"
 - The whole language is interpreted token by token
    - This applies to the `jump` and `goto` operations. 
 - There are no stack frames.
 - There are no comments.
 - The only data type is a 64-bit signed integer.
