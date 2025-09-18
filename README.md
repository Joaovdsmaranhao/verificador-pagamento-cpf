🔎 Verificador de Pagamento por CPF

Projeto que automatiza a consulta do status de pagamento de clientes a partir de uma planilha Excel, utilizando Python + Selenium.

Disponível em duas formas de execução:

✅ Executável (.exe).

💻 Código-fonte em Python.

⚠️ Aviso sobre os dados

Todos os dados presentes na planilha dados_clientes.xlsx são fictícios, utilizados apenas para fins de teste e demonstração.
Não há dados pessoais reais neste repositório.

📌 Funcionalidades

Lê informações (Nome, Valor, CPF, Vencimento) da planilha dados_clientes.xlsx.

Consulta automaticamente o status de pagamento de cada CPF no site público consultcpf-devaprender.netlify.app
.

Registra os resultados (status, método e data do pagamento) em uma nova planilha planilha fechamento.xlsx.

Separa clientes com pagamento pendente.

🚀 Tecnologias Utilizadas

Python 3.8+

Bibliotecas:

openpyxl → manipulação de planilhas Excel

selenium → automação do navegador Chrome

Empacotamento: PyInstaller (geração do .exe)

Ambiente de execução: Google Chrome + ChromeDriver (necessário apenas no modo código-fonte)

▶️ Como executar
🔹 Opção 1 — Usando o Executável

Baixe este repositório.

Entre na pasta dist/.

Execute app.exe.

Certifique-se de que a planilha dados_clientes.xlsx esteja na mesma pasta.

O programa irá gerar a planilha planilha fechamento.xlsx com os resultados.


🔹 Opção 2 — Rodando o Código-Fonte

Clone este repositório:

git clone https://github.com/Joaovdsmaranhao/verificador-pagamento-cpf

cd verificador-pagamento-cpf


Instale as dependências:

pip install -r requirements.txt


Execute o script:

python app.py

📂 Estrutura do Projeto
verificador-pagamento-cpf/

│── build

│   └── ...

│── dist/ 

│   └── app.exe ( Executavel)

│   └── planilha fechamento.xlsx 

│   └── dados_clientes.xlsx  
│── app.py                   
│── app.spec
│── README.md   
│── requirements.txt         
