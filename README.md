# redutor-engrenagens-industrial
# Projeto e Dimensionamento de Redutor de Engrenagens Industrial

Projeto de engenharia mecânica focado no dimensionamento analítico, seleção de componentes normatizados e modelagem 3D de um redutor de velocidade de 3 estágios para acionamento de um misturador industrial (*Ribbon Blender*). Desenvolvido no âmbito da disciplina **SEM 0327 - Elementos de Máquinas III (EESC-USP)**.

---

## 📌 Visão Geral do Sistema
O sistema foi projetado para adaptar a alta rotação e baixo torque de um motor elétrico às exigências operacionais do misturador, garantindo segurança contra fadiga e vida útil prolongada.

* **Relação de Transmissão Total:** ~35:1 (distribuída em 3 estágios para evitar sobrecarga)
* **1º Estágio:** Par cônico de dentes retos a 90° (Aço SAE 8620 cementado / SAE 4320)
* **2º e 3º Estágios:** Pares cilíndricos de dentes helicoidais (Aço SAE 4340 e SAE 1045)
* **Potência de Entrada:** 60 HP (1150 RPM)

---

## 🛠️ Metodologias e Destaques Técnicos

* **Cálculo de Engrenagens:** Dimensionamento via metodologia de Niemann e Dudley-Lewis, com verificações à flexão na raiz do dente, fadiga de contato (*pitting*) e engripamento (*scoring*).
* **Análise Estrutural de Eixos:** Elaboração de Diagramas de Corpo Livre (DCL), esforço cortante, momento fletor/torsor e aplicação de coeficientes de concentração de tensões ($\beta_{kf}$) e fadiga alternada.
* **Mancais de Rolamento:** Seleção rigorosa de rolamentos de rolos cilíndricos via catálogo **SKF**, garantindo vida útil operacional superior a $20.000$ horas ($L_{10h}$).
* **Uniões Eixo-Cubo:** Dimensionamento de chavetas puras (norma DIN 6885) com verificação de pressões de esmagamento no cubo/eixo e tensões de cisalhamento.
* **Documentação CAD / Detalhamento:** Modelagem 3D no Solid Edge e elaboração de desenhos técnicos de fabricação com tolerâncias dimensionais, rugosidades (N6/N7) e indicação de acabamentos.

---

## 🖼️ Galeria do Projeto

*(Nota: Se carregou as imagens com outros nomes, lembre-se de ajustar os nomes dos ficheiros nos links abaixo se necessário)*

| Montagem do Conjunto 3D | Eixo Intermediário com Chavetas |
| :---: | :---: |
| ![Montagem](nome_da_imagem_montagem.png) | ![Eixo](nome_da_imagem_eixo.png) |

---

## 📄 Documentação Completa
O relatório técnico final com todo o memorial de cálculo, tabelas de verificação e desenhos cotados está disponível para consulta:
* 📥 [Baixar Relatório Técnico Completo (PDF)](./nome_do_seu_relatorio.pdf)

---
*Desenvolvido por Gianluca Gomes Souza e Matheus Nunes Rurali — Engenharia Mecânica (EESC-USP).*
