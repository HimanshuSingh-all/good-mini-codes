# good-mini-codes
Just a bunch of short codes that I have written that I like

- Forcing a function to take only keyword arguments (taken from [dev](https://dev.to/uponthesky/pythontips-for-writing-robust-python-code-functions-2g2k) )
    
    "Well, it is not the case. What I meant by doesn't is that you can still write a function solely using positional arguments. However, you can enforce your function to only have keyword arguments. You simply need to put your arguments after placing an asterisk *.
    
    ```python
    def keywords_only(*, arg1: int, arg2: str) -> int:
      if __name__ == '__main__':
          keywords_only(arg1=42, arg2="is good")
    ```
    This is actually not my idea but Sandi Metz's which I read from her OOD book. Not only does it reduce mistakes in calling functions, but also reveals sufficient information about the function(as a documentation)."
