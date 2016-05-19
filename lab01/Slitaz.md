# Comandos Linux



  - pwd (Mostra em que diretório está)
  - mkdir /mack (Cria o diretório mack)
  - cd /mack (Vai para o diretório mack)
  - cd (Volta para o diretório anterior)
  - mkdir /trabalho (Criar o diretório trabalho)
  - cd /mack (Vai para o diretório mack)
  - mkdir /textos (Criar o diretório textos)
  - cat > números.txt (Cria o arquivo numeros.txt e acrescenta algo nele)
  - 10
  - 100
  - 50
  - 25
  - 1
  - 2
  - Ctrl + d (Para terminar de acrescentar) 
  - cat números.txt > numeros1.txt > numeros2.txt (Duplica o arquivo números.txt para números1.txt e números2.txt)
  - cp /mack/*.txt /trabalho (copia todos os arquivos .txt para a pasta trabalho)
  - ls -al 
  - chmod 751 numeros.txt (para mudar a permissão para (-rwxr-x--x))
  - chmod 644 numeros.txt (para mudar a permissão para (-rw-r--r--))
  - cd (Volta para o diretório anterior)
  - mkdir /trabalho_feito
  - cp /mack/* /trabalho_feito (copia a pasta mack e todo seu conteúdo para a pasta trabalho_feito)
  - cd /mack (Vai para o diretório mack)
  - rm *.txt (deleta todos os arquivos com extensão .txt)
  - rmdir /mack (deleta o diretório mack)
  - cd /trabalho_feito (entra no diretório trabalho_feito)
  - mv numeros.txt sequencia.txt (Renomeia numeros.txt para sequencia.txt)
  - ls /bin (Lista todos os arquivos da pasta bin)
  - ls /bin > listabin.txt (Guarda a ls dentro de um arquivo chamado listabin.txt)
  - O comando que apaga uma pasta vazia é (rmdir /nome_da_pasta)
  - mv /trabalho_feito lab_unip_01 (Renomeia o diretório trabalho_feito para lab_unip_01)
  - cp interface_maquina.txt /home/tux/info_system/rede

### Script
````
#!/bin/sh

echo "Digite os numeros 10,100,50,25,1,2 e ctrl+D"
pwd
mkdir /mack
cd /mack
cd
mkdir /trabalho
cd /mack
mkdir /textos
cat > numeros.txt
cat > numeros.txt > numeros1.txt > numeros2.txt
cp /mack/*.txt /trabalho
ls -al
chmod 751 numeros.txt
chmod 644 numeros.txt
cd
mkdir /trabalho_feito
cp /mack/* /trabalho_feito
cd /mack
rm *.txt
cd /trabalho_feito
mv numeros.txt sequencia.txt
ls /bin
ls /bin > listabin.txt
mv /trabalho_feito /lab_unip_01

exit
````
