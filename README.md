# SQL_Murder_Mystery

Overview:
The SQL Murder Mystery is designed as both a self-directed lesson to learn SQL concepts and commands and a fun game for experienced SQL users to solve an intriguing crime. Participants are tasked with solving a murder mystery by querying a database and analyzing the provided data.

Link: https://mystery.knightlab.com/

How to Solve:
If you're ready to solve the mystery, you can access the web-based version at mystery.knightlab.com. For those new to SQL, starting with the walkthrough is recommended to learn the necessary SQL concepts and commands. It won't cover everything about SQL but should provide enough guidance to solve the mystery.

What's Included:
If you prefer to solve the mystery on your own computer, you'll need the following:

sql-murder-mystery.db: SQLite database file containing the data for the mystery.
prompt: Depending on your SQL experience level, choose either the prompt_beginner or prompt_experienced file.
reference: A crash course on SQL concepts and commands.
A SQLite environment of your choice: For beginners, SQLiteStudio is recommended for its user-friendly graphical interface.
Getting Started:
For SQL beginners: Start with the reference, read the prompt_beginner file, then install SQLiteStudio and load the sql-murder-mystery.db file. If you encounter difficulties, refer back to the reference or file a GitHub issue for assistance.
For experienced SQL users: Read the prompt_experienced file, then download the sql-murder-mystery.db file and use your preferred SQL environment to solve the mystery. You can refer to the reference to refresh your memory of SQL concepts.
Checking the Solution:
Once you've identified the murderer, write their name into the solution using the provided query:

sql
INSERT INTO solution VALUES (1, "Insert the name of the person you found here");
SELECT value FROM solution;

Authors:
Joon Park
Cathy He
Inspiration:
This murder mystery was inspired by a crime in the neighboring Terminal City.
