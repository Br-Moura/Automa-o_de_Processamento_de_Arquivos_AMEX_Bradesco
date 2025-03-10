# Automação de Processamento de Arquivos AMEX - Bradesco

## Descrição

Este script automatiza o processamento de arquivos do Banco Bradesco AMEX, facilitando a leitura, comparação e inserção de dados no software **Maticard Pro**.

## Funcionalidades

- **Seleção de Arquivo**: Permite escolher um arquivo `.txt` contendo registros.
- **Localização do PRD**: Encontra automaticamente o arquivo `.PRD.ENC` correspondente.
- **Descriptografia**: Usa o software `AutoDec` para descriptografar o PRD.
- **Comparação de Dados**: Verifica se os registros do arquivo Matica estão presentes no PRD.
- **Automação no Maticard Pro**: Insere os dados automaticamente no software Maticard Pro.
- **Gerenciamento de Arquivos**: Remove arquivos temporários ao final do processo.

## Pré-requisitos

- Python 3.x
- Bibliotecas necessárias (instale com `pip install -r requirements.txt`):
  - `pyautogui`
  - `tkinter`
  - `shutil`
  - `subprocess`
  - `re`
  - `time`
  - `os`
  - `sys`

## Como Usar

1. Execute o script:
   ```sh
   python AMEX.py
