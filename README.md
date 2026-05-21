# Bible Data Pipeline (ETL & BI)

Este é um projeto de Engenharia e Análise de Dados que realiza o processo de ETL (Extração, Transformação e Carga) dos textos estruturados da Bíblia Sagrada, enriquecendo os dados com métricas matemáticas e estatísticas textuais para visualização em um dashboard de Business Intelligence (BI).

## 🛠️ Tecnologias Utilizadas
* **Sistema Operacional:** Linux
* **Linguagem:** Python 3
* **Transformação & Estatística:** Pandas e NumPy
* **Banco de Dados:** MariaDB
* **Ferramenta de BI:** Metabase (Open Source Edition)

## 📁 Estrutura do Projeto
* `data/`: Diretório local contendo os dados (ignorado no Git).
* `src/extract.py`: Módulo responsável pela leitura do arquivo bruto.
* `src/transform.py`: Módulo de engenharia de recursos e cálculos matemáticos.
* `src/load.py`: Ingestão dos dados tratados no banco relacional.

## ⚖️ Licença e Origem dos Dados
A base de dados textual utilizada neste projeto (Tradução João Ferreira de Almeida Atualizada) foi obtida a partir do projeto open-source [scrollmapper/bible_databases](https://github.com/scrollmapper/bible_databases). 

O dataset original é distribuído sob a **Licença MIT**, o que garante que este projeto é de uso livre, gratuito e em total conformidade com os direitos autorais e de domínio público para fins acadêmicos, de portfólio ou comerciais.