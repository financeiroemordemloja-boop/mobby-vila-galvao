# Mobby Vila Galvão — Gestão do Síndico

Gêmeo digital (PropTech) do Condomínio Mobby Vila Galvão (Av. São Bento, 1689 — Vila Galvão, Guarulhos/SP), com a torre em 3D e o painel de gestão do síndico.

> Todos os dados de moradores, boletos, chamados e reservas são **fictícios**, gerados para demonstração.

## Como abrir

Abra o `index.html` em um navegador moderno (Chrome, Edge, Firefox). Não precisa instalar nada: o Three.js é carregado via CDN (precisa de internet).

`mobby-vila-galvao.html` é a mesma página no formato usado para publicar como Artifact no claude.ai (sem as tags `<html>/<head>/<body>`). Sempre edite o `index.html` e gere essa cópia a partir dele.

## Funcionalidades

- **Torre 3D interativa** (Three.js): 15 andares × 8 apartamentos, varandas com terraço grill clicáveis, hover, navegação por andares, rotação automática e vistas pré-definidas.
- **Modos de visualização**: Visão Realista, Mapa de Inadimplência e Alertas de Manutenção.
- **Áreas comuns**: Piscina, Área Gourmet, Salão de Festas, Coworking, Lavanderia Compartilhada, Pet Care e Playground.
- **Painel da unidade** com abas: Resumo e Moradores, Financeiro (histórico de 6 meses e 2ª via simulada), Ocorrências (anotações do síndico) e Reservas e Consumo (água e gás).
- **KPIs**: taxa de ocupação, inadimplência total, chamados abertos e reservas do dia.
- **Busca** por número do apartamento ou nome do morador, com foco automático da câmera.

As alterações (anotações, reservas, envios de 2ª via) ficam salvas no `localStorage` do navegador.
