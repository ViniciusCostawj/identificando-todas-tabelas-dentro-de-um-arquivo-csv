Script em Python que verifica e exibe todas as colunas existentes em um arquivo CSV, facilitando a inspeção de estrutura antes de análises ou comparações de dados.

🧾 README
🧩 Verificador de Colunas CSV
📄 Descrição

Este script em Python foi desenvolvido para identificar e exibir todas as colunas de um arquivo CSV, auxiliando na validação e compreensão da estrutura do arquivo antes de processamentos, filtros ou comparações de dados.

⚙️ Funcionalidades

Lê apenas o cabeçalho do arquivo (rápido e eficiente).

Remove espaços e aspas dos nomes das colunas.

Exibe as colunas formatadas de forma limpa no terminal.

Trata erros de arquivo inexistente ou leitura incorreta.

🚀 Como usar

Certifique-se de ter o Python 3 e o pandas instalados:

pip install pandas


Execute o script informando o nome do arquivo CSV:

python verificar_colunas.py nome_do_arquivo.csv


Exemplo de saída:

--- Colunas encontradas no arquivo: 'dados.csv' ---
['nuop', 'StatusCode', 'DataOperacao', 'ValorTransacao']
--------------------------------------------------

🧠 Tecnologias utilizadas

Python 3

pandas

🧑‍💻 Autor

Vinicius Costa de Paula
Estudante de Ciência da Computação e desenvolvedor com experiência em Python, análise de dados e automação de processos.
