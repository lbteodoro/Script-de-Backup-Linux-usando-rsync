#! /bin/sh

#Variaveis do sistema
DIRORIGEM=(Diretorio de origem dos arquivos)
DIRBACKUP=(Diretorio onde será sincronozado os arquivos)

#Copia os arquivos
rsync -hva $DIRORIGEM $DIRBACKUP
