![banner](https://github.com/user-attachments/assets/2fac8b7b-a1ae-49ed-a632-ae9963e05e66)

<p align="center"">Desenvolvimento dde um artigo cientifico</p>


## 📚 Sumário
- [Descrição Geral](#-analise-dos-fianaciamentos-externos-(COFIEX)-e-seus-Impactos-no-PIB-estadualBrasil (2010–2021))
- [Arquivos do Projeto](#-arquivos-do-projeto000)
- [Etapas do Projeto](#-etapas-do-projeto)
- [Principais Resultados](#-principais-resultados)
- [Gráficos](#-principais-gráficos)
- [Referências](#-referências)

## 
### 📊 Análise dos Financiamentos Externos (COFIEX) e seus Impactos no PIB Estadual — Brasil (2010–2021)                

repositório documenta um estudo completo sobre a relação entre Financiamentos Externos para Obras Públicas (COFIEX) e o crescimento do PIB estadual, com foco nos estados de São Paulo (SP) e Rio de Janeiro (RJ) entre 2010 e 2021.

O objetivo é identificar se os financiamentos internacionais influenciam o crescimento econômico e como eles são distribuídos entre regiões e setores.

##
### 📁 Arquivos do Projeto                                              

🧹 1. Investimento.ipynb

Notebook responsável pela limpeza inicial dos dados COFIEX, tratamento de inconsistências e preparação da base de financiamentos.
##

### 📈 2. PIB.ipynb

Notebook onde é realizada a integração entre a base de financiamentos e os dados do PIB estadual, além da criação da variável derivada "Valor Financiado Ajustado".
##
### 📊 3. PIB_corrigido.ipynb

Notebook final contendo:

impacto dos financiamentos,

Geração dos gráficos finais,

Testes das hipóteses (H1–H6),

Consolidação dos resultados para o artigo científico.
##
### 📄 4. IICongressoIP.docx

IICongressoIP


Arquivo do artigo científico pronto, contendo a discussão teórica e a análise final dos resultados.

**🧭 Etapas do Projeto**
**🔎 1. Preparação Inicial e Limpeza dos Dados**
**✔ O que foi feito**

Leitura e inspeção dos dados originais COFIEX.

Tratamento manual em Excel e correções via Python.

Remoção de registros incompletos ou inválidos.

Criação da base final de financiamentos.

### 📄 Arquivo utilizado

Investimento.ipynb
##

### 🟩 Resultado

Base limpa e padronizada, pronta para análise exploratória.

### 📈 2. Análise Exploratória, Cruzamento e Normalização
✔ Ações realizadas

Integração entre financiamentos COFIEX e PIB estadual.

Ajuste dos valores monetários pela inflação.

Conversão e padronização de datas.

Identificação de picos de investimento e distribuição entre setores.

Criação da variável:
Impacto do Financiamento (t) → PIB (t+1)

### 📄 Arquivo utilizado

PIB.ipynb
##

### 🟩 Resultados

<img width="509" height="218" alt="image" src="https://github.com/user-attachments/assets/25dbd191-b6f7-4427-9550-191e1352cdf9" />
<img width="521" height="284" alt="image" src="https://github.com/user-attachments/assets/5bd2697e-9cfe-47ed-8d4d-5616cddf1fc6" />


Entendimento das diferenças entre quantidade de projetos e volume investido.

Identificação de desequilíbrios regionais e concentração em grandes projetos.

##
### 📉 3. Modelagem, Avaliação de Hipóteses e Conclusão                                     

 **-Ações realizadas**

Avaliação das hipóteses H1–H6.

Correlação entre número de projetos, valor investido e PIB.

Análise dos efeitos setoriais (VAB).

Investigação da influência dos projetos outliers.

Conclusão sobre a fraca correlação agregada.

📄 Arquivo utilizado

PIB_corrigido.ipynb

IICongressoIP.docx (artigo final)
##
### 🟩 Principais conclusões

<img width="534" height="292" alt="image" src="https://github.com/user-attachments/assets/030343ad-a436-4bc8-9fea-3a6c4f1dacf4" />

A correlação entre financiamento externo e PIB é fraca nos dois estados.

O impacto é dominado por poucos projetos de grande porte, que distorcem a média.

A distribuição dos recursos não é proporcional ao tamanho econômico dos estados.

Há indícios de desigualdade regional e influência de fatores políticos.

Os setores mais beneficiados são os de infraestrutura e serviços, gerando efeito crowd-in localizado.
##
### 🎓 Base Científica

O projeto se apoia em autores como:

De Moraes et al. (2022)

Festa Júnior & Santos (2024)

Waldow & Conte Filho (2023)

Betarelli Jr. et al. (2020)

A análise final está detalhada no arquivo IICongressoIP.docx.
##

### 🚀 Como Utilizar o Repositório

Abra os notebooks na ordem:

Investimento.ipynb

PIB.ipynb

PIB_corrigido.ipynb

Execute célula por célula.



[Carta de Aceite.pdf](https://github.com/user-attachments/files/24043973/Carta.de.Aceite.pdf)

