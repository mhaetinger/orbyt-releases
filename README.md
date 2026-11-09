# Orbyt

**Controle financeiro pessoal offline com assistente de IA**

Versão atual: [Orbyt v1.68.9+176](https://github.com/mhaetinger/orbyt-releases/releases/tag/v1.68.9).
[Baixar APK](https://github.com/mhaetinger/orbyt-releases/releases/download/v1.68.9/app-release.apk).

---

## 📲 Como instalar

1. Vá até a aba **[Releases](../../releases)** (menu à direita desta página)
2. Baixe o arquivo `app-release.apk` da versão mais recente
3. No celular: **Configurações → Segurança → Permitir instalação de apps de fontes desconhecidas**
4. Abra o arquivo baixado e confirme a instalação

> **Atualização automática:** após instalar, o Orbyt verifica novas versões ao abrir e oferece atualizar com um toque — sem precisar voltar aqui.

---

## ✨ O que o Orbyt faz

### 💰 Controle financeiro completo
- Registre receitas e despesas por categoria
- Planejador mensal com visão trimestral e tabela anual
- Projeção do saldo ao final do ano baseada nos meses anteriores
- Atualização manual e sincronização automática em primeiro plano, a cada 5 minutos

### 💳 Cartões de crédito
- Fatura calculada automaticamente e exibida no Planejador como despesa
- Compras parceladas distribuídas pelos meses seguintes
- Suporte a qualquer banco brasileiro via BrasilAPI (com busca por nome)
- Gerencie múltiplos cartões com dia de vencimento e banco personalizados

### 🔄 Transações recorrentes
- Crie uma cobrança recorrente (aluguel, assinatura, salário…) uma única vez
- O app gera uma ocorrência por competência ao navegar pelos meses, preservando parcelas adiantadas
- Exclua apenas uma ocorrência ou todas as futuras

### 🤖 Orbyt AI — assistente de finanças
- Botão flutuante disponível em todas as telas
- Converse por texto ou voz (microfone com animação de ondas)
- O assistente consulta seu saldo, lista transações, navega pelo app e cria lançamentos direto no chat
- Confirme antes de salvar: o assistente mostra um preview das transações antes de registrar

### 🔐 Segurança
- Dados salvos localmente com banco de dados criptografado
- Login com digital ou reconhecimento de rosto (biometria nativa do celular)
- Bloqueio de captura de tela e thumbnail no histórico de apps
- Autenticação via e-mail/senha ou conta Google

### ☁️ Offline-first com sincronização na nuvem
- Cadastro e planejamento funcionam sem internet; o chat da IA exige conexão
- Quando conectado, sincroniza automaticamente com a nuvem
- Ao voltar do background, sincroniza em segundo plano

### 🎨 Personalização
- 4 temas de fundo: Padrão, Campo Estelar animado, Gradiente Espacial, Escuro Total
- Modo para daltonismo: receitas em ciano e despesas em magenta (em vez de verde/vermelho)

---

## 📋 Histórico de versões

### v1.68.9
- Cabeçalho e botões da fatura menores, compras separadas visualmente e categoria sem ocupar outra linha alta
- Acesso próprio às assinaturas cadastradas, mesmo sem cobrança no mês
- Botão Pagar / adiantar com altura visual reduzida
- Organizar e Recolher/Expandir na mesma linha, preservando a ordenação

### v1.68.8
- Planejador aproveita a tela atrás da barra inferior recolhida; espaço de proteção só no fim da lista
- Cabeçalho menor; controles extras saem da tela ao rolar e o mês continua visível
- Cartões compactos nos tamanhos Pequena e Padrão, com valor e pagamento na mesma linha quando couberem
- Fonte ampliada mantém adaptação sem esconder valores ou ações

### v1.68.7
- Editar e excluir pagamento pelo próprio lançamento, preservando vínculo e saldo
- Mês e valores completos; botões e cabeçalhos reorganizados para telas pequenas
- Organização em lista estável, com Aplicar e Cancelar
- Categorias nas compras, parcelas e assinaturas do cartão, refletidas nas análises
- Colar, substituir e apagar valores corrigidos no campo monetário

### v1.68.6
- Débito, Pix e boleto vinculados à recorrência contam uma vez; dados antigos são reparados na sincronização
- Corrigir vínculo e Desfazer no sino, com restauração do saldo e revisão da associação aprendida
- Pagamento e adiantamento de fatura no Planejador, identificado e vinculado ao cartão
- Organização simplificada e comprovantes com revisão, confirmação e identificação da origem
- Seleção de 16 bancos, mesmo sem cartão de crédito cadastrado

### v1.68.5
- Efetivadas do mês continuam contando ao selecionar um dia anterior
- Saldo acumulado de volta ao topo e resultado mensal separado
- Pagamentos já registrados e adiantamentos preservados ao navegar pelos dias
- Organizar separado dos filtros; Por dia/Por categoria ligam e desligam
- Categorias atualizam os grupos com a tela aberta; ajuda e tutorial revisados
- 667 testes passaram e análise sem problemas; conferir os ajustes no telefone

### v1.68.4
- Resultado mensal em destaque e pagamentos anteriores já abatidos desde o dia 1
- Histórico acumulado separado, preservando a saída no mês do pagamento
- Por dia liga/desliga e mantém a escolha ao reabrir
- Resumo para valores grandes/fonte ampliada; ajuda e tutorial atualizados
- 659 testes passaram e análise sem problemas; conferir os ajustes no telefone

### v1.68.3
- Lembretes abrem o Planejador; Sim, efetivar / Ainda não no sino e no Android
- Pagamento parcial ou antecipado de fatura com conta e data
- Análises por categoria, navegação por dia e lista diária recolhível
- Comprovantes compartilhados e extratos OFX/CSV com revisão
- Revisão de recorrência, saldo/desfazer, datas e conversas da IA
- Formulários do cartão com valor antes do nome
- 648 testes passaram; notificações, OCR e respostas financeiras da IA precisam da conferência no aparelho

### v1.15.1
- 🐛 Login com digital/rosto não trava mais ao ativar nas configurações de Perfil
- 🐛 Samsung Pass e outros gerenciadores de senha agora oferecem salvar as credenciais após o login

### v1.15.0
- 🎨 Seletor visual de fundo com prévia ao vivo de cada tema
- 🔑 Login com Google funciona corretamente no Android
- 🔐 Ativar biometria agora exige confirmação da senha atual para mais segurança
- 🔄 App detecta novas versões e baixa/instala automaticamente

### v1.14.0
- 🌈 Modo daltônico: cores distintas para receita (ciano) e despesa (magenta)
- 💳 Cartões: botão ⋮ para Editar ou Excluir direto no card (sem precisar deslizar)
- 📊 Projeção anual visível no resumo mensal do Planejador
- 💳 Banco do cartão selecionado pela BrasilAPI completa com campo de busca

### v1.13.0
- 💳 Seção de cartões aparece em todos os meses, mesmo sem compras no período
- 💳 Toque no cartão para editar nome, banco e dia de vencimento
- 🔄 "Tornar recorrente" disponível também no Planejador, não só em Transações

### v1.12.0
- 💳 Fatura do cartão integrada ao Planejador como despesa automática do mês
- 💳 Compras parceladas: o valor total é dividido e lançado nos meses seguintes
- 💳 Gerencie múltiplos cartões pelo Planejador

### v1.11.0
- 🔄 Transações recorrentes: crie uma vez, o app repete automaticamente por 12 meses
- 🏦 Banco associado a transações com badge discreto no card
- 📅 Planejador: deslize horizontalmente para navegar entre meses

### v1.10.0
- 👤 Altere seu e-mail diretamente pelo app sem precisar sair da conta
- 🤖 Assistente IA com correções de estabilidade

### v1.9.0
- 🔑 Troque sua senha diretamente pelo app (sem receber link por e-mail)
- 👤 Botão "Sair da conta" no rodapé do Perfil

### v1.8.0
- 🎤 Assistente IA com microfone — fale e o texto é digitado automaticamente
- 🔐 Após o primeiro login, o app oferece ativar o login biométrico

### v1.7.0
- 👆 Login com digital ou Face ID
- 🎤 Chat da IA com campo de texto multilinha e animação de onda de áudio no microfone

### v1.5.0
- 🤖 Orbyt AI: assistente de finanças integrado em todas as telas
- 🎙️ Controle por voz — navegue, consulte saldo e crie transações falando

### v1.4.0
- 🔒 Banco de dados criptografado no celular
- 📵 Bloqueio de capturas de tela e thumbnail no histórico de apps

### v1.3.0
- 🧭 Navbar flutuante inteligente (recolhe ao rolar, expande ao tocar)
- 📅 Visão anual do planejador organizada por trimestre
- 🔄 Patrimônio atualizado automaticamente ao adicionar transações

---

## 📱 Requisitos

- Android 7.0 (API 24) ou superior
- Espaço livre para baixar o APK e instalar a atualização

---

*Projeto pessoal — distribuição por APK*
