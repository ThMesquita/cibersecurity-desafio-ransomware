# Desafio DIO: Criando um Ransomware para Criptografar Arquivos

Este projeto foi desenvolvido como parte do desafio proposto pela DIO (Digital Innovation One) para aprender sobre segurança cibernética, criptografia e como funcionam as ameaças de ransomware. O objetivo do desafio foi criar um script de **ransomware** que criptografa arquivos em um diretório e exige uma chave para descriptografá-los.

## Objetivo do Desafio

O objetivo deste desafio foi ensinar como funciona a criptografia de arquivos e como malwares, como ransomware, são capazes de criptografar e bloquear o acesso a arquivos, geralmente com a exigência de pagamento de um resgate. Durante o desafio, a criptografia foi feita de maneira controlada e em um ambiente seguro, com o intuito de aprender sobre as técnicas utilizadas por cibercriminosos.

## Funcionalidade do Ransomware

Este script realiza as seguintes ações:

1. **Criptografia de Arquivos**:
   - O ransomware criptografa o arquivo encontrado em um diretório especificado.

2. **Renomeação de Arquivos**:
   - Após a criptografia, o ransomware renomeia os arquivos para adicionar uma extensão que os identifique como criptografados.


### Requisitos:
- Python 3.x
- Biblioteca `pyaes` (para criptografia)
