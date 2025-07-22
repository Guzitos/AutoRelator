# AutoRelator

**AutoRelator** é um script Python para geração automática de relatórios com base em registros de horas extras. Ele lê dados de um arquivo CSV, processa as informações e gera relatórios prontos para uso em análises, RH ou gestão de equipes.

## 🚀 Funcionalidades

- Leitura de arquivos `.csv` com dados de horas extras
- Processamento automático e sumarização por funcionário/data
- Geração de relatórios prontos
- (Opcional) Exportação para arquivos Excel, PDF ou envio por e-mail *(em desenvolvimento)*

## 📁 Estrutura do Projeto

RelatorioAutomaticos/

├── horas_extras.csv # Dados de entrada

├── main.py # Script principal

## ✅ Pré-requisitos

- Python 3.x
- pandas

Instale as dependências com:

```
pip install pandas
```

## ▶️ Como usar
Insira seus dados no arquivo horas_extras.csv

Execute o script:

```
python main.py
```

📌 Exemplo de CSV esperado
```
Nome,Data,Horas Extras
João,2025-07-20,2
Maria,2025-07-20,3.5
```

## 👨‍💻 Autor @Guzitos




