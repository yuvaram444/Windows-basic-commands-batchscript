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
md folder_name
cd folder name
```
<img width="948" height="129" alt="image" src="https://github.com/user-attachments/assets/1a45f0b9-a5fa-4a7d-9637-a0123a57ac0e" />


Remove the directory "my-folder"
## COMMAND AND OUTPUT
```
rm folder_name
```
<img width="952" height="108" alt="image" src="https://github.com/user-attachments/assets/895371cd-8ef2-46d4-ac81-02128ba031a7" />



Create the file Rose.txt
## COMMAND AND OUTPUT
```
type nul > Rose.txt
```
<img width="937" height="40" alt="image" src="https://github.com/user-attachments/assets/deda1ee9-7cb4-4dde-b609-955090e20f2e" />


Create the file hello.txt using echo and redirection
## COMMAND AND OUTPUT
```
echo Hello World > hello.txt
```
<img width="950" height="45" alt="image" src="https://github.com/user-attachments/assets/a36b1551-6a4f-4445-8c24-043d43e40731" />



Copy the file hello.txt into the file hello1.txt
## COMMAND AND OUTPUT
```
copy hello.txt hello1.txt
```
<img width="955" height="63" alt="image" src="https://github.com/user-attachments/assets/04cab519-5a17-4a3a-809c-595e3556f52a" />



Remove the file hello1.txt
## COMMAND AND OUTPUT
```
del hello1.txt
```
<img width="956" height="37" alt="image" src="https://github.com/user-attachments/assets/09f037bf-ca14-45c7-876d-03e7e77ae70a" />



List out the file hello1.txt in the current directory
## COMMAND AND OUTPUT
```
dir hello1.txt
```
<img width="952" height="130" alt="image" src="https://github.com/user-attachments/assets/dd16f8fa-a027-4b19-ba04-5e2e8e8c0561" />



List out all the associated file extensions 
## COMMAND AND OUTPUT
```
assoc
```
<img width="946" height="1093" alt="image" src="https://github.com/user-attachments/assets/af5454a9-99b3-4f81-bfed-c08f96b9aba1" />




Compare the file hello.txt and rose.txt
## COMMAND AND OUTPUT
```
fc hello.txt Rose.txt
```
<img width="956" height="144" alt="image" src="https://github.com/user-attachments/assets/624da033-6c49-4b1c-988f-30a05256efed" />





## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT



# RESULT:
The commands/batch files are executed successfully.

