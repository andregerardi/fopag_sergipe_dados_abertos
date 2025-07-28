# Extração de Dados - Portal da Transparência de Sergipe

Este projeto realiza a raspagem automatizada dos dados de **folha de pagamento** disponíveis no [Portal da Transparência do Estado de Sergipe](https://www.transparencia.se.gov.br/Pessoal/PorOrgao.xhtml), consolidando as informações em um único arquivo CSV.

---

## 📌 Objetivo

Automatizar a coleta e organização dos dados salariais dos servidores públicos vinculados às instituições de saúde do estado de Sergipe, a partir de filtros por **órgão**, **mês** e **ano**.

---

## 🏛️ Instituições mapeadas

O script cobre as seguintes instituições, com códigos de identificação:

- `FES-27-EFETIVO`
- `FES-265-PSS`
- `FES-151-SAMU`
- `FHS-206-CLT-24910`
- `FHS-205-CLT-24900`
- `FHS-152-EFETIVO`
- `FHS-226-ESTAGIARIO`
- `FSPH-167-EFETIVO`
- `FUNESA-168`

---

## 🗓️ Período de coleta

Os dados são coletados para os anos de:

- **2021**
- **2025**

Cada mês de cada ano é percorrido individualmente por órgão.
Os dados por orgão estão na pasta dowloads.

---

## ⚙️ Tecnologias utilizadas

- `Python`
- `Selenium`
- `Pandas`
- `tqdm`
- Navegador: `Chrome` em modo headless

---

## 🧩 Estrutura do código

1. **Criação de diretórios** para armazenar os dados baixados.
2. **Automação com Selenium**: simula a navegação, aplica filtros e realiza os downloads.
3. **Monitoramento dos arquivos baixados**.
4. **Renomeia, processa e movimenta os arquivos** para as pastas corretas.
5. **Concatenação final** dos dados em um único CSV: `todos_os_dados_consolidados.csv`.

---

## 📄 Fonte de documentação

- Documentação do padrão Serigy: [TCE-SE - Recursos Humanos](https://serigy.tce.se.gov.br/comum/recursos-humanos.html#_6-1-folha-de-pagamento)

---
=======
# Extração de Dados - Portal da Transparência de Sergipe

Este projeto realiza a raspagem automatizada dos dados de **folha de pagamento** disponíveis no [Portal da Transparência do Estado de Sergipe](https://www.transparencia.se.gov.br/Pessoal/PorOrgao.xhtml) de 4 organizações estatais.

## 📌 Objetivo

Automatizar a coleta e organização dos dados salariais dos servidores públicos vinculados às instituições de saúde do estado de Sergipe, a partir de filtros por **órgão**, **mês** e **ano**.


## 🏛️ Instituições mapeadas
O mapeamento cobre as seguintes instituições com códigos de identificação:

- `FES-27-EFETIVO`
- `FES-265-PSS`
- `FES-151-SAMU`
- `FHS-206-CLT-24910`
- `FHS-205-CLT-24900`
- `FHS-152-EFETIVO`
- `FHS-226-ESTAGIARIO`
- `FSPH-167-EFETIVO`
- `FUNESA-168`


## 🗓️ Período de coleta

Os dados são coletados para os anos de:

- **2021**
- **2025**

Cada mês de cada ano é percorrido individualmente por órgão.
Os dados por orgão estão na pasta dowloads.


## ⚙️ Tecnologias utilizadas

- `Python`
- `Selenium`
- `Pandas`
- `tqdm`
- Navegador: `Chrome` em modo headless


## 🧩 Estrutura do código

1. **Criação de diretórios** para armazenar os dados baixados.
2. **Automação com Selenium**: simula a navegação, aplica filtros e realiza os downloads.
3. **Monitoramento dos arquivos baixados**.
4. **Renomeia, processa e movimenta os arquivos** para as pastas corretas.
5. **Concatenação final** dos dados em um único CSV: `todos_os_dados_consolidados.csv`.


## 📄 Fonte de documentação

- Documentação do padrão Serigy: [TCE-SE - Recursos Humanos](https://serigy.tce.se.gov.br/comum/recursos-humanos.html#_6-1-folha-de-pagamento)
