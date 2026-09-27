# 📊 Análise da Folha de Pagamento com Power BI

Projeto de Business Intelligence desenvolvido utilizando Microsoft Power BI
para análise e visualização de dados públicos relacionados à folha de
pagamento.

O projeto foi desenvolvido como parte do meu processo de aprendizado e
aperfeiçoamento em análise de dados, Business Intelligence, modelagem de
dados, Power Query e DAX.

---

## 🎯 Objetivo

Transformar uma grande base de dados públicos de folha de pagamento em um
relatório interativo que permita explorar informações relacionadas a:

- quantidade de servidores;
- órgãos;
- cargos;
- tipos de vínculo;
- valores brutos da folha;
- valores líquidos pagos;
- férias;
- décimo terceiro;
- evolução dos valores ao longo do tempo.

O projeto também busca demonstrar a aplicação prática de conceitos de
Business Intelligence na transformação de dados brutos em informações
visuais para análise.

---

## 🛠️ Tecnologias e recursos utilizados

- Microsoft Power BI
- Power Query
- DAX
- Modelagem de dados
- Dashboards interativos
- Visualização de dados
- Filtros e segmentações
- Medidas
- Análise temporal

---

## 🗂️ Estrutura do modelo

O modelo do relatório é composto principalmente por:

### `folha de pagamento`

<img width="1324" height="585" alt="image" src="https://github.com/user-attachments/assets/0ee06af4-d0f0-466b-9da5-98173c307e61" />

Tabela principal utilizada para as análises relacionadas aos dados da folha
de pagamento.

Entre os campos utilizados nos visuais estão:

- Data
- Cargo
- Tipo de Vínculo
- Órgão
- Unidade_Órgão
- Valor_Provento
- Valor_Liquido
- Valor_Provento
- Valor_Decimo_Terceiro
- Valor_Ferias_Mais_Um_Terco_Ferias

### `Métricas`

Tabela utilizada para organização das principais medidas do relatório.

Entre as medidas utilizadas estão:

- Total servidores
- qtd orgãos
- Total Bruto da Folha
- Total Líquido Pago
- Total Férias Pagas

---

# 📈 Páginas do relatório

## 1. Visão Geral

<img width="2420" height="1325" alt="pcmbi-visao-geral" src="https://github.com/user-attachments/assets/0c98bc0e-3040-4fe7-8024-3f69b988e662" />

A página de visão geral apresenta os principais indicadores do modelo e
permite uma análise inicial da composição da folha de pagamento.

### Principais indicadores

- Total de servidores
- Quantidade de órgãos
- Total bruto da folha
- Total líquido pago
- Total de férias pagas

### Análises disponíveis

- Servidores por tipo de vínculo
- Total bruto da folha por tipo de vínculo
- Média de proventos por tipo de vínculo
- Distribuição dos servidores por tipo de vínculo

### Filtros

O usuário pode utilizar filtros relacionados a:

- Ano
- Mês
- Órgão
- Unidade do órgão
- Cargo
- Tipo de vínculo

---

## 2. Órgãos e Cargos

<img width="2420" height="1325" alt="pcmbi-orgaos-e-cargos" src="https://github.com/user-attachments/assets/530b5f57-f001-4571-9ce9-eb6d7069df74" />

A página de órgãos e cargos permite aprofundar a análise da folha de
pagamento considerando a estrutura organizacional e os cargos.

### Análises

- Total bruto da folha por cargo
- Total de servidores por cargo
- Valor de proventos por órgão
- Quantidade de servidores por órgão
- Distribuição por tipo de vínculo

Também é apresentada uma tabela relacionando:

- Tipo de vínculo
- Total de servidores
- Total bruto da folha

---

## 3. Evolução Temporal

<img width="2420" height="1325" alt="pcmbi-evolucao-temporal" src="https://github.com/user-attachments/assets/e2d62214-bc3a-4bc0-9d27-8115d66ff7be" />

A página de evolução temporal permite analisar o comportamento dos
indicadores ao longo dos meses e anos disponíveis na base.

### Análises

- Evolução do valor líquido pago por mês
- Evolução do valor bruto da folha por mês
- Valores relacionados ao décimo terceiro
- Valores relacionados às férias e adicional de um terço
- Evolução do total bruto da folha
- Evolução da quantidade de servidores

Essa página permite explorar tendências e variações temporais presentes
na base de dados.

---

# 📊 Principais indicadores

O dashboard utiliza medidas para centralizar os principais indicadores
utilizados nas páginas do relatório.

| Indicador | Descrição |
|---|---|
| Total servidores | Quantidade total de servidores considerada pelo modelo |
| qtd orgãos | Quantidade de órgãos considerada na análise |
| Total Bruto da Folha | Valor total bruto utilizado nos indicadores |
| Total Líquido Pago | Valor líquido total considerado pelo modelo |
| Total Férias Pagas | Total relacionado aos valores de férias |

---

# 🔎 Interatividade

O relatório utiliza recursos de interatividade do Power BI, permitindo
que os filtros aplicados pelo usuário afetem os demais elementos do
relatório.

Entre os recursos utilizados estão:

- Segmentações de dados (slicers)
- Navegação entre páginas
- Interação entre visuais
- Gráficos comparativos
- Gráficos temporais
- Cards de indicadores
- Tabelas
- Visualizações de distribuição

---

# 📚 Aprendizados

Este projeto foi desenvolvido para colocar em prática conhecimentos
relacionados a:

- tratamento e preparação de dados;
- modelagem de dados;
- criação de medidas;
- utilização de DAX;
- criação de dashboards;
- construção de indicadores;
- análise temporal;
- utilização de filtros e segmentações;
- visualização de dados;
- organização de relatórios de Business Intelligence.

---

# 📁 Arquivo do Power BI

O arquivo `.pbix` possui aproximadamente 300 MB devido ao volume de dados
históricos utilizados no projeto.

A dimensão do arquivo está relacionada principalmente ao modelo de dados,
que contém uma base pública abrangendo diversos meses de informações.

Devido ao tamanho do arquivo, o `.pbix` completo pode ser disponibilizado
separadamente, enquanto este repositório concentra a documentação,
imagens e informações técnicas do projeto.

---

# 👨‍💻 Autor

**Marcos Wendel Luz Magalhães**

Estudante de Sistemas de Informação com foco em:

- Power BI
- Análise de Dados
- Business Intelligence
- Excel
- DAX
- Power Query

🔗 LinkedIn:
https://www.linkedin.com/in/marcos-wendel-luz-magalhães-846a542b8/

🔗 GitHub:
https://github.com/MarcosWendel18
