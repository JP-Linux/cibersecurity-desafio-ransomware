
# Projeto cibersecurity-desafio-ransomware

Este projeto contém um par de scripts simples para criptografia e descriptografia de arquivos usando o algoritmo de criptografia AES no modo CTR. Por favor, lembre-se de que este projeto é apenas para fins educacionais e não deve ser usado para atividades maliciosas.

## Conteúdo

- [Introdução](#introdução)
- [Arquivos](#arquivos)
- [Uso](#uso)
- [Aviso Legal](#aviso-legal)

## Introdução

O Projeto cibersecurity-desafio-ransomware demonstra como a criptografia AES no modo CTR pode ser usada para criptografar e descriptografar arquivos. O projeto inclui dois scripts: `encrypter.py` e `decrypter.py`.

## Arquivos

- `encrypter.py`: Este script recebe um arquivo de entrada (`teste.txt`) e o criptografa usando o algoritmo de criptografia AES no modo CTR. O arquivo criptografado é salvo com a extensão `.ransomwaretroll`.

- `decrypter.py`: Este script recebe um arquivo criptografado (com a extensão `.ransomwaretroll`), o descriptografa usando o algoritmo de criptografia AES no modo CTR e restaura o arquivo original.

## Uso

1. **Criptografia:**

   Execute o script `encrypter.py` para criptografar um arquivo:

   ```bash
   python encrypter.py
   ```

   O script irá ler o conteúdo de `teste.txt`, criptografá-lo usando AES-CTR e salvar os dados criptografados em um novo arquivo com a extensão `.ransomwaretroll`.

2. **Descriptografia:**

   Execute o script `decrypter.py` para descriptografar um arquivo previamente criptografado:

   ```bash
   python decrypter.py
   ```

   O script irá ler os dados criptografados do arquivo `.ransomwaretroll`, descriptografá-los usando AES-CTR e salvar os dados descriptografados de volta em `teste.txt`.

**Observação:** Este projeto destina-se apenas a fins educacionais. Não é adequado para uso real como ransomware ou para atividades maliciosas.

## Aviso Legal

Este projeto é criado apenas para fins educacionais e discussões éticas sobre criptografia, segurança e programação. Os autores e colaboradores deste projeto não endossam nem apoiam qualquer uso ilegal ou malicioso do código fornecido. O projeto é fornecido "como está", sem garantia de qualquer tipo. Use este código de forma responsável e respeite as leis e regulamentos de sua jurisdição.

---
**Aviso Legal**: Este projeto não incentiva nem endossa atividades ilegais ou antiéticas. Use este código de maneira responsável e apenas para fins educacionais.
