# C / C++ Setup Tutorial For Visual Studio Code For Windows
### Tutorial By: Kanagawa Yamada

Prerequisites: 
1. [VSCode Installer](https://code.visualstudio.com/download)
2. [MSYS2](https://www.msys2.org/) 

## Configuring MinGW Compiler

1. Download MSYS2, and install it (Do not change anything)
2. Search for "MSYS2 MINGW64" app <br />

![image](https://github.com/user-attachments/assets/17909a80-fd61-4a84-8dd0-9e1e2190c172) <br />

3. Run ```pacman -S --needed base-devel mingw-w64-ucrt-x86_64-toolchain``` On MSYS2 Terimnal
4. Type y and let the installation finish <br />

![image](https://github.com/user-attachments/assets/7e9c043b-68e9-4b88-8e9c-2102f5943439) <br />

## Configure System Path

1. Go to control panel and search for "Edit the system environment variables" <br />
   
![image](https://github.com/user-attachments/assets/97037370-2977-4fe2-8df7-d858d6568a8e) <br />

2. Go to "Environment Variables" <br />
   
![image](https://github.com/user-attachments/assets/67a12905-d03f-447b-ae41-6fa17250a6dd) <br />

3. Search for Path in System Variables, and double click it <br />

![image](https://github.com/user-attachments/assets/79cc7141-999b-4eb0-8823-d5d1d9ce2e5c) <br />


5. Press Ok

## Configure VSCode

1. 
