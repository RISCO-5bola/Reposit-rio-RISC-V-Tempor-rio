# Memória de Dados

Na memória de dados, são adicionadas as condições iniciais do programa que foi simulado no processador. A definição desse programa está presente na página inicial do repositório e na pasta da Memória de Instruções.7

## Resursos para leitura e escrita na memória
Os sinais mem_read e mem_write habilitam a leitura de uma posição "endereco" (output "read_data") ou a escrita de uma "write_data" na posição endereço, respectivamente.
A leitura é assíncrona (sem depender da borda de subida do clock) e a escrita é síncrona (ocorre na borda de subida do clock).

## Utilização da memória
Abaixo estão as posições da memória 32x32 que foram usadas, assim como as suas especificações.
A senha é gerada por um gerador de números aleatórios e as outras são específicadas manualmente, representando um input do usuário.
A Memória de Dados também serve de output, já que o resultado (1 se o jogador adivinhou a senha e 0 caso contrário) será gravado na posição especificada).

<p align="center">
  <img src="datamem.png" width="100%" height="180%"\>
</p>
