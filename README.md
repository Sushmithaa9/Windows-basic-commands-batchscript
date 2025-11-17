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
<img width="712" height="49" alt="image" src="https://github.com/user-attachments/assets/058cff0c-3dd5-4f36-8447-08f6bff59207" />


Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="684" height="49" alt="image" src="https://github.com/user-attachments/assets/ab1df1b4-e337-4f8a-ba4a-396baa448e83" />



Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="669" height="81" alt="image" src="https://github.com/user-attachments/assets/20a01e3c-cb84-48bd-a846-2732ed0e0935" />


Create the file hello.txt using echo and redirection
## COMMAND AND OUTPUT
<img width="736" height="70" alt="image" src="https://github.com/user-attachments/assets/b717fc65-6f5d-48e9-a751-249bfc46a5a7" />

Copy the file hello.txt into the file hello1.txt
## COMMAND AND OUTPUT
<img width="762" height="89" alt="image" src="https://github.com/user-attachments/assets/ce34f8bd-99d2-4cee-a62b-637d405f09bb" />

Remove the file hello1.txt
## COMMAND AND OUTPUT
<img width="656" height="74" alt="image" src="https://github.com/user-attachments/assets/cbdec64d-e8a0-42aa-adcf-3290dd2ad6cb" />


List out the file hello1.txt in the current directory
## COMMAND AND OUTPUT
<img width="686" height="175" alt="image" src="https://github.com/user-attachments/assets/152431f2-c777-4edd-93c4-fb9e8c10fb18" />


List out all the associated file extensions 
## COMMAND AND OUTPUT
<img width="686" height="1042" alt="image" src="https://github.com/user-attachments/assets/bc339a3f-fddb-4746-8bf1-f36c986399d8" />



Compare the file hello.txt and rose.txt
## COMMAND AND OUTPUT
<img width="713" height="178" alt="image" src="https://github.com/user-attachments/assets/cb70c096-e256-41a4-81b3-1bb9e39f8ba6" />


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
<img width="602" height="130" alt="image" src="https://github.com/user-attachments/assets/250c9670-aad6-43a4-81f4-14f60d1732eb" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="663" height="321" alt="image" src="https://github.com/user-attachments/assets/3b1e9da4-6c9d-4bc7-8adb-bf2153812f60" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
<img width="517" height="183" alt="image" src="https://github.com/user-attachments/assets/348d7c71-4852-4688-815a-97f211a4624d" />




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="452" height="85" alt="image" src="https://github.com/user-attachments/assets/0b3977b4-985f-4716-88f1-b30fbc065091" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="499" height="160" alt="image" src="https://github.com/user-attachments/assets/6c2b06a9-5e77-412f-b5b0-990e858b4a80" />

<img width="465" height="159" alt="image" src="https://github.com/user-attachments/assets/5bb1c22e-16ff-4e97-b6f9-cbc7582d96a1" />

<img width="508" height="166" alt="image" src="https://github.com/user-attachments/assets/1c3c7e01-ff0d-491b-994b-48da5d7a3cd8" />


# RESULT:
The commands/batch files are executed successfully.

