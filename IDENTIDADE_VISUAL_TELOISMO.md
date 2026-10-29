# ⚒️ MANUAL DE IDENTIDADE VISUAL — TELOÍSMO (v3.0 — RITO FIBONACCI)

> **Doutrina Filosófica:** Pragmatismo, Racionalidade Implacável, Superação Material e Domínio dos Instintos orientados ao *Telos*.  
> **Diretriz Estética:** Brutalismo Tático, Minimalismo Implícito, Precisão Metálica, Proporção Áurea ($\varphi = 1.618$). Sem misticismos, sem curvas orgânicas supérfluas, sem excessos.

---

## 1. Paleta de Cores Oficial (Design Tokens)

### A. Paleta Principal (Fundo Escuro — Padrão Oficial)
| Token | Nome | Hex | Papel Semântico e Aplicação |
| :--- | :--- | :---: | :--- |
| `--color-void` | **Preto Profundo (Void)** | `#09090B` | Fundo principal (o caos/niilismo abraçado) e cortes de espaço negativo (`21px`). |
| `--color-surface` | **Superfície Tática** | `#0E0E12` | Interior de painéis densos, cards de axiomas e tabelas. |
| `--color-steel-dark` | **Cinza-Chumbo** | `#27272A` | Circunferência externa cortada (segundo plano), sombras duras e divisórias. |
| `--color-steel-main` | **Aço Escovado** | `#52525B` | Corpo principal do Martelo Teloísta (coluna, cabo e cabeça cega) e bordas estruturais. |
| `--color-crimson` | **Vermelho Carmesim** | `#991B1B` | Ponta triangular afiada (Razão/Ação/Retaliação), linhas de corte e estados de hover. Uso cirúrgico e escasso. |
| `--color-text-primary` | **Branco Frio Tático** | `#F4F4F5` | Títulos e textos principais de máxima legibilidade. |
| `--color-text-secondary`| **Cinza Metálico** | `#A1A1AA` | Textos de apoio, subtítulos e telemetria secundária. |

### B. Paleta Monocromática (Preto & Branco) e Fundo Claro
| Variante | Arquivo | Fundo | Anel | Martelo (Corpo) | Ponta Direita | Cortes Negativos |
| :--- | :--- | :---: | :---: | :---: | :---: | :---: |
| **1. Oficial Cor (Escuro)** | `logo.svg` / `logo_teloista.svg` | `#09090B` | `#27272A` | `#52525B` | `#991B1B` | `#09090B` |
| **2. P&B (Fundo Escuro)** | `logo_pb_fundo_escuro.svg` | `#09090B` | `#52525B` | `#F4F4F5` | `#F4F4F5` | `#09090B` |
| **3. P&B (Fundo Claro)** | `logo_pb_fundo_claro.svg` | `#F4F4F5` | `#A1A1AA` | `#09090B` | `#09090B` | `#F4F4F5` |
| **4. Cor (Fundo Claro)** | `logo_cor_fundo_claro.svg` | `#F4F4F5` | `#A1A1AA` | `#27272A` | `#991B1B` | `#F4F4F5` |

---

## 2. O Rito Geométrico de Fibonacci ($\varphi = 1.6180339...$)

Toda a construção do **Martelo Teloísta** e do sistema de layout obedece estritamente à **Sequência de Fibonacci**:
$$5, \; 8, \; 13, \; 21, \; 34, \; 55, \; 89, \; 144, \; 233, \; 377, \; 610, \; 987$$

| Termo Fibonacci | Medida (`px`) | Aplicação Estrutural no Símbolo e Interface |
| :---: | :---: | :--- |
| **$F_5$** | `5px` | Espessura das barras verticais de corte carmesim na UI. |
| **$F_6$** | `8px` | Deslocamento das sombras sólidas brutalistas (`8px 8px 0px`). |
| **$F_7$** | `13px` | Corpo de texto técnico (`--text-xs`) e espaçamentos internos compactos. |
| **$F_8$** | `21px` | **Espessura dos Cortes de Espaço Negativo** no logo (`stroke-width="21"`), altura do pescoço do cabo (`21px`), base do olhal (`21px`) e abas da face flangiada (`21px`). |
| **$F_9$** | `34px` | Altura do topo do olhal (`34px`), colar do cabo (`34px`), largura do chanfro esquerdo (`34px`) e **projeção da ponta carmesim para fora do anel** (`34px`). |
| **$F_{10}$** | `55px` | **Espessura da Circunferência (`stroke-width="55"`)**, altura da base do pomo (`55px`), **respiro entre a face esquerda e o interior do anel** (`55px`) e tamanho do grid de fundo (`55×55px`). |
| **$F_{11}$** | `89px` | **Largura da Haste do Cabo** (`89px`, de `-44.5` a `+44.5`) e limite superior da cabeça (`y = -89`). |
| **$F_{12}$** | `144px` | **Largura e Altura do Núcleo Central da Cabeça (`144 × 144px`)** ($144 / 89 = 1.618$) e **projeção do cabo para fora da base do anel** (`144px`). |
| **$F_{13}$** | `233px` | **Alcance Esquerdo da Cabeça Cega** (`x = -233px` — Força Material contida no anel). |
| **$F_{14}$** | `377px` | **Alcance Direito da Ponta Carmesim** (`x = +377px` — Razão perfurando o anel). **Razão Áurea Exata:** $\frac{377}{233} = 1.618025 \approx \varphi$. |
| **$F_{15}$** | `610px` | **Enquadramento Total do Martelo (`610 × 610px`)**: largura total da cabeça (`233 + 377 = 610px`) e altura total do topo do olhal à base do pomo (`123 + 487 = 610px`). |

---

## 3. Tipografia Oficial

1. **Títulos e Axiomas de Impacto (`--font-display`):**
   - **Fonte:** `'Space Grotesk'`, peso `700 (Bold)`, `UPPERCASE`, `letter-spacing: -0.03em`.
2. **Telemetria, Índices, Numeração Romana e Botões (`--font-mono`):**
   - **Fonte:** `'JetBrains Mono'`, pesos `500` e `700`, `UPPERCASE`, `letter-spacing: 0.08em` a `0.12em`.
3. **Corpo Doutrinário e Mandamentos (`--font-sans`):**
   - **Fonte:** `'Inter'`, pesos `400`, `500` e `600`, `line-height: 1.55` a `1.618`.

---

## 4. Os 10 Mandamentos do Teloísmo

1. **I.** Ame a todos, mas a si mesmo primeiro.
2. **II.** Honre a qualquer um, desde que o mérito seja comprovado material e intelectualmente.
3. **III.** Evite o roubo, o assassinato e a irresponsabilidade material ou biológica no mundo.
4. **IV.** Sinta o ódio e as demais emoções, mas submeta a utilidade desses impulsos ao crivo da lógica antes da ação.
5. **V.** Acumule recursos sem culpa sob a mecânica do sistema vigente, mas opere para a superação lógica deste modelo pautado na escassez e miséria estrutural.
6. **VI.** Rejeite a barbárie e a violência gratuita. Contudo, perante ameaça à sua vida ou integridade, a retaliação exata e defensiva é um dever estratégico.
7. **VII.** Abrace seus instintos físicos e emocionais como força motriz; sacie-os, mas aplique escrutínio racional, pois dar sentido estruturado é superior a ser escravo do que se sente.
8. **VIII.** Respeite o direito alheio à fé e ao conforto dogmático, mas exija a separação absoluta entre crença pessoal e fato empírico.
9. **IX.** Repudie o anti-intelectualismo e a ignorância voluntária. Busque a superação contínua de si mesmo, rejeitando a arrogância sem nivelar o conhecimento à mediocridade.
10. **X.** Aceite a própria escuridão. Reconheça e utilize a totalidade de sua natureza humana como ferramenta pragmática, recusando-se permanentemente a ser controlado por ela.

---

## 5. Inventário de Arquivos do Projeto

- `IDENTIDADE_VISUAL_TELOISMO.md` — Manual oficial de especificações técnicas e filosóficas.
- `logo.svg` / `logo_teloista.svg` — Símbolo oficial colorido sobre fundo escuro (`#09090B`).
- `logo_pb_fundo_escuro.svg` — Versão monocromática P&B negativa para fundo escuro.
- `logo_pb_fundo_claro.svg` — Versão monocromática P&B positiva para fundo claro (`#F4F4F5`).
- `logo_cor_fundo_claro.svg` — Versão colorida adaptada para fundo claro (`#F4F4F5`).
- `styles.css` — Folha de estilos oficial baseada nos tokens de Fibonacci.
- `index.html` — Landing page do Manifesto Teloísta com os 10 Mandamentos e matriz de variantes do logo.
- `social-post.svg` — Template `1080×1080` para citações individuais.
- `post_whatsapp_10_mandamentos.html` — Arte HTML no formato vertical padrão `1080×1350` (proporção 4:5 vertical ideal para WhatsApp/Instagram).
- `post_whatsapp_10_mandamentos.png` — Imagem PNG final em `1080×1350` pronta para compartilhamento sem cortes no WhatsApp.
