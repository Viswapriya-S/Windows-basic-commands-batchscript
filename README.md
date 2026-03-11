# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript
Name: Viswapriya 
Reg:no. 25018876
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
<img width="642" height="114" alt="Screenshot 2026-03-11 091526" src="https://github.com/user-attachments/assets/4bdab874-5381-4c26-af89-02bf6ae013b1" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="494" height="64" alt="Screenshot 2026-03-11 091804" src="https://github.com/user-attachments/assets/181a05ae-770a-4bd1-b334-a2fa3be811a5" />


Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="696" height="378" alt="Screenshot 2026-03-11 092117" src="https://github.com/user-attachments/assets/4c6da4e6-d987-4a66-b936-649f92904f4d" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="623" height="121" alt="Screenshot 2026-03-11 092211" src="https://github.com/user-attachments/assets/cb3ff5e4-cefd-4913-a57f-87bd153240d0" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="499" height="144" alt="Screenshot 2026-03-11 092253" src="https://github.com/user-attachments/assets/2c36315c-f652-414d-83df-8a5489f332ee" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="546" height="244" alt="Screenshot 2026-03-11 092355" src="https://github.com/user-attachments/assets/5ded07fd-8339-4b03-a122-47db21c03b4c" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="546" height="244" alt="Screenshot 2026-03-11 092355" src="https://github.com/user-attachments/assets/8035a3ec-4abb-464f-ac32-be4c0e318d0e" />

List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="687" height="730" alt="Screenshot 2026-03-11 092444" src="https://github.com/user-attachments/assets/dcaf1a16-69c3-46db-a8b3-3b9bccf35fcc" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="543" height="222" alt="Screenshot 2026-03-11 092625" src="https://github.com/user-attachments/assets/9a90df64-c16b-488b-9559-bea23b260faf" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
<img width="657" height="289" alt="Screenshot 2026-03-11 085556" src="https://github.com/user-attachments/assets/5b8c9f6a-9d61-4dbf-b7b3-2f0f85310c92" />

<img width="487" height="156" alt="Screenshot 2026-03-11 092714" src="https://github.com/user-attachments/assets/5e398271-7500-4cd5-9409-9e81b025cd8c" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="672" height="491" alt="Screenshot 2026-03-11 092749" src="https://github.com/user-attachments/assets/50897251-a7f1-43ca-ba55-32e9a91d150b" />

<img width="592" height="226" alt="Screenshot 2026-03-11 092817" src="https://github.com/user-attachments/assets/f3b74e91-c2f2-43fc-96cd-1f278ceea8e8" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
<img width="389" height="186" alt="Screenshot 2026-03-11 092842" src="https://github.com/user-attachments/assets/d2c872ab-eb78-472e-a62c-d1ab4509d39f" />

<img width="514" height="240" alt="Screenshot 2026-03-11 092924" src="https://github.com/user-attachments/assets/b7eccd4a-3f9e-422b-82ff-9edf38c153c8" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="410" height="198" alt="Screenshot 2026-03-11 093256" src="https://github.com/user-attachments/assets/22010174-db07-4dc3-a0a6-9644c1f2a7f8" />

<img width="610" height="235" alt="Screenshot 2026-03-11 093242" src="https://github.com/user-attachments/assets/f3cb203b-25b5-4eca-98ea-dcfe2df668a0" />

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="504" height="532" alt="Screenshot 2026-03-11 093450" src="https://github.com/user-attachments/assets/b7f8b384-eecf-4af3-9982-a21baca753a4" />

<img width="509" height="411" alt="Screenshot 2026-03-11 093514" src="https://github.com/user-attachments/assets/0f0a3881-5625-4a9f-931d-953ec4168aa6" />

# RESULT:
The commands/batch files are executed successfully.

