# Basic Linux Command
1. Current directory
```bash
    pwd
```
2. Clear Shell (or press `ctrl l`)
```bash
    clear 
```
3. Channel command action - press `ctrl c`

4. Change Directory 
```bash
    cd
```
* Move last Directory
```bash
    cd -
```
* Move arent Directory
```bash
    cd ..
```
5. List all file and directory in current directory
```bash
    ls
```
6. List all file and directory with more details
```bash
    ls -l
```
* liar with show hidden file
```bash
    ls -la (show hidden file)
```
7. Read a file into shell
```bash
    cat <file_name>
```
8. Read large file into shell
```bash
    less <file_name>
```
9. Create a directory into current directory
```bash
    mkdir <folder_name>
```
* Create nested directory intot current directory
```bash
    mkdir -p <folder1/folder2/folder3>
```
10. Delete a direcotry 
```bash
    rm <folder_name>
```
11. Detele directory with all contains file and folders
```bash
    rm -r <folder_name>
```
12. copy file's data to another file
```bash
    cp <copy_file> <paste_file>
```
13. copy file from nested folder
```bash
    cp -r <folder1/folder2> <folder3>
```
14. Move file to another file(delete file and copy all data to another file) or another folder (move file to current folder to another folder ) or folder to another folder (move folder inside another folder)
```bash
    mv <file_name> <file_name2>
```
```bash
    mv <file_name> <folder>
```
```bash
    mv <folder1> <folder2>
```

15. found where bnarry command file stored Store
```bash
which bash
```
16. Edit file into shell or create a file 
```bash
nano <file_name>
```
* `ctrl x` - exit nano , `ctrl o` - save change, `ctrl w` - search, `ctrl a` - start of line, `ctrl e` - end of line 

17. Run script by shell
```bash
    bash <script>
```
- Try to run this script 

```bash
    echo "Hello world"

    echo "Enter your name : "
    # read the input
    read name
    # prompt 
    read -p "Email : " email
    # secure prompt
    read -sp "password: " password
    # dollar sign use variable
    echo "Welcome to $name,$email "


```
18. Check status code of a command or script
```bash
echo $?
```
* code 0 mean no error 

### Package Manager

1. update all packege
```bash
apt update
sudo apt update
```
2. install packegae

```bash
apt install nano
sudo apt install nano
```
3. apt remove nano
```bash
sudo apt remove nano 
```
4. Want to see processing on shell
```bash
top
```
```bash
htop (apt install htop)
```
5. Kill the process
```bash
kill -9 <processId>
```# Linux-Command
