## stdout (Standard out)
  - I/O(input/output) streams.
  - The ">" is a redirection operator allows use the change where standart output goes.
    ```
      $ echo Hello World > peanuts.txt
    ```
  - I didn't wanto to overwrite my peanuts.txt, there is a redirection operator for that as well, ">>".
    ```
      $ echo Hello World >> peanuts.txt
    ``` 

## stdin  (Standard in)
  - We have stdin from devices like the keyboard, but you can use files, output from other processes and the terminal as well.
  - Example:
    ```
      $ cat < peanuts.txt > banana.txt 
    ```
    - Just like we had ">" for stdout redirection, we can use "<" for stdin redirection.

## stderr (Standard error)
  - There is actually another I/O stream called stderr.
  - By default, stderr sends its output to the screen as well, it's a completely different stream that stdout. So you'll need to redirect its output a different way.
  
## pipe and tea 
  - The pipe operator "|", allows us to get the stdout of a command and make the stdin to another process. 
  - If I wanted to write the output command to two differents streams:
    ```
      $ ls | tee peanuts.txt
    ```