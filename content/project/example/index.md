---
slides: example
url_pdf: ""
summary: Fabricio Murai, Bruno Demattos Nogueira, Francisco Galuppo Azevedo
authors: []
url_video: ""
date: 2016-04-27T00:00:00Z
categories: []
external_link: http://test.com
url_slides: ""
title: Randomized Experiments in Social Networks
tags:
  - network A/B testing
  - social networks
  - network bucket testing
links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/fabriciomurai
image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart
  preview_only: true
  filename: net-ab-testing.png
url_code: ""
---

Testes A/B são experimentos randomizados que permitem comparar duas variantes de um tratamento. Esta técnica é muito utilizada por empresas que oferecem serviços na Web para avaliar o impacto de novas funcionalidades no comportamento de seus usuários, pois não requer feedback explícito dos usuários e é capaz de quantificar a significância estatística dos efeitos observados. Durante o período de um experimento, cada usuário é redirecionado aleatoriamente para a versão atual do site ou para a versão modificada. Os estimadores para o efeito médio de tratamento são baseados na Stable Unit Treatment Value Assumption, que diz que o comportamento de um indivíduo condicionado ao seu tratamento não é afetado pelo tratamento dado aos outros. Esta suposição é violada em redes sociais devido às interações entre os usuários. Por isso,  modelos que visam caracterizar a interferência de um usuário nos outros vêm sendo propostos, assim como técnicas de amostragem que objetivam minimizar conexões entre usuários em tratamentos diferentes. No entanto, as técnicas existentes para a testes A/B em redes ainda são muito incipientes e não há consenso sobre qual modelo de interferência deve ser aplicado a um conjunto de dados. O objetivo deste projeto é desenvolver um arcabouço para testes A/B em redes robusto a vários modelos de interferência, capaz de minimizar o erro de estimação ocasionados pelas diferenças entre o modelo de interferência assumido e a realidade, dotado de grande poder estatístico, equipado com garantias teóricas e escalável.
