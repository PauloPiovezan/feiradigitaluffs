# 🛒 Feira Digital

> Plataforma unificada de comércio eletrônico voltada ao fortalecimento e à inclusão digital de micro e pequenos empreendedores locais.

---

##  Dados do Projeto

* **Instituição:** Universidade Federal da Fronteira Sul (UFFS) — Ciência da Computação
* **Título do Projeto:** Feira Digital
* **Estudantes:** Paulo Renato Piovezan Filho e Manoel Alves Cardoso
* **ODS Escolhido:** ODS 8 – Trabalho Decente e Crescimento Econômico (ONU)

---

##  Introdução e Contextualização

No Brasil, os pequenos negócios representam **26,5% do PIB** e foram responsáveis por cerca de **sete em cada dez empregos formais** gerados em 2024 (SEBRAE, 2025a, 2025b). No entanto, a taxa de mortalidade supera **20% nas microempresas** e **30% nos MEIs** (SEBRAE/MG, 2025), evidenciando barreiras à sustentabilidade no mercado.

---

##  Justificativa com Base em Evidências

O e-commerce brasileiro movimentou aproximadamente **R$ 235,5 bilhões em 2025**, com alta de **15,3%** e cerca de **94,2 milhões de consumidores** (ABComm, 2025). O **Feira Digital** conecta esses dados ao oferecer uma vitrine unificada e acessível, superando as restrições orçamentárias e técnicas dos pequenos empreendedores locais.

---

##  Objetivos

### Objetivo Geral
Impulsionar o crescimento e a sustentabilidade de micro e pequenas empresas por meio do aproveitamento do mercado de e-commerce local.

### Objetivos Específicos
* Disponibilizar uma plataforma unificada de comércio digital direcionada a micro e pequenos empreendedores da cidade e região do usuário.
* Facilitar o processo de divulgação e publicidade de pequenos empreendedores, ampliando sua visibilidade no mercado local.
* Permitir o gerenciamento simplificado e ágil de estoque e pedidos pelos próprios vendedores.

---

##  Alinhamento com a ODS (Agenda 2030)

* **ODS:** Objetivo de Desenvolvimento Sustentável 8 – Trabalho Decente e Crescimento Econômico (ONU).
* **Meta Específica:** **Meta 8.3** — Apoio às atividades produtivas, empreendedorismo e formalização de micro, pequenas e médias empresas (ONU).

### Como o projeto contribui
O **Feira Digital** elimina barreiras tecnológicas para pequenos comerciantes, viabilizando o crescimento e a formalização dos negócios regionais em conformidade com a Meta 8.3 da ONU.

---

##  Público-Alvo

1. **Micro e Pequenos Empresários:** Empreendedores que buscam expandir presença de mercado e gerenciar produtos sem altos investimentos em TI.
2. **Consumidores Locais:** Clientes interessados em valorizar a economia regional e comprar diretamente de fornecedores locais.

---

##  Escopo e Funcionalidades

### Mapa do Site
* **Login (`login.html`):** Catálogo público com busca de produtos locais.
* **Vitrine (`vitrine.html`):** Catálogo público com busca de produtos locais.
* **Cliente (`cliente.html`):** Acompanhamento de pedidos.
* **Vendedor(`vendedor.html`):** Painel administrativo de gestão.

### Funcionalidades (MVP)
* **Área do Vendedor:** painel de pedidos.
* **Área do Cliente:** status de pedidos.

### Funcionalidades Desejáveis
* Chat direto entre clientes e vendedores.
* Sistema de avaliações de produtos e comerciantes.

---

##  Paleta de Cores e Acessibilidade

| Variável CSS | Função na Interface | Código Hex | Justificativa |
| :--- | :--- | :---: | :--- |
| `--color-brand-blue` | **Cor Primária** (Cabeçalho/Rodapé) | `#5fa8d3` | Azul acolhedor que transmite confiança e destaque visual. |
| `--color-brand-bg` | **Fundo Principal** | `#ebebeb` | Cinza neutro que reduz o brilho e garante contraste com textos escuros. |
| `--color-brand-surface` | **Superfície e Contornos** | `#c0c0c0` | Cinza médio para delimitação de cartões de produtos. |

---

## Tecnologias Utilizadas

* **HTML5:** Semântica estrutural.
* **Tailwind CSS:** Estilização responsiva *mobile-first*.
* **Google Material Icons:** Iconografia de interface.
* **JavaScript:** Interatividade no navegador.

---

## Como Executar o Projeto

1. **Clone este repositório:**
   ```bash
   git clone https://github.com/PauloPiovezan/feiradigitaluffs.git
   cd feira-digital
   ```
2. **Compile o Tailwind CSS:**
   ```bash
   npx tailwindcss -i ./src/input.css -o ./css/output.css --watch
   ```
3. **Visualize no navegador:**
   Abra `login.html` diretamente ou use o Live Server no VS Code.

---

## Referências

* **ABCOMM.** *Crescimento do e-commerce brasileiro.* 2025. Disponível em: https://abcomm.org.
* **ONU.** *ODS 8: trabalho decente e crescimento econômico.* Disponível em: https://un.org.
* **SEBRAE.** *Grandes números dos pequenos negócios no Brasil.* 2025a. Disponível em: https://agenciasebrae.com.br.
* **SEBRAE.** *Pequenos negócios dominaram criação de empregos em 2024.* 2025b. Disponível em: https://agenciasebrae.com.br.
* **SEBRAE/MG.** *Sobrevivência das empresas no Brasil.* 2025. Disponível em: https://sebraemg.com.br.