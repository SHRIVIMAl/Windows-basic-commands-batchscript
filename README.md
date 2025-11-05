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

<img width="425" height="53" alt="image" src="https://github.com/user-attachments/assets/8aa75f12-a74f-49ff-b19e-1a58afc71ae2" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT

<img width="433" height="45" alt="image" src="https://github.com/user-attachments/assets/75a275d4-ce41-4837-8aae-e3beb921b745" />


Create the file Rose.txt

## COMMAND AND OUTPUT

<img width="513" height="124" alt="image" src="https://github.com/user-attachments/assets/378c1f17-a402-4c05-b74d-8249a0b6a4b8" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT

<img width="509" height="78" alt="image" src="https://github.com/user-attachments/assets/40f56bb7-8a66-44ba-8311-7d4f56ad7f8b" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT

<img width="512" height="129" alt="image" src="https://github.com/user-attachments/assets/5d07d489-206f-4f82-b4a2-fc9e0a980f49" />

Remove the file hello1.txt

## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT

<img width="477" height="184" alt="image" src="https://github.com/user-attachments/assets/b7a5555b-b6a7-45ed-a8e3-f6a16456ef65" />

List out all the associated file extensions 

## COMMAND AND OUTPUT

<img width="458" height="252" alt="image" src="https://github.com/user-attachments/assets/bb2792cb-dc82-41cc-83d5-12e8b4bbf6ad" />

Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

<img width="511" height="187" alt="image" src="https://github.com/user-attachments/assets/e22c9ed9-d6ae-483f-8d86-8d599a2b690f" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="411" height="88" alt="image" src="https://github.com/user-attachments/assets/24c3e515-558a-48b4-afe1-e9aeeec038b0" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT


<img width="510" height="197" alt="image" src="https://github.com/user-attachments/assets/9c6a255e-f048-4370-ad42-ac3c2dfbcc7f" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="371" height="198" alt="image" src="https://github.com/user-attachments/assets/566f5a0d-a25a-413b-95bc-825cce7aa542" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="515" height="191" alt="image" src="https://github.com/user-attachments/assets/1c75a835-9f9f-4613-ae1a-9f1f30d3dc8f" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="485" height="427" alt="image" src="https://github.com/user-attachments/assets/88116656-12cd-4817-ae4d-9a54c83b22c3" />


# RESULT:
The commands/batch files are executed successfully.

