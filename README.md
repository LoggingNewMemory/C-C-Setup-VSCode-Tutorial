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

6. Press new and add MingW directory, by default is ```C:\msys64\ucrt64\bin``` <br />

![image](https://github.com/user-attachments/assets/9aa3d3f3-1fcc-4c1f-81e8-1a7ddedf0771) <br />

7. Press Ok and close all windows

5. Press Ok

## Verify if MinGW correcty installed

1. Open Command Prompt <br />

![image](https://github.com/user-attachments/assets/fbc0a6e0-b2fc-46cf-954a-532cd3466c55) <br />

2. type:
```gcc --version```
```g++ --version```
```gdb --version```

![image](https://github.com/user-attachments/assets/3e611517-3615-4ade-9110-6e7739994e60) <br />


## Configure VSCode

1. Open VSCode and install "C / C++ Extension Pack" extension <br />

![image](https://github.com/user-attachments/assets/c32ccdb4-b660-4401-be3a-0d43702fa646) <br />

2. Write hello world program (Or you can paste my code)

```
#include <stdio.h>

int main() {
    printf("Hello Kanagawa Yamada");
}
```

![image](https://github.com/user-attachments/assets/b9e728ad-d6a2-4ff2-902b-db3bc1d1a1b9) <br />

3. Run the program <br />

![image](https://github.com/user-attachments/assets/2541aed9-2c66-4763-ae29-9ff2e547a323) <br />

4. You can see the output on terminal tab <br />

![image](https://github.com/user-attachments/assets/7dc8647e-899e-473e-81c6-f7de4fd65e93) <br />

## Troubleshooting

- If you enconter run error, try to delete .vscode folder, because that directory contains runner configuration file (Don't worry, it will regenerate automatically if it's deleted)

![image](https://github.com/user-attachments/assets/ca400c0e-192d-4038-841f-7d4928093466) <br />

## Pro Tip

- If your terminal is overfilled just type ```clear```
