#### January 28, 2019
---

**Tricks**
- Sort items in a file alphabetically using the SORT command in Linux/Unix terminal with the simple command below 
    ```
    sort path/to/file.ext > path/to/output-file.ext
    ```
    To view contents of a file
    ```
    cat path/to/file.ext
    ```
  Resource: [https://www.geeksforgeeks.org/sort-command-linuxunix-examples/](https://www.geeksforgeeks.org/sort-command-linuxunix-examples/)
  
#### January 31, 2019
---

**Tricks**
- Open AVD without opening Android Studio
    - In root folder, run the following command to get a list of AVDs on your system
        ```
        cd Library/Android/sdk/tools
        ```
        ```
        ./emulator -list-avds
        ```
        e.g
        ![avd-cmd-example](https://github.com/iverenshaguy/new-things-i-learned/blob/master/images/Screenshot%202019-01-31%20at%208.29.21%20PM.png)
        
    - Run the following command to open one of the AVDs
        ```
        emulator -avd name-of-avd
        ```
        e.g.
        ```
        emulator -avd Nexus_5X_API_24
        ```
