# CMD Commands

| Command Method     | Command Example                           | Description                                                                                      |
| ------------------ | ----------------------------------------- | ------------------------------------------------------------------------------------------------ |
| **Using `echo`**   | `echo This is some text > filename.txt`   | Creates a file with the specified content. If the file exists, it will be overwritten.           |
| **Using `type`**   | `type nul > filename.txt`                 | Creates an empty file. The `nul` device represents a null stream, essentially an empty file.     |
| **Using `copy`**   | `copy nul filename.txt`                   | Also creates an empty file. `nul` is treated as a source of nothing, resulting in an empty file. |
| **Using `fsutil`** | `fsutil file createnew filename.txt 1024` | Creates a file of a specific size (in bytes). Here, `1024` creates a 1KB file.                   |

## Common Commands

| Command                                   | Description                                                        |
| ----------------------------------------- | ------------------------------------------------------------------ |
| cd                                        | Change directory                                                   |
| dir                                       | List directory contents                                            |
| md                                        | Make directory                                                     |
| rd                                        | Remove directory                                                   |
| copy                                      | Copy files and folders                                             |
| move                                      | Move files and folders                                             |
| del                                       | Delete files                                                       |
| ren                                       | Rename files and folders                                           |
| attrib                                    | Change file attributes                                             |
| xcopy                                     | Copy files and folders with options                                |
| systeminfo                                | Displays system information                                        |
| ipconfig                                  | Displays network configuration                                     |
| ping                                      | Tests network connectivity                                         |
| tracert                                   | Traces route to a network host                                     |
| nslookup                                  | Queries DNS information                                            |
| tasklist                                  | Lists running processes                                            |
| taskkill                                  | Terminates running processes                                       |
| chkdsk                                    | Checks disk integrity                                              |
| sfc /scannow                              | Scans system files for corruption                                  |
| netstat                                   | Displays network connections                                       |
| cls                                       | Clears the screen                                                  |
| shutdown                                  | Shuts down the computer                                            |
| restart                                   | Restarts the computer                                              |
| format                                    | Formats a disk                                                     |
| help                                      | Displays help for commands                                         |
| color                                     | Changes the command prompt colors                                  |
| time                                      | Displays or sets the system time                                   |
| date                                      | Displays or sets the system date                                   |
| pause                                     | Pauses command execution                                           |
| ver                                       | Displays the Windows version                                       |
| `start`                                   | To open a file in the respective editor                            |
| `color [attr]`                            | Changes the text and background color of the Command Prompt.       |
| `code`                                    | Creates and opens a file in Visual Studio Code.                    |
| `echo`                                    | Creates a file with specified text content using `echo`.           |
| `copy nul filename.txt`                   | Creates an empty file using the `copy` command.                    |
| `type nul > filename.txt`                 | To create an empty file using type                                 |
| `fsutil file createnew filename.txt 1024` | Creates a file with a specified size (1024 bytes in this example). |
