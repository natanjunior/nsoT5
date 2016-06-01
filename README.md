# Trabalho 5 - Sistemas Operacionais 
### Sistemas de Arquivo – undelete de arquivo em pen-drive
Os trabalhos de S.O. normalmente exigem muita dedicação e persistência do aluno, pois costumam tomar muito tempo e apresentam um grande overhead inicial (exigem que vocês tomem conhecimento do ambiente, das chamadas de sistema, da estrutura de dados, etc …), além de outras dificulades... No entanto, só através da prática é que vocês irão tomar uma maior intimidade com os conceitos S.O. e terão condições de fazerem programas que explorem mais a fundo as possibilidades de um Sistema Computacional.
- Em um pen-drive usb, formatá-lo com o sistema de arquivos FAT 32.
- Criar no diretório raiz 5 subdiretórios: SD0, SD1, SD2, SD3 e SD4
- Copiar em cada subdiretório 371 arquivos com aproximadamente 1 KB.
- Criar no subdiretório SD1, mais 3 subdiretórios: SD1.0, SD1.1 e SD1.2
- Copiar no diretório raiz o máximo de arquivos possíveis, cada um com aproximadamente 512 Bytes.
- Copiar no subdiretório de SD1.0 o dobro do número de arquivos existentes no diretório raiz, cada arquivo com aproximadamente 4 KB.
- Copiar no subdiretório de SD1.1 o triplo do número de arquivos existentes no diretório raiz, cada arquivo com aproximadamente 8 KB.
- Copiar em DS1.2 arquivos de vídeo, de forma a encher o pen-drive.
- Apagar aleatoriamente, os arquivos deletados não podem ter sido criados sequencialmente, 100 arquivos de aproximadamente 1, 4 e 8 KB, em diferentes diretórios.
- Copiar 10 arquivos textos distintos, cada um com aproximadamente 40 KB
- Apagar o 3º, o 5º e o 7º arquivos criados.
- Fazer o undeletes do 5º arquivo:
  1. de forma manual, utilizando algum visualizador de clusters ( mostrar como se faz ao professor em sala de aula; e
  2. de forma automática (o programa que você implementou na linguagem C/C++).
