# Portal de Candidaturas (Redesign Cebraspe)

![Status](https://img.shields.io/badge/Status-Concluído-success)
![Disciplina](https://img.shields.io/badge/Disciplina-IHC-blue)

Um protótipo de alta fidelidade desenvolvido como projeto acadêmico para a disciplina de **Interação Humano-Computador (IHC)**. O objetivo deste projeto foi recriar e otimizar a experiência do usuário (UX) e a interface (UI) do processo de matrícula e acompanhamento de candidaturas do Cebraspe, focando em uma abordagem moderna, intuitiva e *Mobile-First*.

---

## 👨‍🎓 Informações Acadêmicas

* **Professor:** Lucas Rodrigues da Silva

* **Aluno:** Enzo Gazolla Nagano
* **RA:** 22401710


---

## 🎯 Objetivo do Projeto

O **Portal de Candidaturas** resolve dores comuns encontradas em processos seletivos e matrículas de universidades, propondo:
- **Navegação Linear:** Um fluxo em etapas claras (Stepper) que guia o usuário do início ao fim sem perda de contexto.
- **Feedback Visual:** Alertas, barras de progresso dinâmicas e transições visuais de estado (ex: botão de gerar PIX).
- **Consistência:** Um *Design System* padronizado focado em usabilidade com cores acessíveis e tipografia legível.
- **Prevenção de Erros:** Validação de campos obrigatórios (ex: E-mail e regras de preenchimento) antes de avançar para a próxima etapa.

---

## 🚀 Funcionalidades e Telas Principais (Happy Path)

O projeto simula um fluxo real de ponta a ponta (Happy Path), contemplando:

1. **Dashboard (`portal.html`):** Visão geral do status do candidato e acesso rápido a inscrições.
2. **Matrícula (`matricula.html`):** Escolha de Curso e Campus de preferência.
3. **Dados Pessoais (`pessoal.html`):** Formulário de coleta com máscaras de dados e validação de e-mail e preenchimento.
4. **Documentos (`documentos.html`):** Envio simulado de arquivos exigidos com validação de obrigatoriedade.
5. **Revisão (`revisao.html`):** Resumo completo dos dados preenchidos pelo usuário com opções fluidas de retorno e edição.
6. **Finalização (`finalizacao.html`):** Emissão de taxa de pagamento (simulação de geração de PIX via JS) e fechamento do ciclo.

**Extras:**
* Lógica simulada de atalho ("Salvar para depois") que ilustra de forma didática o bloqueio de progressão sem preenchimento correto de dados.
* Caixa de entrada de notificações (`inbox.html`).
* Gerenciamento de conta do candidato (`conta.html`).

---

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído "do zero" (Vanilla) para garantir máxima performance e controle absoluto da interface, sem o uso de frameworks pesados:

* **HTML5:** Estrutura semântica e acessível.
* **CSS3:** Estilização baseada em Flexbox/Grid, responsividade Mobile-First, variáveis CSS e micro-interações.
* **JavaScript:** Validações de formulário, lógica de UI (modais, mudanças de estado e navegação simulada).
* **Phosphor Icons:** Biblioteca de ícones utilizada para enriquecer a experiência visual.

---

## 📥 Como executar o projeto

Como trata-se de um projeto front-end puramente em HTML/CSS/JS, **não é necessária nenhuma instalação ou configuração de servidor**.

1. Clone o repositório ou baixe a pasta do projeto.
2. Dê um duplo clique no arquivo `index.html` (ou `portal.html` para pular o login direto para a dashboard).
3. O projeto abrirá em seu navegador padrão. Recomenda-se utilizar a ferramenta de desenvolvedor do navegador (F12) no modo de **dispositivo móvel** para a melhor experiência de visualização!

---

> Projeto criado com foco em excelência de experiência de usuário (UX) e alta fidelidade visual de interface (UI).
