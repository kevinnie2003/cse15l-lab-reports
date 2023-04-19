# Lab 1 Instructions
By Kevin Nie

*This is an tutorial about how to log into a course-specific account on ieng6.*

1. First, you should download Virtual Studio Code. This is a very powerful tool.
   [VS Code Download Link](https://code.visualstudio.com)
   <img width="1440" alt="截屏2023-04-05 18 17 40" src="https://user-images.githubusercontent.com/122497019/230248440-e89b5c99-61c1-4b3e-8df8-51cf9bb971ae.png">

2. After installing VS Code, you should use your computer to connect remotely. Your account name is available at [here](https://sdacs.ucsd.edu/~icc/index.php). You may want to reset your password, but wait for 15 minutes before trying to log in.
   Here is the tutorial if you want to reset your password: [[TUTORIAL] How to Reset your CSE 15L Password](https://drive.google.com/file/d/17IDZn8Qq7Q0RkYMxdiIR0o6HJ3B5YqSW/view)
3. Open a new terminal in VS Code, enter 
```
ssh cs15lsp23??@ieng6.ucsd.edu
```
   where "??" is your identical two letter of your account. You may find your username here: https://sdacs.ucsd.edu/~icc/index.php
   

   Then you should enter "yes" to use your password to log in. After entering your password correctly, you will log in and see a similar output:
   
   <img width="700" alt="截屏2023-04-05 17 45 53" src="https://user-images.githubusercontent.com/122497019/230249502-f6d9302b-2c4b-4283-8d76-10abe0b90b7e.png">

4. Try some commands now! Try commands like cd, ls, pwd, mkdir, cp, and cat.
   Here is an example where I want to enter one of my classmates' directory but got "permission denied". Then I change to the public directory and listed the files there. I used cd to change directory and ls to list files or directories.
<img width="1312" alt="截屏2023-04-05 18 33 40" src="https://user-images.githubusercontent.com/122497019/230250372-7ef9fc62-d8cb-4a2b-a1d1-e5074f30359b.png">
   Here's another example where I copied hello.txt from cs15lsp23/public directory by using command cp. Then I copied README.md from my wavelet directory. I used cat to read data from the file and give their content as output.
<img width="1146" alt="截屏2023-04-19 15 22 28" src="https://user-images.githubusercontent.com/122497019/233212607-dfeac3d4-0ed7-461f-ab58-3f273743027f.png">

Good luck on playing with Linux!
