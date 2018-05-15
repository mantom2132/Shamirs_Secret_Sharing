# Shamirs_Secret_Sharing
This project featuresz a java implementation of Shamir's secret sharing scheme coded in Java and a GUI made using netbeans 
to demonstrate how this scheme works.

BUILD/RUN instruction:
1. Open Netbeans
2. Team> Remote> Clone
3. Add repository url, fill in username and password. 
4. Click on Next.
5.Select master* branch and click Next.
6. Select Destination directory of your choosing.
7. Click on Finish.
8. Build Project
9. Run project

The GUI will appear, you will be prompted to:
1. Input a secret (please keep bellow 10 digits, use only numbers)
2. Input a number of shares you wish to generate(again keep bellow 10, only numbers)
3.Input the threshold number of shares. 
4.Click on Input Secret, Input Numberof Shares and Input threshold. 
5.Click on Generate shares. The shares generated will appear.

In order to reconstuct the secret:
1.input the number of shares to input
2.Input which share to input
3.Click on Input Shares. 
4. Repeat the process in steps 2-3 for as many times as the value you entered on the number of shares to input.
5. If the nyumber of shares you inputed is equal to the threshold number of shares, the correct secret will be reconstructed
otherwise, a number different to the secret will appear.
