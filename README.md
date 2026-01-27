# Codebreaker2025
This repo contains the sourcecode for the 2025 NSA Codebreaker Challenge

## Download instructions
```bash
git clone https://github.com/Astrixo/Codebreaker2025
```
```bash
cd Codebreaker2025/Tasks
```

## Checking your answers
The success message and badge are zipped in a password protected zip folder in each task's folder.
```bash
unzip task1Badge.zip
```
Enter the password when prompted.
## Password Formats

**Task 1** - SHA1 hash of the suspect file
```bash
sha1sum <path/to/file>
```
**Task 2** - SHA1 hash of the sum of all suspect IP addresses

192.168.1.1 = 362
```bash
echo -n "362" | sha1sum
```
**Task 3-7** - COMING SOON 