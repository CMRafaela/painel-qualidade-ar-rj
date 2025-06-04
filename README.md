# 🌬️ Painel de Qualidade do Ar

Esse projeto é parte de um desafio técnico.  
O objetivo é oferecer aos cidadãos um painel que exibe, de forma clara e acessível, a qualidade do ar em diferentes bairros do Rio de Janeiro.

---

## 🚀 Tecnologias Utilizadas

- **Next.js 15**  
- **React 19**  
- **TypeScript**  
- **Tailwind CSS**  
- **Leaflet + React Leaflet** (para exibir um mapa interativo com os bairros do RJ)  
- **Recharts**  
- **Vitest + Testing Library** (para testes unitários)

---

## ✨ Funcionalidades Implementadas

- Visualização da qualidade do ar por bairro no Mapa Interativo.  
- Tabela com dados recentes de qualidade do ar.  
- Filtros por bairro e qualidade.  
- Alternância entre visualização de mapa e tabela.  
- Exibição de detalhes e gráfico em modal ao clicar em um bairro.  
- Dados simulados via API mockada interna (`/api/qualidade-ar`).  
- Responsividade para dispositivos móveis.  
- Acessibilidade com uso de labels, roles e navegação por teclado.  
- Testes automatizados com Vitest para componentes e interações principais.

---

## 🧠 Decisões Técnicas

- O projeto foi iniciado com o template oficial do **Next.js 15** com **App Router** e **Tailwind CSS**.  
- Utilizei componentização para garantir reutilização e facilitar os testes.  
- Como o SWC do Next não é compatível com todas as bibliotecas de testes, optei por usar Babel com Vitest.  
- As fontes foram configuradas manualmente via CSS para evitar conflito com `next/font` ao usar Babel.  
- Os dados estão mockados internamente na rota `src/app/api/qualidade-ar/route.ts`, simulando uma API REST.

---

## 🛠️ Como Rodar o Projeto Localmente

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/seu-repo.git

# Acesse a pasta do projeto
cd seu-repo

# Instale as dependências
npm install

# Rode o servidor local
npm run dev
