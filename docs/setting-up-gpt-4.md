# Setting Up GPT-4

Step 1 - Install OpenAI packages

```
pip install openai
```

Step 2 - create a new API key at [https://platform.openai.com/api-keys](https://platform.openai.com/api-keys)

![alt](https://drive.google.com/file/d/1xfs_SZVbK6hhDf2-_AMH4uCxdgFlGiMK/view?usp=sharing)

Step 3 - Run the interpreter command after installing open-interpreter and enter your newly generated api key

![alt](https://drive.google.com/file/d/1avLeCIKvQV732mbrf-91s5T7uJfTLyCS/view?usp=sharing)

or

**FOR MACOS :**

1.  **Open Terminal**: You can find it in the Applications folder or search for it using Spotlight (Command + Space).
    
2.  **Edit Bash Profile**: Use the command `nano ~/.bash_profile` or `nano ~/.zshrc` (for newer MacOS versions) to open the profile file in a text editor.
    
3.  **Add Environment Variable**: In the editor, add the line below, replacing `your-api-key-here` with your actual API key:
    
    ```
    export OPENAI\_API\_KEY='your-api-key-here'
    ```
    
4.  **Save and Exit**: Press Ctrl+O to write the changes, followed by Ctrl+X to close the editor.
    
5.  **Load Your Profile**: Use the command `source ~/.bash_profile` or `source ~/.zshrc` to load the updated profile.
    
6.  **Verification**: Verify the setup by typing `echo $OPENAI_API_KEY` in the terminal. It should display your API key.
    

**FOR WINDOWS :**

1.  **Open Command Prompt**: You can find it by searching "cmd" in the start menu.
    
2.  **Set environment variable in the current session**: To set the environment variable in the current session, use the command below, replacing `your-api-key-here` with your actual API key:
    
    ```
    setx OPENAI\_API\_KEY "your-api-key-here"
    ```
    
    This command will set the OPENAI\_API\_KEY environment variable for the current session.
    
3.  **Permanent setup**: To make the setup permanent, add the variable through the system properties as follows:
    
    *   Right-click on 'This PC' or 'My Computer' and select 'Properties'.
        
    *   Click on 'Advanced system settings'.
        
    *   Click the 'Environment Variables' button.
        
    *   In the 'System variables' section, click 'New...' and enter OPENAI\_API\_KEY as the variable name and your API key as the variable value.
        
4.  **Verification**: To verify the setup, reopen the command prompt and type the command below. It should display your API key: `echo %OPENAI_API_KEY%`
