## Instalar Chocolatey
Para empezar a instalar el chocolatey lo primero de nada es poner este comando (Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))) que lo que hace es preparar nuestra powershell para la ejecucion de scripts externos y es necesario para instalar chocolatey.
![Local](https://github.com/luradur094/Chocolatey/blob/main/imagenes/Captura1.PNG)

Tras poner este comando ponemos el siguiente que sera (choco install vlc) que el cual nos instalara el programa vlc a nuestro sistema enseñando el proceso de instalacion en la PowerShell mientras se instala al finalizar nos saldra el programa en la pantalla de inicio para que lo podamos ejecutar cunado queramos.
![Local](https://github.com/luradur094/Chocolatey/blob/main/imagenes/Captura2.PNG)

Para instalar los programas ponemos choco install seguido del programa que queremos instalar y se instalara sin problemas
