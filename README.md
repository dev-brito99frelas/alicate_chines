# alicate_chines
É um repositório dedicado a resolução de problemas, e configuraçoẽs.  

## Criar pendrive bootavel windows estando em uma máquina linux:
-  Levando em conta que qualquer máquina Linux já vem com python 3 instalado, caso não tenha vindo acompanhado com o pip:
```
  sudo apt install python3-pip && pip3 --version      
```
-  Pois bem, a ferramenta que criaremos o pendrive Bootável do window será o [woeusb](https://github.com/WoeUSB/WoeUSB-ng) que é instalado pelo pip.
```  
  sudo apt install git p7zip-full python3-pip python3-wxgtk4.0 grub2-common grub-pc-bin && sudo pip3 install WoeUSB-ng
```  
- Agora se tudo ocorreu corretamente é só mandar bala, baixar a iso abrir o programa, e fazer o pendrive bootável. 
- _Obs: Vale lembrar que se para base - Fedora o que muda:_  
```  
  sudo dnf install git p7zip p7zip-plugins python3-pip python3-wxpython4 && sudo pip3 install WoeUSB-ng
```
