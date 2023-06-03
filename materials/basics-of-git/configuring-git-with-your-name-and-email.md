# Configuring Git with Your Name and Email

In the character-driven world of code organization, where every detail matters, configuring Git with your name and email is an important step. Git uses this information to attribute commits to the correct author. By setting up your name and email, you establish a clear identity within your project's history. In this material, we will guide you through the process of configuring Git with your name and email. Let's get started!

## Configuring Git on Windows, Linux, and Mac

To configure Git with your name and email, follow these steps:

1. Open a terminal or command prompt on your computer.

2. Type the following command, replacing `"Your Name"` with your actual name:
   ```
   git config --global user.name "Your Name"
   ```

3. Press Enter to execute the command. This sets your name as the global Git user name.

4. Next, enter the following command, replacing `"youremail@example.com"` with your actual email address:
   ```
   git config --global user.email youremail@example.com
   ```

5. Press Enter to execute the command. This sets your email as the global Git user email.

## Verifying Your Configuration

To verify that your name and email are properly configured, follow these steps:

1. Open a terminal or command prompt.

2. Enter the following command:
   ```
   git config --global user.name
   ```

3. Press Enter to display the configured name.

4. Similarly, enter the following command:
   ```
   git config --global user.email
   ```

5. Press Enter to display the configured email.

If the displayed name and email match your desired configuration, you have successfully configured Git with your name and email.

## Conclusion

Congratulations! You have successfully configured Git with your name and email. This simple configuration step helps establish your identity as a contributor to your projects and allows Git to accurately attribute your commits. By personalizing your Git configuration, you contribute to the character-driven narrative of your code organization journey.
