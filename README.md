<h1 align="center">Vitor de Toledo Magalhães</h1>
<h3 align="center">Desenvolvedor Python | Automação (RPA) | Engenharia de Dados Cloud (AWS)</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/magalhaes-vitor/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:vitor.de.toledo.magalhaes@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

---

### 🚀 Sobre mim

Atuo hoje como **Desenvolvedor RPA com foco em Engenharia de Dados na TOP MIND**, construindo automações e pipelines de dados escaláveis. Já passei pelo **BTG Pactual**, onde desenvolvi robôs de reconciliação bancária integrados à AWS para mais de 5.000 transações diárias, reduzindo o tempo de processamento em 70%.

Gosto de unir rigor analítico (tenho pesquisa acadêmica publicada em redes neurais) com entrega ágil: minha praia é pegar dados brutos e transformá-los em pipelines serverless, resilientes e baratos de operar.

- Trabalhando atualmente com automação RPA e engenharia de dados para a **TOP MIND**
- Aprofundando conhecimento em arquiteturas serverless e Data Contracts na AWS
---

### 🛠️ Stack & Ferramentas

**Cloud & Data Engineering**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white)
![Glue](https://img.shields.io/badge/AWS_Glue-527FFF?style=flat-square&logo=amazonaws&logoColor=white)
![S3](https://img.shields.io/badge/Amazon_S3-569A31?style=flat-square&logo=amazons3&logoColor=white)
![Athena](https://img.shields.io/badge/Amazon_Athena-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![ECS Fargate](https://img.shields.io/badge/ECS_Fargate-FF9900?style=flat-square&logo=amazonecs&logoColor=white)
![EventBridge](https://img.shields.io/badge/EventBridge-FF4F8B?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**RPA & Automação**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![UiPath](https://img.shields.io/badge/UiPath-FA4616?style=flat-square&logo=uipath&logoColor=white)
![Power Automate](https://img.shields.io/badge/Power_Automate-0066FF?style=flat-square&logo=powerautomate&logoColor=white)

**Dados, Análise & Visualização**

![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

---

### 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Magalhaes-vitor&show_icons=true&theme=default&hide_border=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Magalhaes-vitor&layout=compact&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Magalhaes-vitor&hide_border=true" />
</p>

---

### 📌 Projetos em destaque

#### 🌎 [Comex Data Product](https://github.com/Magalhaes-vitor/comex-data-product)
Pipeline serverless na AWS para automação e análise da balança comercial brasileira, reconciliando o volume físico movimentado no Porto de Santos (APS) com o valor declarado à alfândega (MDIC), contextualizado por câmbio (Bacen) e sazonalidade agrícola (CONAB).

- Orquestração via **EventBridge** disparando **AWS Lambda** (container image), com data lake em camadas **Medallion (Bronze/Silver/Gold)** no S3 e infraestrutura como código via **AWS SAM**
- **Data Contracts com Pydantic** e circuit breakers de qualidade, com alertas em tempo real via **Slack**
- Modelo dimensional consultável via **Athena SQL** e dashboards em **Power BI**
- Em produção: pipeline completo roda em ~69s e já processou **8,86 milhões de registros** em uma reconstrução histórica de 2019–2026

`Python` `AWS Lambda` `AWS Glue` `Athena` `Pydantic` `Docker` `AWS SAM`

#### 💲 [Inteligência Competitiva e Precificação](https://github.com/Magalhaes-vitor/projeto-precificacao-inteligente)
Pipeline end-to-end de coleta e análise de preços em múltiplos marketplaces (e-commerce e varejo), gerando inteligência competitiva para tomada de decisão em precificação.

- **Scrapers em Python/Selenium** para captura automatizada de preços
- Ingestão em **S3 (camada Bronze)**, transformação com **AWS Glue** e consulta via **Athena**
- Orquestração com **EventBridge** e execução em **ECS Fargate (Docker)**
- Dashboard de monitoramento com atualização diária no **Power BI**, com custo operacional de menos de US$ 0,05/dia

`Python` `Selenium` `AWS Glue` `Athena` `EventBridge` `Power BI`

---

### 📫 Vamos conversar

<p align="center">
  <a href="https://www.linkedin.com/in/magalhaes-vitor/">Conecte-se comigo no LinkedIn</a>
</p>
