# Instalando STS - Spring Tool Suite no LINUX

Baixe: A versão baseada na IDE Eclipse para LINUX.

Link:

https://spring.io/tools

$ cd Downloads

$ sudo mv spring-tool-suite-4-4.14.1.RELEASE-e4.23.0-linux.gtk.x86_64.tar.gz /opt

$ cd /opt/

$ sudo tar zxvf spring-tool-suite-4-4.14.1.RELEASE-e4.23.0-linux.gtk.x86_64.tar.gz

$ cd sts-4.14.1.RELEASE/

$ sudo ./SpringToolSuite4

$ sudo vi /usr/share/applications/stsLauncher.desktop

Copie e cole dentro do arquivo aberto após executar o comando acima, e altere as linhas que possuem versões caso não seja a mesma da qual foi instalada, se necessário alterar as versão use a tecla "i" para fazer o INSERT no arquivo e ESC após alterar algo, e para finalizar use a tecla ":" para inserir comandos, nesse caso para escrever e sair desse arquivo, "w = significa write" e "q = significa quite", digite wq e aperte a tecla enter.

[Desktop Entry]

Name=Spring Tool Suite

Comment=Spring Tool Suite 4.14.1

Exec=/opt/sts-4.14.1.RELEASE/SpringToolSuite4

Icon=/opt/sts-4.14.1.RELEASE/icon.xpm

StartupNotify=true

Terminal=false

Type=Application

Categories=Development;IDE;Java;
