# Inventory Management & Logistics Dashboard 

This repository presents a Business Intelligence solution designed for inventory monitoring, international in-transit shipment tracking, and asset auditing of high-performance fitness equipment. The project integrates multiple operational and logistics data sources to provide greater visibility into inventory availability, import pipelines, and product technical specifications.

Its primary objective is to support strategic decision-making related to replenishment planning, procurement activities, product distribution, and efficient management of both available and incoming assets.

## Business Context

Managing inventory for large-scale equipment involves significant challenges due to extended replenishment lead times, complex international logistics operations, and the need for detailed asset control.

To ensure operational predictability, organizations must simultaneously monitor physical inventory levels and products already purchased but still moving through the supply chain.

This project was developed to address these challenges by consolidating inventory, import, and technical asset information into a single analytical platform.

## Dashboard Structure & Analytical Views

### 1. Inventory & Pipeline Overview

A strategic view designed to monitor inventory levels, logistics movements, and replenishment planning activities.

#### Key Metrics

* Physical inventory available in warehouses.
* Quantity of products in domestic and international transit.
* Projected inventory balance considering future arrivals.
* Number of monitored active SKUs.
* Inventory distribution by product category.

#### Features

* Consolidated monitoring of the logistics pipeline.
* Detailed SKU-level visibility.
* Segmentation by product lines:

  * Bikes;
  * Ellipticals;
  * Treadmills;
  * Strength Equipment.
* Dynamic filters by commercial relevance and strategic categories.

#### Available Analyses

* Comparison between available inventory and in-transit quantities.
* Identification of stockout risks and excess inventory scenarios.
* Support for receiving schedules and distribution planning.

---

### 2. Asset Specification & Hardware Tracking

An analytical view focused on the detailed control of technical specifications associated with the equipment portfolio.

#### Key Metrics

* Quantity of assets by technical configuration.
* Individual asset control through serial number tracking.
* Distribution of equipment by hardware specifications.
* Availability of premium-feature products.

#### Features

* Monitoring of technical attributes relevant to corporate customers.
* Identification of equipment with advanced capabilities.
* Segmentation based on specific product characteristics.

#### Technical Mapping

* Console size:

  * Small;
  * Medium;
  * Large.

* Connectivity features:

  * Streaming-enabled equipment;
  * Equipment without integrated connectivity.

* Tracking of operational attributes and technical observations.

## Technologies & Tools

* **Power BI:** Development of dashboards and interactive visualizations.
* **DAX:** Creation of logistics KPIs, inventory metrics, and automated inventory projection calculations.
* **Power Query (M Language):** ETL processes for data extraction, cleansing, transformation, and consolidation.
* **Data Modeling:** Design of optimized analytical models supporting fast filtering by SKU, category, and product line.
* **File Integration:** Automated consolidation of multiple operational spreadsheets into a unified dataset.

## Technical Challenges Overcome

* **Decentralized Data Integration:**

  * Automated consolidation of independent operational files into a single analytical model while preserving SKU integrity and consistency.

* **Logistics Data Cleansing:**

  * Standardization and correction of records containing structural inconsistencies that impacted calculations related to weight, volume, and inventory quantities.

* **Missing Data Management:**

  * Implementation of rules to handle incomplete technical attributes without compromising inventory reporting accuracy.

* **Scalable Analytical Modeling:**

  * Development of a robust structure capable of supporting multiple equipment categories while maintaining high query performance.

## Key Insights

* **Supply Bottleneck Identification:**

  * Clear visibility into the imbalance between available warehouse inventory and significant in-transit volumes, highlighting the importance of prioritizing receiving operations and inventory planning.

* **Enhanced Supply Chain Visibility:**

  * Continuous monitoring of the logistics pipeline, reducing uncertainty regarding future product availability.

* **Smart Portfolio Auditing:**

  * Accurate identification of equipment featuring premium capabilities, such as larger displays and streaming support, enabling more targeted commercial strategies.

* **Improved Decision-Making:**

  * Delivery of reliable information to procurement, logistics, and sales teams, contributing to more efficient asset management practices.

---

*This project is part of my professional portfolio in Business Intelligence, Analytics, and Data Engineering applied to Inventory Management, Supply Chain Operations, and Import Logistics, demonstrating my ability to transform complex operational data into actionable business insights.*

_________________________________________________________________________

# Inventory Management & Logistics Dashboard 

Este repositório apresenta uma solução de Business Intelligence desenvolvida para o monitoramento de inventário, rastreamento de mercadorias em trânsito internacional e auditoria de ativos de equipamentos de alta performance do segmento fitness. O projeto integra diferentes fontes de dados operacionais e logísticos para proporcionar maior visibilidade sobre a disponibilidade de estoque, o pipeline de importação e as especificações técnicas dos equipamentos.

O objetivo é apoiar decisões estratégicas relacionadas ao abastecimento, planejamento de compras, distribuição de produtos e gestão eficiente dos ativos disponíveis e futuros.

## Contexto do Negócio

A gestão de estoque de equipamentos de grande porte apresenta desafios significativos devido aos elevados tempos de reposição, complexidade logística internacional e necessidade de controle detalhado dos ativos comercializados.

Para garantir maior previsibilidade operacional, torna-se essencial acompanhar simultaneamente o estoque físico disponível e os volumes já adquiridos que ainda se encontram em trânsito ao longo da cadeia de suprimentos.

Este projeto foi desenvolvido para atender a essa necessidade, consolidando informações de inventário, importação e características técnicas dos equipamentos em uma única plataforma analítica.

## Estrutura dos Dashboards & Visões Analíticas

### 1. Visão Geral de Estoque e Pipeline Logístico (Inventory & Pipeline Overview)

Visão estratégica voltada ao acompanhamento dos níveis de estoque, movimentação logística e planejamento de abastecimento.

#### Principais Métricas

* Estoque físico disponível em armazém.
* Quantidade de mercadorias em trânsito internacional e nacional.
* Saldo total projetado considerando recebimentos futuros.
* Quantidade de SKUs ativos monitorados.
* Distribuição do estoque por categoria de produto.

#### Funcionalidades

* Monitoramento consolidado do pipeline logístico.
* Visualização detalhada por SKU.
* Segmentação por linhas de produtos:

  * Bikes;
  * Elípticos;
  * Esteiras;
  * Equipamentos de Força.
* Filtros dinâmicos por relevância comercial e categorias estratégicas.

#### Análises Disponíveis

* Comparação entre estoque disponível e volumes em trânsito.
* Identificação de riscos de ruptura ou excesso de estoque.
* Apoio ao planejamento de recebimentos e distribuição.

---

### 2. Auditoria Técnica de Ativos (Asset Specification & Hardware Tracking)

Visão analítica dedicada ao controle detalhado das características técnicas dos equipamentos presentes no inventário.

#### Principais Métricas

* Quantidade de equipamentos por configuração técnica.
* Controle individualizado por número de série.
* Distribuição dos ativos por especificações de hardware.
* Disponibilidade de equipamentos com recursos premium.

#### Funcionalidades

* Rastreamento de atributos técnicos relevantes para o mercado corporativo.
* Identificação de equipamentos com recursos avançados.
* Segmentação por características específicas de produto.

#### Mapeamento Técnico

* Tamanho do console:

  * Pequeno;
  * Médio;
  * Grande.

* Recursos de conectividade:

  * Compatibilidade com Streaming;
  * Equipamentos sem conectividade integrada.

* Controle de atributos operacionais e observações técnicas.

## Tecnologias e Ferramentas

* **Power BI:** Desenvolvimento dos dashboards e criação das visualizações interativas.
* **DAX:** Construção de indicadores logísticos, métricas de inventário e projeções automatizadas de saldo.
* **Power Query (M Language):** Processos de ETL para consolidação, limpeza e transformação dos dados.
* **Modelagem de Dados:** Estruturação de modelos otimizados para análises rápidas por SKU, categoria e linha de produto.
* **Integração de Arquivos:** Consolidação automatizada de múltiplas planilhas operacionais provenientes de diferentes áreas do negócio.

## Desafios Técnicos Superados

* **Unificação de Fontes Descentralizadas:**

  * Consolidação automatizada de arquivos independentes em um único modelo analítico, garantindo integridade e padronização dos SKUs.

* **Tratamento de Dados Logísticos:**

  * Limpeza e padronização de registros contendo inconsistências estruturais que comprometiam cálculos relacionados a peso, cubagem e volumes.

* **Tratamento de Dados Ausentes:**

  * Desenvolvimento de regras para lidar com atributos técnicos incompletos sem comprometer os indicadores de inventário.

* **Escalabilidade do Modelo Analítico:**

  * Construção de uma estrutura capaz de suportar múltiplas categorias de equipamentos mantendo alta performance nas consultas.

## Principais Insights Obtidos

* **Identificação de Gargalos de Abastecimento:**

  * Evidência clara do desbalanceamento entre estoque físico disponível e elevado volume de produtos em trânsito, reforçando a importância do planejamento de recebimento e priorização operacional.

* **Maior Visibilidade da Cadeia de Suprimentos:**

  * Monitoramento contínuo do pipeline logístico, reduzindo incertezas relacionadas à disponibilidade futura dos produtos.

* **Auditoria Inteligente do Portfólio:**

  * Identificação precisa dos equipamentos com características premium, como telas maiores e recursos de streaming, apoiando estratégias comerciais direcionadas.

* **Suporte à Tomada de Decisão:**

  * Disponibilização de informações confiáveis para áreas de compras, logística e vendas, contribuindo para uma gestão mais eficiente dos ativos.

---

*Este projeto integra meu portfólio profissional em Business Intelligence, Analytics e Engenharia de Dados aplicados à Gestão de Inventário, Supply Chain e Logística de Importação, demonstrando minha capacidade de transformar dados operacionais complexos em insights estratégicos para o negócio.*

