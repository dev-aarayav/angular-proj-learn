# ANGULAR PROJECT FOR WINDOWS 11

## Prerequisites
1. Install WSL from PowerShell Terminal using command: ```wsl --install``` then check status with ```wsl --status```
2. Install a Linux distribution from Microsoft Store (in this case Ubuntu 20.04.6 LTS)
   *NOTE: If you need to access OS files, Open a "File Explorer" window > in the search bar type ```\\wsl$``` > All Ubuntu Distros will appear
3. Other approach will be to use "NVM (Node Version Manager)" to install it so run the following command:
   ```curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash```
4. Then, close the terminal, reopen terminal to ensure the changes take effect. To list all the Node versions available, run command: ```nvm ls-remote --lts```
   *NOTE: Close terminal to apply changes correctly, then continue with next step*
5. OPTIONAL: Open the official [website](https://nodejs.org/en/download/) to validate which is LTS version (in this case is ```20.10.0```).
6. Once you know LTS version, run command: ```nvm install <version x.x.x>``` in this case is ```20.10.0``` (Each node version comes bundled with a version of npm.)
7. OPTIONAL: Set LTS version as default if you have multiple versions installer, run command: ```nvm alias default 20.10.0```
   *NOTE: To list all versions of node installed run command: ```nvm ls```
8.  Then verify once again the node version with ```node -v```
    *NOTE: if you see the following error ```node: /lib/x86_64-linux-gnu/libc.so.6: version `GLIBC_2.28' not found ``` you have to downgrade to a version that supports GLIBC.*
9.  OPTIONAL: Setup Terminal in Visual Studio Code to run WSL Terminal, from ```C:\WINDOWS\System32\cmd.exe``` to ```C:\\Windows\\System32\\bash.exe```


7. Instalar NodeJS LTS (Build Env: https://nodejs.org/es/)
8. Instalar Angular CLI -> <em>npm install -g @angular/cli</em>
9. Revisar que Angular CLI esta instalado -> <em>ng --version</em>
10. Tener instalado un editor de texto potente -> MS Visual Studio Code

## Comandos en la terminal
1. Crear un proyecto de Angular -> <em>ng new "project_name"</em>
- Angular router = Yes
- Types of Style = CSS
2. npm install (Dependencias)
3. ng build (Compilar)
4. ng serve --open (Ejecutar proyecto)


![](https://upload.wikimedia.org/wikipedia/commons/c/cf/Angular_full_color_logo.svg){width='100px'}