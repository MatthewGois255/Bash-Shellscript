O objetivo desse código é automatizar o processo de adicionar, comitar e dar push em arquivos no git de uma repositótio romoto do Github

#! /bin/bash
echo "file you want to add:"
read file
git add $file
echo "type in your message before commiting:"
read message
git commit -m "$message"
git push origin main

obs: o algoritmo funcionou, mas não testei adicionar mais de um arquivo no primeiro prompt e a mensagem do commit que eu dei era de apenas quatro letras
