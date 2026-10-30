# LabFORMA: Gramática da Forma

> **Versão:** 1.0.0  
> **Desenvolvimento:** Prof. Dr. Jarryer Andrade de Martino  
> **Instituição:** Universidade Federal do Espírito Santo (UFES) — Centro de Artes | Departamento de Arquitetura e Urbanismo  
> **Grupo de Pesquisa:** TIP – Tecnologias Integradas ao Projeto  
> **Acesso On-line:** https://jarryerdemartino.github.io/gramaticadaforma

---

## 📌 Informações da Aplicação

| Item | Detalhe |
| :--- | :--- |
| **Nome da Aplicação** | LabFORMA: Gramática da Forma |
| **Autor e Desenvolvedor** | Prof. Dr. Jarryer Andrade de Martino |
| **Instituição** | Universidade Federal do Espírito Santo (UFES) |
| **Centro / Depto.** | Centro de Artes / Departamento de Arquitetura e Urbanismo |
| **Grupo de Pesquisa** | TIP – Tecnologias Integradas ao Projeto |
| **Versão** | 1.0.0 |
| **Ano de Publicação** | 2026 |
| **DOI** | 10.5281/zenodo.23777622 |
| **Registro INPI** | *[em andamento]* |
| **Repositório** | https://github.com/jarryerdemartino/gramaticadaforma |

---

## 📖 Manual do Usuário

### 1. Escolha da Forma Inicial (Passo 1)
No painel lateral esquerdo (ou pelo botão **Regras / Painel** no celular), selecione o sólido inicial: **Cubo (1x1x1)** ou **Paralelepípedo (2x1x1)**.

### 2. Interação 3D e Seleção de Face
Interaja com a janela 3D (arraste para rotacionar e use *pinch/scroll* para zoom). Clique/toque na face em que deseja aplicar uma transformação.

> 💡 **Dica de Interatividade:** Você pode interagir com qualquer sólido que faça parte da composição a qualquer momento.

### 3. Aplicação de Regras Gramaticais (Passo 2)
Com a face selecionada, escolha a regra no painel lateral:
* **Adição (R01 a R05):** Adiciona novos cubos ou paralelepípedos acoplados.
* **Substituição (R06 e R07):** Converte a peça selecionada em outra forma espacial.
* **Subtração (R08 e R09):** Remove da composição o elemento selecionado.

### 4. Registro Processual Gerativo (Linha do Tempo)
Na parte inferior encontra-se o **Registro Processual Gerativo**. Ao clicar em qualquer um dos passos, a composição retoma instantaneamente aquele estado específico do histórico.

### 5. Eixos de Coordenadas no Sistema (Configuração Z-Up)
Nesta interface, o plano do piso é formado pelos eixos X e Y, enquanto o eixo Z representa a altura vertical:
* **Eixo X (Verde):** Dimensão horizontal (Largura).
* **Eixo Y (Vermelho):** Dimensão horizontal (Comprimento / Profundidade).
* **Eixo Z (Azul):** Dimensão vertical (Altura / Elevação).

---

## 🧠 Conceito Teórico: Gramática da Forma

A **Gramática da Forma** é um sistema formal baseado em regras que opera e calcula diretamente com formas bidimensionais ou tridimensionais, em vez de utilizar apenas símbolos ou palavras (Stiny; Gips, 1971; Knight; Stiny, 2015). Formulada originalmente por analogia às gramáticas linguísticas, ela estabelece uma sintaxe geométrica e um formalismo computacional que substitui a intuição puramente subjetiva por um processo gerativo explícito e rigoroso no design (Stiny; Gips, 1971).

Em sua formulação clássica, a Gramática da Forma é definida essencialmente por quatro componentes fundamentais (Stiny; Gips, 1971; Haakonsen; Rønnquist; Labonnote, 2022):
1. **Vocabulário de formas:** Reúne os elementos primitivos de construção da linguagem.
2. **Marcadores:** Símbolos ou formas não terminais que orientam o processo generativo.
3. **Regras de forma:** Instruções de substituição e transformação espacial do tipo $A \rightarrow B$.
4. **Forma inicial:** Ponto de partida a partir do qual as regras são aplicadas recursivamente.

A aplicação do sistema ocorre por meio de um processo recursivo de derivação, no qual o projetista identifica uma subforma na composição e a substitui segundo as regras preestabelecidas, gerando sequências de transformações geométricas (Stiny; Gips, 1971; Knight; Stiny, 2015). Esse método pode ser empregado sob duas abordagens:
* **Analítica:** Voltada para identificar e codificar as regras sintáticas que caracterizam estilos históricos preexistentes.
* **Sintética:** Voltada para a criação de linguagens de projeto inteiramente inéditas (Stiny; Mitchell, 1978; Stiny, 1980).

No campo da arquitetura, destacou-se inicialmente na análise e geração de plantas baixas e fachadas residenciais. Posteriormente, o seu uso expandiu-se para diversas outras áreas como no design de mobiliário, na solução de problemas complexos de arranjo espacial, na otimização de desempenho na engenharia estrutural e no ensino do design por meio da manipulação lógica de blocos geométricos (Stiny; Gips, 1971; Knight, 1980; Stiny, 1980; Hou; Stouffs, 2018).

Atualmente, o método é operacionalizado tanto por meio de softwares e intérpretes computacionais específicos quanto pela integração em plataformas comerciais de modelagem paramétrica e otimização (Haakonsen; Rønnquist; Labonnote, 2022). Paralelamente, desenvolvimentos teóricos mais recentes expandiram o conceito para as "gramáticas do fazer", aproximando a computação gráfica tradicional do engajamento sensorial e da manipulação física direta de materiais no mundo real (Knight; Stiny, 2015).

---

## 📜 Licença de Uso, Reconhecimento de Autoria e Citação

### Licença de Uso
Esta aplicação é disponibilizada gratuitamente para fins educacionais, acadêmicos, científicos e de pesquisa, com o objetivo de contribuir para o ensino, a aprendizagem e a investigação em Arquitetura, Urbanismo, Projeto Arquitetônico, Metodologias de Projeto e Gramática da Forma.

* É permitida sua utilização por estudantes, professores, pesquisadores e profissionais, desde que respeitadas as disposições de reconhecimento de autoria estabelecidas neste documento.
* A utilização da aplicação não implica transferência de propriedade intelectual sobre seus fundamentos teóricos, métodos, algoritmos, processos, modelos computacionais, interface gráfica ou demais elementos que a compõem.
* **É vedada a comercialização da aplicação, bem como sua redistribuição modificada sem autorização expressa do autor.**
* Esta aplicação adota os princípios da licença **Creative Commons Atribuição-NãoComercial 4.0 Internacional (CC BY-NC 4.0)**.

> © 2026. Prof. Dr. Jarryer Andrade de Martino. Todos os direitos reservados.

### Reconhecimento de Autoria
Esta aplicação foi concebida, desenvolvida e implementada pelo **Prof. Dr. Jarryer Andrade de Martino**, docente do Departamento de Arquitetura e Urbanismo do Centro de Artes da Universidade Federal do Espírito Santo (UFES), coordenador do Grupo TIP – Tecnologias Integradas ao Projeto.

O autor é também responsável pela concepção, desenvolvimento e implementação da Gramática da Forma empregada nesta aplicação, bem como pela idealização, projeto, estrutura pedagógica e desenvolvimento computacional da interface.

O projeto conta com apoio institucional da **Universidade Federal do Espírito Santo (UFES)**, Campus Goiabeiras, Vitória, Espírito Santo, Brasil.

Ao utilizar esta aplicação em atividades de ensino, pesquisa, extensão, produção técnica, apresentações, trabalhos acadêmicos, relatórios, artigos científicos, dissertações, teses, projetos profissionais ou quaisquer produtos derivados de sua utilização, solicita-se que seja realizado o devido reconhecimento de autoria mediante citação formal da ferramenta e de seu autor.

### Transparência no Desenvolvimento
Esta aplicação foi produzida com a utilização de ferramentas de Inteligência Artificial Generativa como suporte ao desenvolvimento computacional. Entre as ferramentas empregadas encontram-se o **Google Gemini** e o **Microsoft Copilot**, utilizadas como recursos auxiliares na elaboração, revisão, otimização e depuração de códigos-fonte.

A autoria intelectual da Gramática da Forma, os fundamentos teóricos e metodológicos, a arquitetura do software, a modelagem computacional, a interface gráfica, a estrutura pedagógica e todos os conteúdos disponibilizados nesta interface permanecem integralmente atribuídos ao autor. As ferramentas de IA mencionadas foram utilizadas exclusivamente como instrumentos de apoio ao desenvolvimento técnico, não configurando autoria ou coautoria da aplicação.

---

## 📚 Recomendação de Citação

Os usuários desta aplicação são incentivados a citar a ferramenta sempre que ela contribuir direta ou indiretamente para análises, estudos, exercícios didáticos, processos projetuais, pesquisas ou publicações.

### Referência ABNT (NBR 6023:2018):

```text
MARTINO, Jarryer Andrade de. LabForma: Gramática da Forma. Versão 1.0.0. [Software]. Vitória, ES: Universidade Federal do Espírito Santo, Centro de Artes, Departamento de Arquitetura e Urbanismo, Grupo TIP – Tecnologias Integradas ao Projeto, 2026. Disponível em: https://github.com/jarryerdemartino/gramaticadaforma. Acesso em: [DIA MÊS ANO].
```

### Formas de Citação no Texto ABNT (NBR 10520:2023):

* **Citação indireta (entre parênteses):** `(Martino, 2026)`
* **Citação direta ou menção ao autor na frase:** `Martino (2026)`

---

## 🔬 Referências Bibliográficas

* HAAKONSEN, Sverre Magnus; RØNNQUIST, Anders; LABONNOTE, Nathalie. Fifty years of shape grammars: A systematic mapping of its application in engineering and architecture. *International Journal of Architectural Computing*, v. 20, n. 2, p. 1-18, 2022.
* HOU, Dan; STOUFFS, Rudi. An algorithmic design grammar for problem solving. *Automation in Construction*, v. 94, p. 417-437, 2018.
* KNIGHT, Terry Weissman. The generation of Hepplewhite-style chair-back designs. *Environment and Planning B: Planning and Design*, v. 7, n. 2, p. 227-238, 1980.
* KNIGHT, Terry; STINY, George. Making grammars: From computing with shapes to computing with things. *Design Studies*, v. 41, p. 8-28, 2015.
* STINY, George. Kindergarten grammars: designing with Froebel's building gifts. *Environment and Planning B: Planning and Design*, v. 7, n. 4, p. 407-462, 1980.
* STINY, George; GIPS, James. Shape grammars and the generative specification of painting and sculpture. In: IFIP CONGRESS, 1971, Ljubljana. *Proceedings...* Amsterdam: North-Holland, 1971. p. 125-135.
* STINY, George; MITCHELL, William J. The Palladian grammar. *Environment and Planning B: Planning and Design*, v. 5, n. 1, p. 5-18, 1978.
