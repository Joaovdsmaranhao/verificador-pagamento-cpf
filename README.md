# VERIFICADOR DE PAGEMENTO POR CPF

Este projeto automatiza a consulta do status de pagamento de clientes a partir de uma planilha Excel, usando Selenium para acessar um site de consulta pública.

---

# Aviso sobre os dados
Atenção:
Todos os dados presentes na planilha dados_clientes.xlsx são fictícios e utilizados apenas para fins de teste e demonstração.
Não há dados pessoais reais neste repositório.


## Funcionalidades

- Lê dados (Nome, Valor, CPF, Vencimento) da planilha `dados_clientes.xlsx`.
- Consulta o status de pagamento de cada CPF no site [consultcpf-devaprender.netlify.app](https://consultcpf-devaprender.netlify.app/).
- Registra os resultados (status, método e data do pagamento) em uma planilha `planilha fechamento.xlsx`.
- Marca clientes com pagamento pendente separadamente.

---

## Tecnologias Utilizadas

- Python 3.8+
- Bibliotecas:
  - `openpyxl` para manipulação de planilhas Excel.
  - `selenium` para automação do navegador Chrome.
- Google Chrome + ChromeDriver compatível instalado.

---

## Como executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/Joaovdsmaranhao/verificador-pagamento-cpf.git
   cd verificador-pagamento-cpf
