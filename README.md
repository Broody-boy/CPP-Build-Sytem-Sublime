# Recreate Sublime C++ Setup
How to recreate Sublime C++ setup:

#### Restore Sublime settings:
   - Go to Preferences > Settings and copy paste the contents of the Preferences.sublime-settings of this repo and save.

#### Restore Build System for C++ in Sublime Text:

1) Setup the layout as given in GFG article:  
  a) View > Layout > Columns : 3  
  b) View > Groups > Max Columns : 2.

2) Make and move the c++, in.txt and out.txt files to their respective sections.

3) Go to Tools > Build System > New Build System and copy paste the contents of CPP.sublime-build file of this repo to it.

4) Save it also as CPP.sublime-build

5) Go to Tools > Build System menu and select our CPP build system. A tick will now appear alongside it in the same menu as it is has now become the default Build System.

6) Go to the C++ file and then run using: ctrl + B

- Source of this: [GFG Article](https://www.geeksforgeeks.org/setting-up-sublime-text-for-cpp-competitive-programming-environment/)

**Note:** The in.txt and out.txt files should be in same location as the C++ file.

**Tip**: Location of both CPP.sublime-build and Preferences.sublime-settings files: "C:\Users\Arshdeep\AppData\Roaming\Sublime Text\Packages\User"
