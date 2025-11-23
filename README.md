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

<img width="791" height="259" alt="image" src="https://github.com/user-attachments/assets/4b7f38a4-d9c8-4719-aaa2-e500c395fd36" />



Remove the directory "my-folder"

## COMMAND AND OUTPUT

<img width="1128" height="294" alt="image" src="https://github.com/user-attachments/assets/89b76df0-5681-4fd3-a05e-d1793a7cb424" />


Create the file Rose.txt

## COMMAND AND OUTPUT

<img width="817" height="230" alt="image" src="https://github.com/user-attachments/assets/a7f57d8f-a34e-4a30-9f27-a2eeb18718ba" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT

<img width="665" height="128" alt="image" src="https://github.com/user-attachments/assets/f1f83353-d363-4e1f-94f2-4f5449c9cd10" />


Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT

<img width="568" height="135" alt="image" src="https://github.com/user-attachments/assets/ac37d07b-327d-46fa-b7ef-21e6abce6f30" />

Remove the file hello1.txt

## COMMAND AND OUTPUT

<img width="555" height="238" alt="image" src="https://github.com/user-attachments/assets/e8894962-d6b3-4f77-9fc3-99f50e342a48" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT

<img width="520" height="692" alt="image" src="https://github.com/user-attachments/assets/7913ced0-7393-4036-8e81-a64821c17962" />

List out all the associated file extensions 

## COMMAND AND OUTPUT

<img width="521" height="684" alt="image" src="https://github.com/user-attachments/assets/30ee12b7-e048-40bc-be90-1b467291250e" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

<img width="674" height="229" alt="image" src="https://github.com/user-attachments/assets/d375d252-c706-48ea-b4c0-3782742bc8f6" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="471" height="114" alt="image" src="https://github.com/user-attachments/assets/bb211cd1-ed74-41d5-8acd-5c819d2f4ff3" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT


<img width="661" height="229" alt="image" src="https://github.com/user-attachments/assets/10b117a7-855c-430a-ab0d-a79ba9494d5c" />


Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="554" height="189" alt="image" src="https://github.com/user-attachments/assets/1efc4c3a-d9e6-40e1-81ef-96e8324bd0ca" />


Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="449" height="96" alt="image" src="https://github.com/user-attachments/assets/bf8bddd2-9dfb-4d1d-817b-01c38e984b46" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="558" height="397" alt="image" src="https://github.com/user-attachments/assets/2eedcb09-c02f-4be3-a853-985c711ff210" />


# RESULT:
The commands/batch files are executed successfully.

