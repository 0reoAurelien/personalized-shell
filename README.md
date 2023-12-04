# Lab Report for ENSEASH Shell

## Overview
This project, titled ENSEASH Shell, is a simple shell implementation developed in C. The shell is designed to execute commands, provide information about their execution, and support various features such as command execution with arguments, exit status display, and time measurement.

## Project Structure
The project consists of a single C file, `enseash.c`, implementing the ENSEASH Shell. The code is well-organized and divided into functions to enhance readability and maintainability. The main components include:

- **display_welcome():** Displays a welcome message upon launching the shell.
- **display_prompt():** Generates and displays the prompt, including exit status, signal, and execution time.
- **enseash_exit():** Displays a farewell message when exiting the shell.
- **disp_NewLine():** Writes a new line character to the shell.
- **readCommand():** Reads user input, ensuring no errors occur, and handles the exit command.
- **execute_cmd():** Executes the entered command, capturing information such as exit status and execution time.

## Features
The ENSEASH Shell supports various features as outlined in the project specifications:

1. **Welcome Message and Prompt:** Displays a welcome message and provides a user-friendly prompt.

2. **Command Execution:** Executes simple commands entered by the user and returns to the prompt.

3. **Exiting the Shell:** Allows the user to exit the shell by typing 'exit' or using `<Ctrl>+D`.

4. **Displaying Command Status:** Shows the exit code or signal of the previous command in the prompt.

5. **Measuring Command Execution Time:** Utilizes `clock_gettime` to measure the execution time of commands.

6. **Executing Complex Commands:** Handles commands with arguments seamlessly.

7. **Redirections with `<` and `>`:** Manages input and output redirection.

8. **Pipe Redirection with `|`:** Implements pipe redirection to connect the output of one command to the input of another.

9. **Running Commands in the Background with `&`:** Supports running commands in the background, displaying immediate prompts.

## Recommendations
While the project meets the specified requirements, there are some potential enhancements:

- **Error Handling:** The code could benefit from additional error handling, such as validating user input for potential errors.

- **Code Comments:** Though generally well-commented, adding comments for complex sections or algorithms can further improve code understanding.

- **Documentation:** Consider adding inline documentation to explain the purpose and usage of specific functions or sections of code.

## Conclusion
The ENSEASH Shell is a functional and well-implemented micro shell with support for essential features. It provides a solid foundation for further development and learning in the realm of shell programming. The code is clean, adheres to coding standards, and demonstrates proficiency in C programming.

Feel free to explore, enhance, and customize the ENSEASH Shell to meet your specific needs. If you have any questions or need assistance, don't hesitate to reach out. Happy coding!
