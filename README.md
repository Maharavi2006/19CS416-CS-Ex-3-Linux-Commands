# 19CS416-CS-Ex-3-Linux-Commands

**Linux** is an open-source operating system, and its kernel is the heart of the OS, facilitating communication between hardware and software. One of the key advantages of Linux is its customizability; developers can modify the Linux kernel to create their own tailored operating systems.

## Linux Commands

Linux commands are executed in the terminal, which is case-sensitive. This guide covers some basic and advanced commands used in Linux.

### 1. `ls` Command

The `ls` command is used to display a list of contents in a directory.

**Syntax:** 
```bash
ls
```

**Output:**

<img width="1276" height="223" alt="image" src="https://github.com/user-attachments/assets/c05e0582-9c2c-4a89-a987-405bd54e60e6" />


### 2. `pwd` Command

The `pwd` command displays the location of the current working directory.

**Syntax:**
```bash
pwd
```

**Output:**

<img width="564" height="123" alt="image" src="https://github.com/user-attachments/assets/c343bbf3-953d-4c36-937a-afea082c32f6" />


### 3. `mkdir` Command

The `mkdir` command is used to create a new directory.

**Syntax:**
```bash
mkdir <directory_name>
```

**Output:**

<img width="845" height="178" alt="image" src="https://github.com/user-attachments/assets/1c359caf-6d96-4baa-a0cd-0a1723862a5e" />


### 4. `rmdir` Command

The `rmdir` command is used to delete a directory.

**Syntax:**
```bash
rmdir <directory_name>
```

**Output:**

<img width="764" height="185" alt="image" src="https://github.com/user-attachments/assets/e192f901-ca0d-441c-9acb-c2cd0fe4e715" />


### 5. `cd` Command

The `cd` command is used to change the current directory.

**Syntax:**
```bash
cd <directory_name>
```

**Output:**

<img width="596" height="115" alt="image" src="https://github.com/user-attachments/assets/237c35e4-390e-4380-918e-407ba93d77d9" />


### 6. `cat` Command

The `cat` command is used to create, display, and concatenate files.

**Syntax:**
```bash
cat [OPTION]... [FILE]...
```

**Output:**

<img width="530" height="162" alt="image" src="https://github.com/user-attachments/assets/2a6efb0f-8d75-475c-b6ad-761f8226f437" />


### 7. `cp` Command

The `cp` command is used to copy files or directories.

**Syntax:**
```bash
cp <source_file> <destination_file>
```

**Output:**

<img width="778" height="206" alt="image" src="https://github.com/user-attachments/assets/43840e7f-0a6f-4609-b9d4-3632e7341eac" />


### 8. `gedit` Command

`gedit` is a general-purpose text editor used to create and edit text files.

**Syntax:**
```bash
gedit <file_name>
```

**Output:**

<img width="471" height="55" alt="image" src="https://github.com/user-attachments/assets/8150957c-f3c7-4009-8f77-82dd307aac10" />


### 9. `su` Command

The `su` command provides administrative access to another user.

**Syntax:**
```bash
su <username>
```

**Output:**

<img width="651" height="145" alt="image" src="https://github.com/user-attachments/assets/b73ebd45-aaba-40b7-b952-3f7fce1ed371" />


### 10. `mv` Command

The `mv` command is used to move a file or directory from one location to another.

**Syntax:**
```bash
mv <file_name> <directory_path>
```

**Output:**

re<img width="545" height="281" alt="image" src="https://github.com/user-attachments/assets/ac5ad424-bc3a-4d16-b6d4-02aa99df5d7a" />


### 11. `rename` Command

The `rename` command is used to rename files.

**Syntax:**
```bash
rename 's/old-name/new-name/' <files>
```

**Output:**

<img width="585" height="58" alt="image" src="https://github.com/user-attachments/assets/236eb0f6-4b61-48fc-90b7-ba0aa32d578a" />


### 12. `head` Command

The `head` command displays the first 10 lines of a file.

**Syntax:**
```bash
head <file_name>
```

**Output:**

<img width="568" height="68" alt="image" src="https://github.com/user-attachments/assets/e1a42591-fca2-48f6-8fa6-591c45cf096f" />


### 13. `tail` Command

The `tail` command displays the last 10 lines of a file.

**Syntax:**
```bash
tail <file_name>
```

**Output:**

<img width="566" height="91" alt="image" src="https://github.com/user-attachments/assets/3b6da268-359c-4813-8588-e07fe3e789cd" />


### 14. `id` Command

The `id` command displays the user ID (UID) and group ID (GID).

**Syntax:**
```bash
id
```

**Output:**

<img width="950" height="109" alt="image" src="https://github.com/user-attachments/assets/db90e0c1-8a6a-47dc-b990-789e644ac456" />

### 15. `grep` Command

The `grep` command is used to search for a pattern within files.

**Syntax:**
```bash
command | grep <search_word>
```

**Output:**

<img width="570" height="89" alt="image" src="https://github.com/user-attachments/assets/2a6ddb86-f537-4756-8ddf-6280be4497c1" />


### 16. `tr` Command

The `tr` command is used to translate or delete characters.

**Syntax:**
```bash
command | tr <old> <new>
```

**Output:**

<img width="534" height="71" alt="image" src="https://github.com/user-attachments/assets/fde707dc-aa7a-43a5-9fa3-fa3d5f6ef7bd" />


### 17. `chmod` Command

The `chmod` command is used to change the access mode (permissions) of a file.

**Syntax:**
```bash
chmod <options> <permissions> <file_name>
```

**Output:**

<img width="544" height="58" alt="image" src="https://github.com/user-attachments/assets/c7f21b4c-a71c-45a8-b518-efcbe40b6b82" />


### 18. `tar` Command

The `tar` command is used to create or extract archive files.

**Syntax:**
```bash
tar [options] [archive-file] [files_to_archive]
```

**Output:**

<img width="576" height="101" alt="image" src="https://github.com/user-attachments/assets/d9bc848d-5567-4505-b306-5c6c56832066" />


### 19. `chown` Command

The `chown` command is used to change the ownership of a file.

**Syntax:**
```bash
chown <owner_name> <file_name>
```

**Output:**

<img width="651" height="61" alt="image" src="https://github.com/user-attachments/assets/93bfeced-2b29-4cf1-8d7a-f261198cff2a" />


### 20. `make` Command

The `make` command is used to build and maintain groups of programs.

**Syntax:**
```bash
make [-f makefile] [options] [targets]
```

**Output:**

<img width="596" height="190" alt="image" src="https://github.com/user-attachments/assets/4a5524b4-3f44-46d7-82eb-230c636d955f" />



### 21. `ifconfig` Command

The `ifconfig` command is used to configure network interfaces.

**Syntax:**
```bash
ifconfig [options] [interface]
```

**Output:**

<img width="610" height="459" alt="image" src="https://github.com/user-attachments/assets/970fcd64-9d6f-4ff9-8443-eb6e0daf2f22" />

### 22. `chmod 777` Command

The `chmod 777` command gives read, write, and execute permissions to the owner, group, and others.

**Syntax:**
```bash
chmod 777 <file_name>
chmod -R 777 /path/to/file/or/folder
```

**Output:**

<img width="463" height="46" alt="image" src="https://github.com/user-attachments/assets/f83f24ab-6d35-4d8b-b946-32c16bace140" />


### 23. `host` Command

The `host` command is used to display the IP address for a given domain name.

**Syntax:**
```bash
host <domain_name> or <ip_address>
```

**Output:**

<img width="884" height="289" alt="image" src="https://github.com/user-attachments/assets/48dba787-f0bc-4336-98fd-79269b9f15f0" />


### 24. `gzip` Command

The `gzip` command is used to compress files, replacing the original file with a compressed one with a `.gz` extension.

**Syntax:**
```bash
gzip <file1> <file2> <file3>...
```

**Output:**

<img width="592" height="276" alt="image" src="https://github.com/user-attachments/assets/2ac32136-3203-4525-be16-7fad47da770f" />

### 25. `sort` Command

The `sort` command is used to sort the contents of a file alphabetically.

**Syntax:**
```bash
sort <file_name>
```

**Output:**

<img width="453" height="83" alt="image" src="https://github.com/user-attachments/assets/a336e514-0f8c-4724-aad8-00a0fcc18361" />


### 26. `cal` Command

The `cal` command displays the current month's calendar with the current date highlighted.

**Syntax:**
```bash
cal
```

**Output:**

<img width="415" height="177" alt="image" src="https://github.com/user-attachments/assets/73ca00fd-c645-4b60-b2a2-19c20b8009ba" />


### 27. `clear` Command

The `clear` command clears the terminal screen.

**Syntax:**
```bash
clear
```

**Output:**

<img width="477" height="63" alt="image" src="https://github.com/user-attachments/assets/641f2380-42a2-44a3-ba77-f24ff819213e" />

### 28. `mail` Command

The `mail` command is used to send emails from the command line.

**Syntax:**
```bash
mail
```

**Output:**

<img width="427" height="113" alt="image" src="https://github.com/user-attachments/assets/6373cff6-fa14-4cb0-bf83-c8ad1b3d515d" />


### 29. `df` Command

The `df` command displays the disk space usage of file systems.

**Syntax:**
```bash
df
```

**Output:**

<img width="834" height="206" alt="image" src="https://github.com/user-attachments/assets/393c3e13-f68b-4eba-83cb-f18eea930b92" />


### 30. `find` Command

The `find` command is used to search for files in a directory hierarchy.

**Syntax:**
```bash
find <directory> -name <file_name>
```

**Output:**

<img width="587" height="223" alt="image" src="https://github.com/user-attachments/assets/b9f91b34-c99e-4a2d-b37c-6e6cfd679bf2" />

## Result
Linux commands are executed in the linux terminal successfully.
