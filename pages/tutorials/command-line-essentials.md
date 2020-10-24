## <span style="text-decoration:underline">Command Line Essentials</span>

\> [Homepage](../../README.md) \>

Welcome! Here we will cover most of the commands a developer would typically make use of on a daily basis. Our focus here will be commands that help with interacting with files and folders (also known as directories).

## NAVIGATION

#### PRESENT DIRECTORY

```
.
```

```
./
```

PREVIOUS DIRECTORY

```
..
```

```
../
```

-   Note that the navigation syntax above are generally implemented with commands below, and can be used with them.

## Commands

> When implementing the commands below, do not use the `<` and `>` symbols. This is just for a distinguising effect.

---

CHANGING DIRECTORY

```cmd
cd <DIRECTORY-NAME>
```

-   The `cd` keyword is used for changing directories. Its primary purpose is taking one from the current directory to another existing directory. Think of it as a way to change locations within a system by using the command line.

---

CREATING A FILE

```cmd
touch <FILENAME>.<ext>
```

-   The `touch` keyword is used for creating files. When creating a file it is important to include the relevant extension (eg. `.txt`, `.html`, `.css`, `.js`, `.py`, `.php`; etc). This helps your system know what type of file you can interacting with, and assists it in performing properly.

-   The command above creates a file in the directory where one is currently, on the command line. For cases where you need to create a file elsewhere, use `touch` followed by a space and the relevant navigation symbols, before the desired filename.

---

CREATING A DIRECTORY

```cmd
mkdir <DIRECTORY-NAME>
```

-   The `mkdir` keyword is used for creating directories (folders). This should be done without spacing in the folder name. The dash (`-`) or underscore (`_`) symbols can be used to simulate spacing.

---

MOVING A DIRECTORY

```cmd
mv <PRESENT-LOCATION>/<DIRECTORY-NAME> <NEW-LOCATION>
```

-   One use of the `mv` keyword is for moving directories. The syntax of this command takes three major arguments: the keyword, the present location and directory name, with the new location being the final argument.

    -   An example of this is as follows: `mv ./cheese ../burger`. This dummy command moved the `cheese` directory one step above (to the previous directory, named `burger`).

---

RENAMING A DIRECTORY

```cmd
mv <CURRENT-DIRECTORY-NAME> <NEW-DIRECTORY-NAME>
```

-   Another primary use of the `mv` keyword is renaming directories. This application of the keyword is far more direct, yet still takes three arguments.

    -   The first argument is the keyword, followed by the current name of the directory or folder, followed immediately by the new name.

---

COPYING A FILE

```cmd
cp <PRESENT-LOCATION>/<FILE>.<EXT> <NEW-LOCATION>
```

-   The `cp` keyword is used for copying files from one location to another. It takes three arguments as well.
    -   The first argument is the keyword, the second is a combination of the present location and filename (do not forget to include the extension - `.txt`, for example), with the final argument being the desired location for the copied file.

---

Make luxurious use of the navigation techniques with all of the commands above. This is because in many cases, the operations that need to be done on files and folders, require action in distant locations.
