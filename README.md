# Ipea

Olá, bem-vindo ao meu portfólio de **Visualização e Análise de Dados do Ipea**.

Neste repositório eu mostro, de forma técnica, como acessar arquivos, mapear, explorar e modelar dados, e te oriento a tomar decisões com base no que estou criando, com alta performance e desempenho, seja dentro do seu negócio ou em um estudo pessoal no campo da Estatística.

Os dados vêm do [Ipeadata](http://www.ipeadata.gov.br/) e são acessados direto pelo pacote [`ipeadatar`](https://github.com/gomesleduardo/ipeadatar), sem precisar baixar arquivos manualmente.

---

## Projetos

### 01. Aumento da Gasolina

Variação anual do preço médio da gasolina (R$/m³), com média simples, CAGR e acumulado desde o início do período.

![Aumento da Gasolina](Gasolina/gasolina_variacao.png)

- **Fonte:** ANP via Ipeadata (série `ANP_PRGASOL`)
- **Código:** [`Gasolina/gasolina.R`](Gasolina/gasolina.R)
- **Formato:** 1080 x 1440 px (3:4), pronto para Instagram

---

## Como executar

1. Instale o [R](https://cran.r-project.org/) e o [RStudio](https://posit.co/download/rstudio-desktop/).
2. Clone o repositório:
   ```bash
   git clone https://github.com/aldreiperalta/Ipea.git
   ```
3. Abra a pasta como projeto no RStudio (*File → New Project → Existing Directory*).
4. Instale os pacotes:
   ```r
   install.packages(c("ipeadatar", "dplyr", "lubridate", "ggplot2", "showtext", "tibble"))
   ```
5. Abra o script de um projeto e execute com **Ctrl + Shift + S**. A imagem é gerada na pasta do projeto.

---

## Tecnologias

![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![ggplot2](https://img.shields.io/badge/ggplot2-visualização-1f4e79?style=flat)
![Ipeadata](https://img.shields.io/badge/Ipeadata-fonte%20de%20dados-0C212C?style=flat)

---

## Autor

**Aldrei Peralta**, Estatístico e Engenheiro de Software, fundador da Campo Analítico.

[GitHub](https://github.com/aldreiperalta)
