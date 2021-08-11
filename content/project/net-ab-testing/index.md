---
title: Randomized Experiments in Social Networks
summary: Novel algorithms and models for network A/B testing.
tags:
  - network A/B testing
  - online social networks
  - network bucket testing
  - linkedin
  - graphs
date: 2016-04-27T00:00:00Z

# Optional external URL for project (replaces project detail page).
external_link: ""

authors: [Fabricio Murai, Bruno Demattos Nogueira, Francisco Galuppo Azevedo]

image:
  caption: Parallel epsilon-net.
  focal_point: Smart
  filename: net-ab-testing.png
  preview_only: true


links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/fabriciomurai
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

---

Testes A/B são experimentos randomizados que permitem comparar duas variantes de um tratamento. Esta técnica é muito utilizada por empresas que oferecem serviços na Web para avaliar o impacto de novas funcionalidades no comportamento de seus usuários, pois não requer feedback explícito dos usuários e é capaz de quantificar a significância estatística dos efeitos observados. Durante o período de um experimento, cada usuário é redirecionado aleatoriamente para a versão atual do site ou para a versão modificada. Os estimadores para o efeito médio de tratamento são baseados na Stable Unit Treatment Value Assumption, que diz que o comportamento de um indivíduo condicionado ao seu tratamento não é afetado pelo tratamento dado aos outros. Esta suposição é violada em redes sociais devido às interações entre os usuários. Por isso,  modelos que visam caracterizar a interferência de um usuário nos outros vêm sendo propostos, assim como técnicas de amostragem que objetivam minimizar conexões entre usuários em tratamentos diferentes. No entanto, as técnicas existentes para a testes A/B em redes ainda são muito incipientes e não há consenso sobre qual modelo de interferência deve ser aplicado a um conjunto de dados. O objetivo deste projeto é desenvolver um arcabouço para testes A/B em redes robusto a vários modelos de interferência, capaz de minimizar o erro de estimação ocasionados pelas diferenças entre o modelo de interferência assumido e a realidade, dotado de grande poder estatístico, equipado com garantias teóricas e escalável.
