# Notepad-plus-plus-MIPS-Syntax-Highlighting
Add Syntax Highlighting and AutoCompletion when writing MIPS in Notepad++

### Installation and Usage
1. Download the `userDefineLang.xml` file.
2. Navigate to the `C:\Users\<user>\AppData\Roaming\Notepad++` directory. In that directory you should find other .xml files and possibly a file named userDefineLang.xml.
3. If there isn't such a file in the directory, just copy the file you downloaded into that directory and go to step 5.
4. Otherwise, in order to not lose any other user-defined languages, open the downloaded file, copy everything between the `<UserLang>` and `</UserLang>` tag, including the tags, and paste it *right after the `<NotepadPlus>` tag in the userDefineLang.xml file already present on your computer*.
5. Save the userDefineLang.xml file, restart Notepad++ and under the menu *Language* you should find the *MIPS* language you just installed. Click on it to set it as the language of the current file and you're done!
