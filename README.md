# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

## COMMAND AND OUTPUT
```
mkdir my-folder
```
<img width="500" height="80" alt="Screenshot 2026-03-19 205843" src="https://github.com/user-attachments/assets/5bc68962-dd24-40b1-af0f-dc51d4454fdc" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT
```
rmdir my-folder
```
<img width="406" height="61" alt="image" src="https://github.com/user-attachments/assets/10f14f20-7723-4412-a3c9-41a7e3f97a37" />

Create the file Rose.txt

## COMMAND AND OUTPUT
```
COPY CON Rose.txt
dir Rose.txt
```
<img width="514" height="115" alt="Screenshot 2026-03-19 210103" src="https://github.com/user-attachments/assets/76b081cf-6383-421f-8ffd-df975df014dc" />
<img width="590" height="217" alt="Screenshot 2026-03-19 210110" src="https://github.com/user-attachments/assets/c3201154-80aa-4be1-b0c8-f9e9f01b56e2" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
```
echo “hello world” > hello.txt
type hello.txt
```
<img width="547" height="118" alt="image" src="https://github.com/user-attachments/assets/0f026ad4-d759-45e4-b278-a0a67ddfefa3" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
```
copy hello.txt hello1.txt
```
<img width="707" height="141" alt="image" src="https://github.com/user-attachments/assets/4a4ee42a-1be0-42fd-8ee0-a3e9183b5932" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
```
del hello1.txt
```
<img width="617" height="137" alt="image" src="https://github.com/user-attachments/assets/cab865aa-53d9-4689-899e-16d3690ca328" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
```
dir hello1.txt
```
<img width="612" height="197" alt="image" src="https://github.com/user-attachments/assets/a490db9c-189a-4c50-ad47-7c53ef12391f" />


List out all the associated file extensions 

## COMMAND AND OUTPUT
```
assoc | more
```
<img width="786" height="465" alt="image" src="https://github.com/user-attachments/assets/fdee1138-558e-4a3d-9f6a-63908f08873e" />

Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
```
fc hello.txt Rose.txt
```
<img width="651" height="202" alt="image" src="https://github.com/user-attachments/assets/85e43e7e-6ec3-45de-a14f-6b2ccc43c993" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

<img width="832" height="502" alt="image" src="https://github.com/user-attachments/assets/dbb3ec3b-99d7-441b-b732-96e143b9db45" />




## OUTPUT

<img width="672" height="243" alt="image" src="https://github.com/user-attachments/assets/4a1b9eba-eaff-4995-852d-ed608279df93" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT


<img width="443" height="162" alt="image" src="https://github.com/user-attachments/assets/ef6403e9-a898-4946-a0c1-73efe9c5efd4" />


Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="767" height="257" alt="image" src="https://github.com/user-attachments/assets/2b3987dd-f852-47e6-9955-553af39eafdc" />

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="650" height="471" alt="image" src="https://github.com/user-attachments/assets/26edcd52-d112-4284-977d-d08cc4d106f8" />


# RESULT:
The commands/batch files are executed successfully.

