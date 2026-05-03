# 💸 Meus Gastos

> Aplicação web para controle e acompanhamento de gastos mensais — simples, visual e direto ao ponto.

🔗 **[Acesse o app →](https://gestao-de-gastos-six.vercel.app)**

---

## ✨ Funcionalidades

- **Dashboard** — visão geral do mês com cards de resumo (total gasto, saldo do orçamento, maior gasto e média diária)
- **Gráficos interativos** — gastos por categoria, orçado vs. real e evolução mensal dos últimos 5 meses com dados reais
- **Detalhamento por categoria** — matriz expansível com colunas Orçado / Real / Desvio; clique em uma categoria para ver cada lançamento individualmente
- **Lançar gastos** — formulário para registrar despesas com descrição, valor, data, categoria e tipo de imóvel
- **Histórico completo** — tabela filtrável por categoria (chips) e por descrição (busca em tempo real), com total do filtro visível
- **Orçamento por categoria** — defina metas mensais e acompanhe o consumo em tempo real com barras de progresso
- **Navegação por mês** — navegue entre meses para analisar períodos anteriores
- **Suporte mobile** — barra de navegação inferior fixada no rodapé, acessível em qualquer dispositivo

## 🗂️ Categorias suportadas

| Categoria | | Categoria | |
|---|---|---|---|
| 🏠 Moradia | | 💡 Contas fixas | |
| 🛒 Alimentação | | 🚗 Transporte | |
| 🧴 Higiene & Limpeza | | 🏥 Saúde | |
| 🎮 Lazer | | 💰 Reserva | |
| 🐾 Petz | | 📦 Outros | |

## 🛠️ Tecnologias

- **HTML5** — estrutura semântica
- **CSS3** — design system próprio com variáveis CSS, dark mode nativo, layout responsivo
- **JavaScript (Vanilla)** — sem frameworks, sem dependências de build
- **[Chart.js 4.4](https://www.chartjs.org/)** — gráficos interativos
- **[DM Sans + DM Serif Display](https://fonts.google.com/)** — tipografia via Google Fonts
- **[Supabase](https://supabase.com/)** — banco de dados PostgreSQL + autenticação via e-mail e senha
- **[Vercel](https://vercel.com/)** — deploy e hospedagem

## 🚀 Como usar

Por ser um arquivo HTML único, não há instalação ou build necessário:

```bash
# Clone o repositório
git clone https://github.com/rvbittencourt07/gestao-de-gastos.git

# Abra o arquivo no navegador
# Duplo clique em index.html
# — ou —
# Use uma extensão como Live Server no VS Code
```

## 📁 Estrutura do projeto

```
gestao-de-gastos/
└── index.html   # Aplicação completa (HTML + CSS + JS)
```

## 🗺️ Roadmap

- [x] Migrar persistência de `localStorage` para **Supabase**
- [x] Autenticação via e-mail e senha
- [x] Publicar no **Vercel**
- [x] Filtro por categoria e busca por descrição no histórico
- [x] Detalhamento por categoria com matriz orçado/real/desvio
- [x] Suporte mobile com bottom navigation bar
- [x] Categoria **Petz** 🐾
- [ ] Exportar dados em CSV
- [ ] Confirmação antes de deletar um gasto
- [ ] Suporte a múltiplos usuários (imóvel alugado vs. financiado)

## 📄 Licença

Projeto pessoal — uso livre.
