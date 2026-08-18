readme nada vibecodado desse site vibecodado

# 📚 Painel de Revisões Espaçadas - Foco ENEM

Uma aplicação web leve, responsiva e pronta para uso, desenvolvida em um único arquivo HTML, com o objetivo de otimizar a preparação para o **ENEM** e vestibulares.

O sistema utiliza a técnica de **Repetição Espaçada (Spaced Repetition)** para combater a Curva do Esquecimento, integrada com um **Rastreador de Desempenho em Questões** e **Controle de Incidência**.

---

## 🚀 Funcionalidades

- **🔄 Algoritmo de Repetição Espaçada:** Recalcula automaticamente as datas de revisão conforme você avança nos ciclos (1 dia $\rightarrow$ 7 dias $\rightarrow$ 15 dias $\rightarrow$ 30 dias $\rightarrow$ 60 dias).
- **🚨 Alerta de Atrasos & Status Visual:** Os assuntos são ordenados cronologicamente:
    - 🚨 **Atrasados:** Destacados em vermelho.
    - ⭐ **Para Hoje:** Destacados em azul brilhante.
    - 💤 **Futuros:** Apresentados de forma suave/opaca até o dia correto.
- **🎯 Rastreador de Questões e Taxa de Acertos:** Registro do número de questões resolvidas e acertos a cada revisão concluída, calculando a taxa de rendimento em porcentagem (%).
- **🔥 Filtro por Incidência no ENEM:** Classificação dos assuntos por prioridade (_Alta Incidência_, _Média_ ou _Baixa_).
- **📊 Painel de Métricas em Tempo Real:** Visualização no topo com total de assuntos pendentes, para hoje, cadastrados e taxa de acerto global.
- **🔍 Busca e Filtros:** Pesquisa por palavra-chave ou filtragem direta por disciplina.
- **💾 Persistência Local:** Todos os dados ficam salvos de forma segura no próprio navegador do usuário (`localStorage`).
- **✏️ Edição e Exclusão:** Gerenciamento simples dos registros.

---

## 📁 Estrutura do Projeto

O projeto adota o conceito de _vibe-coding_, estando totalmente contido em um único arquivo para máxima simplicidade de uso e implantação:

```text
├── index.html       # Contém a estrutura (HTML), estilos (CSS) e lógica (JavaScript)
└── README.md        # Documentação do projeto
```
