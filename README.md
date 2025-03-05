# Sistema Bancário Simples em Python

Este é um sistema bancário simples em Python que permite realizar depósitos, saques e visualizar o extrato da conta.

## Funcionalidades

* **Depósito:** Permite depositar valores positivos na conta.
* **Saque:** Permite sacar valores da conta, respeitando o saldo, limite de saque e limite de saques diários.
* **Extrato:** Exibe o histórico de transações (depósitos e saques) e o saldo atual da conta.

## Como Executar

1.  Certifique-se de ter o Python instalado em seu sistema.
2.  Salve o código em um arquivo com a extensão `.py` (por exemplo, `banco.py`).
3.  Abra um terminal ou prompt de comando.
4.  Navegue até o diretório onde você salvou o arquivo.
5.  Execute o script com o comando `python banco.py`.
6.  Siga as instruções do menu para realizar as operações desejadas.

## Requisitos

* Python 3.x

## Limitações

* O sistema não possui persistência de dados. Ao fechar o programa, todas as informações são perdidas.
* O sistema assume que há apenas um usuário.
* O extrato é armazenado como uma string única, o que pode não ser eficiente para grandes volumes de transações.
* Não há tratamento de erros para entradas inválidas (por exemplo, digitar letras em vez de números).

## Melhorias Futuras

* Implementar persistência de dados (por exemplo, usando arquivos ou bancos de dados).
* Adicionar suporte para múltiplos usuários.
* Melhorar a estrutura do extrato (por exemplo, usando uma lista de dicionários).
* Adicionar tratamento de erros robusto.
* Implementar outras funcionalidades bancárias (por exemplo, transferências, pagamentos, etc.).

## Observações

Este é um projeto simples para fins de aprendizado. Sinta-se à vontade para modificá-lo e melhorá-lo de acordo com suas necessidades.
