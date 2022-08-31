# These are the Shell Scripting Basics Exercises of my second week at Alx-Holberton coding school

Exercise 0: pwd  ---> This prints working directory

Exercise 1: ls ---> This shows the list of the content of a  directory

Exercise 2: cd ---> This changes the directory

Exercise 3: ls -l ---> Shows a list of directory contents in long form

Exercise 4: ls -la ---> Shows a list of directory contents in long form, including hidden files

Exercise 5: ls -la ---> This files get arranged in an ordered list

Exercise 6: mkdir /tmp/my_first_directory ---> This will Create a my_first_directory directory inside the tmp directory

Exercise 7: mv /tmp/betty /tmp/my_first_directory/betty ---> This will move the file betty, which is located inside the tmp directory, to the my_first_directory directory, which is also located inside the tmp directory. This exercise wasn't difficult but was finally able to manuover

Exercise 8: rm /tmp/my_first_directory/betty ---> Removed the file betty which was located in tmp/my_first_directory directory.

Exercise 9: rmdir /tmp/my_first_directory --> Removed the directory my_first_directory which was located in the directory tmp.

Exercise 10: cd - ---> Was used to change directory to the previous directory you are in.

Exercise 11: ls -la . .. /boot List --> This showed how flexible ls can be. All files/directories, including hidden files/directories, from 3 separate directories: current directory, parent of working directory, and /boot directory are printed. The ls command allows multiple directories to be listed separated by spaces.

Exercise 12: file /tmp/iamafile ---> This was used to print the type of file "iamafile".

Exercise 13: ln -s /bin/ls ls --> Creates a symbolic link named ls for /bin/ls

Exercise 14: cp -u *.html .. --> This will copy all html files from the current directory to the parent directory, but only copy files that didn't exist in the parent directory or are newer versions than the ones that already exist in the parent directory. The -u option didn't show on the terminal manual page. The -u option copies the file into the directory if its a newer version. If the file doesn't exist in the directory, it will copy over. The -n option works for copying files that don't exist in the parent directory, but it doesn't check if the file is a newer version or not.

Exercise 15: mv [[:upper:]]* /tmp/u ---> This move all files that begin with a capital letter to /tmp/u

Exercise 16: rm *~ --> The *~ tell the rm command to delete all files in the current directory that end with a ~

Exercise 17: mkdir -p welcome/to/school ---> had to look this up. But what it doesis that it Creates directory welcome in current directory. Create directory to inside directory welcome. Create directory school inside directory to. The -p option creates any intermediate directories in the path argument.

Exercise 18: ls -pam --> had to do a bit of research here. Typically it list all files and directories of the current directory, separated by commas. Directory names should end with a /. The listing should be alph ordered, except for dot (.) or dot dot (..), which should be listed at the beginning. The -a option is to show any hidden files. The -p option writes a / at the end of directory names. The -m option streams the output, separating each listing with commas.

Exercise 19: 0 string SCHOOL School data !:mime School --> note: You may have
to run a "file -C -m <filename>. It Creates a magic file called school.mgc that
can be used with the command file to detect School data files. School data
files always contain "SCHOOL" at offset 0.
