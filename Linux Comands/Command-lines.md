# Command Lines

## PWD (Print Working Directory)
  - To see where you are, you can use pwd command, it just shows you which directory you are in.

## CD (Change Directory)
  - cd nameDirectory
  - cd ( . , .. , ~ , - )
    - . (current directory)  
    - .. (parent directory)  
    - ~ (home directory)  
    - -- (previus directory): This will take you to they previous directory you are just at.

## ls (List Directories)
  - The ls command will list directories and files in the current directory by default, however you can which path you want to list the directories of.
  - Not all files in a directory will be visible. Files name that start with "."are hidden, you can view them however with: 
    ```
    - Ls -a
    ```
  - This command shows a detalied list of files in a long format.
    ```
    - Ls -l
    ```
    - This will show you detalied information:
      - file permissions
      - number of links
      - owner name
      - owner group
      - file size
      - timestamp of last modification 
      - file/directory name

## TOUCH
  - This command make some files.
  - Touch allows you to the create new empty files.
  ```
  touch nameFile
  ```

## FILE
  - In Linux, file aren't required to represente contents of the file. You can create a file called funny.gif that ins't actually a gif.
  - To find out what kind of file a file is, use file command.
  - It will show a description of the file's contents.
  ```
    file nameFile.jpg
  ```

## CAT
  - Use cat for read a file.
  - It's not great for view large files and it's only meant for short content.

## LESS
  - If you are viewing text files large than a simple output, less is more.
  - Use the command to navigate through less:
    - q: Used to quit out of less and go back to your shell.
    - g: Moves to beginning of the text file.
    - G: Moves to the end of text file.
    - /search: For specific text inside the text document. Prefacing the words you want to search.

## History
  - For commands historic.

### CP (Copy)
### MV (Move)
### Mkdir (Make Directory)
### rm (Remove) 
  -  rm -r (remove directory)
