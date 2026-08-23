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
<img width="1341" height="620" alt="image" src="https://github.com/user-attachments/assets/8c6ca999-de3d-4650-8bb7-5b477eb2edc2" />

## COMMAND AND OUTPUT
Remove the directory "my-folder"
<img width="1518" height="250" alt="image" src="https://github.com/user-attachments/assets/20f66367-972a-4946-80df-fc6c836b7218" />

## COMMAND AND OUTPUT
Create the file Rose.txt
<img width="1027" height="576" alt="image" src="https://github.com/user-attachments/assets/5671169e-7fdc-469c-801d-608abdb49483" />

## COMMAND AND OUTPUT
Create the file hello.txt using echo and redirection
<img width="1230" height="266" alt="image" src="https://github.com/user-attachments/assets/745ded88-6d81-404f-837a-eb949acf6545" />

## COMMAND AND OUTPUT
Copy the file hello.txt into the file hello1.txt
<img width="1117" height="270" alt="image" src="https://github.com/user-attachments/assets/e008b168-5e39-40eb-9ebe-600eed53d9d1" />

## COMMAND AND OUTPUT
Remove the file hello1.txt
<img width="1272" height="643" alt="image" src="https://github.com/user-attachments/assets/bba982a1-6a97-4e59-bd5b-db476f25e0aa" />

## COMMAND AND OUTPUT
List out the file hello1.txt in the current directory
<img width="844" height="633" alt="image" src="https://github.com/user-attachments/assets/3a308223-01a3-4847-857a-d890b2ad8cb3" />

## COMMAND AND OUTPUT
List out all the associated file extensions 
<img width="855" height="640" alt="image" src="https://github.com/user-attachments/assets/74d38686-3da8-47ff-a306-cac33e14f342" />

## COMMAND AND OUTPUT
Compare the file hello.txt and rose.txt
<img width="770" height="218" alt="image" src="https://github.com/user-attachments/assets/9bc03589-5125-416f-a6c9-b97f57d67fdc" />

## COMMAND AND OUTPUT
## Exercise 2: Advanced Batch Scripting
## OUTPUT
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

<img width="864" height="109" alt="image" src="https://github.com/user-attachments/assets/a8939a37-6984-4157-a56c-5976ea73f2ed" />

Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.

## OUTPUT
<img width="670" height="302" alt="image" src="https://github.com/user-attachments/assets/ed9999bf-3daa-4a2b-89fc-efdfc03de375" />
Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.

## OUTPUT
<img width="785" height="166" alt="image" src="https://github.com/user-attachments/assets/6c990f7f-2969-483e-90d8-377b56940abd" />
Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="727" height="80" alt="image" src="https://github.com/user-attachments/assets/1f056c4e-6abc-4599-8bfb-8894beb4c9b4" />

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.

## OUTPUT
<img width="1191" height="484" alt="image" src="https://github.com/user-attachments/assets/c09a299b-a65d-48db-a214-3cbba162742b" />
# RESULT:
The commands/batch files are executed successfully.

