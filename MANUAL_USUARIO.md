# 📘 MANUAL DO USUÁRIO - LEGADO AI

## ÍNDICE

1. [Introdução](#1-introdução)
2. [Autenticação](#2-autenticação)
3. [Dashboard - Visão Geral](#3-dashboard---visão-geral)
4. [Funcionárias IA (Agentes)](#4-funcionárias-ia-agentes)
5. [Negócios](#5-negócios)
6. [Mensagens](#6-mensagens)
7. [Configurações](#7-configurações)
8. [Fluxo Recomendado](#8-fluxo-recomendado-para-iniciantes)
9. [Glossário](#9-glossário)

---

## 1. INTRODUÇÃO

O **Legado AI** é uma plataforma de automação de atendimento via WhatsApp utilizando Inteligência Artificial. Com ele, você pode:

- ✅ Criar "funcionárias virtuais" que respondem automaticamente via WhatsApp
- ✅ Gerenciar múltiplos negócios em uma única conta
- ✅ Acompanhar métricas de performance em tempo real
- ✅ Intervir manualmente quando necessário
- ✅ Economizar tempo com automação inteligente

### 1.1 Navegação Principal

O menu lateral (sidebar) contém as seguintes opções:

| Ícone | Menu | Descrição |
|-------|------|-----------|
| 📊 | Dashboard | Visão geral e métricas |
| 🤖 | Funcionárias IA | Gerenciar agentes virtuais |
| 🏢 | Negócios | Cadastrar e gerenciar empresas |
| 💬 | Mensagens | Visualizar e responder conversas |
| ⚙️ | Configurações | Perfil, segurança e conta |

---

## 2. AUTENTICAÇÃO

### 2.1 Login

**Caminho:** Acesso inicial do sistema

**Campos:**
- **Email:** Seu email cadastrado
- **Senha:** Sua senha de acesso

**Passo a passo:**
1. Acesse a URL do sistema
2. Digite seu email no campo "Email"
3. Digite sua senha no campo "Senha"
4. Clique em **"Entrar"**

**💡 Dica:** Caso tenha esquecido a senha, clique em "Esqueceu a senha?" abaixo do campo de senha.

---

### 2.2 Cadastro de Nova Conta

**Caminho:** Tela de Login → "Cadastre-se"

**Campos obrigatórios:**
- **Nome Completo:** Seu nome para identificação
- **Email:** Email válido para login
- **Senha:** Mínimo de 6 caracteres
- **Confirmar Senha:** Repetir a senha

**Passo a passo:**
1. Na tela de login, clique em **"Cadastre-se"**
2. Preencha todos os campos
3. Clique em **"Criar Conta"**
4. Você será redirecionado automaticamente para o Dashboard

---

### 2.3 Recuperação de Senha

**Caminho:** Tela de Login → "Esqueceu a senha?"

**Passo a passo:**
1. Na tela de login, clique em **"Esqueceu a senha?"**
2. Digite seu email cadastrado
3. Clique em **"Enviar Link de Recuperação"**
4. Verifique sua caixa de entrada (e spam)
5. Clique no link recebido por email
6. Defina sua nova senha

---

## 3. DASHBOARD - VISÃO GERAL

**Caminho:** Menu → Dashboard (ícone 📊)

O Dashboard é dividido em duas seções principais:

### 3.1 Cards de Estatísticas Gerais

Na parte superior, você verá 4 cards com informações resumidas:

| Card | Descrição |
|------|-----------|
| **Total de Negócios** | Quantidade de negócios cadastrados na sua conta |
| **Agentes Ativos** | Proporção de agentes ativos vs total (ex: 2/3) |
| **Conversas Ativas** | Conversas em andamento no momento |
| **Mensagens Hoje** | Total de mensagens trocadas no dia |

---

### 3.2 Performance da IA

Abaixo dos cards gerais, há a seção de métricas avançadas:

#### 3.2.1 Filtros

Você pode filtrar os dados por:

**Período:**
- Hoje
- Últimos 7 dias
- Últimos 30 dias
- Período personalizado (selecionar datas)

**Funcionária:** Filtrar por agente específico ou "Todos"

#### 3.2.2 KPIs (Indicadores de Performance)

5 cards com métricas-chave:

| KPI | O que significa |
|-----|-----------------|
| **Conversas Automatizadas** | % de conversas resolvidas 100% pela IA |
| **Tempo de 1ª Resposta** | Tempo médio até a primeira resposta |
| **Handover para Humano** | % de conversas que precisaram de intervenção |
| **Conversas Resolvidas** | Total de conversas finalizadas no período |
| **Tempo Economizado** | Horas economizadas pela automação |

**💡 Dica:** Passe o mouse sobre cada card para ver uma explicação detalhada.

---

#### 3.2.3 Gráficos e Visualizações

**a) Mensagens por Hora**
- Gráfico de área mostrando volume de mensagens ao longo do dia
- Linha azul: Mensagens recebidas
- Linha roxa: Mensagens enviadas
- Útil para identificar horários de maior movimento

**b) Taxa de Automação por Dia**
- Gráfico de linha mostrando % de automação diária
- Linha pontilhada: Meta de 80% (referência)
- Quanto maior a taxa, mais eficiente está a automação

**c) Tempo de Primeira Resposta (Boxplot)**
- Distribuição estatística dos tempos de resposta
- Mostra mediana, quartis e outliers
- Ajuda a identificar consistência no atendimento

**d) Mapa de Calor (Heatmap)**
- Volume de conversas por hora × dia da semana
- Verde mais escuro = maior volume de conversas
- Útil para identificar horários de pico e planejar recursos

**e) Tempo Economizado**
- Gráfico de linha mostrando horas economizadas por dia
- Cálculo baseado em: 2min primeira resposta + 5min tratamento humano
- Demonstra o ROI da automação

---

## 4. FUNCIONÁRIAS IA (AGENTES)

**Caminho:** Menu → Funcionárias IA (ícone 🤖)

### 4.1 Visão Geral

Nesta tela você gerencia suas "funcionárias virtuais" - os agentes de IA que respondem pelo WhatsApp.

### 4.2 Filtros de Busca

- **Campo de busca:** Buscar por nome da funcionária
- **Filtro por negócio:** Mostrar apenas agentes de um negócio específico
- **Filtro por status:** Ativo, Inativo ou Em Treinamento

---

### 4.3 Criar Nova Funcionária

**Passo a passo:**
1. Clique no botão **"+ Nova Funcionária"** (canto superior direito)
2. Preencha os campos:
   - **Avatar:** Clique para fazer upload de uma foto (opcional)
   - **Nome do Agente:** Nome que aparecerá nas conversas (ex: "Maria")
   - **E-mail do Google Calendar:** Para agendamentos (opcional)
   - **Negócio:** Selecione a qual negócio pertence ⚠️ **OBRIGATÓRIO**
   - **Cargo:** Função do agente (ex: "Atendente")
   - **Status:** Ativo, Inativo ou Em Treinamento
   - **Descrição:** Breve descrição do agente
3. Clique em **"Salvar"**
4. Um QR Code será exibido para conectar o WhatsApp

---

### 4.4 Conectar WhatsApp

Após criar a funcionária, é necessário vincular um número de WhatsApp:

**Passo a passo:**
1. O modal com QR Code aparecerá automaticamente
2. No celular, abra o WhatsApp
3. Vá em **Configurações → Dispositivos Conectados → Conectar Dispositivo**
4. Escaneie o QR Code exibido na tela
5. Aguarde a confirmação "Conectado"

**Status de conexão:**

| Ícone | Status | Significado |
|-------|--------|-------------|
| 🟢 | Conectado | WhatsApp funcionando normalmente |
| 🟡 | Conectando | Aguardando conexão |
| 🔴 | Desconectado | Precisa reconectar |

---

### 4.5 Card da Funcionária - Funcionalidades

Cada funcionária é exibida em um card com as seguintes opções:

**Informações exibidas:**
- Avatar e nome
- Cargo/função
- Status de conexão (badge colorido)
- Negócio vinculado
- Quantidade de mensagens enviadas

**Botões de ação (no canto superior direito):**

| Ícone | Ação | Quando usar |
|-------|------|-------------|
| 🔄 | Reconectar WhatsApp | Quando o status está "Desconectado" |
| 🕐 | Sincronizar histórico | Para importar mensagens antigas |
| 📱 | Conectar WhatsApp | Exibir QR Code novamente |
| ✏️ | Editar informações | Alterar dados da funcionária |
| 🗑️ | Excluir funcionária | Remover permanentemente |

**Controle de Pausa Global:**
- **Switch "Pausa Global"**: Liga/desliga todas as respostas automáticas
- 🔴 **Quando ativado (vermelho):** O agente NÃO responde nenhuma conversa
- 🟢 **Quando desativado (verde):** O agente responde normalmente

**💡 Dica:** Use a pausa global durante férias ou manutenção.

---

### 4.6 Editar Funcionária

**Passo a passo:**
1. No card da funcionária, clique no ícone de **lápis** (✏️)
2. Altere os campos desejados
3. Clique em **"Salvar"**

---

### 4.7 Excluir Funcionária

**Passo a passo:**
1. No card da funcionária, clique no ícone de **lixeira** (🗑️)
2. Confirme a exclusão clicando em **"Deletar"**

⚠️ **ATENÇÃO:** Esta ação é irreversível! Todas as conversas e dados vinculados serão perdidos.

---

## 5. NEGÓCIOS

**Caminho:** Menu → Negócios (ícone 🏢)

### 5.1 Visão Geral

Gerencie as empresas/negócios aos quais suas funcionárias virtuais estão vinculadas. Cada negócio pode ter múltiplas funcionárias IA.

### 5.2 Criar Novo Negócio

**Passo a passo:**
1. Clique em **"+ Novo Negócio"** (canto superior direito)
2. Preencha os campos:
   - **Logo:** Upload de imagem (opcional, recomendado)
   - **Nome do Negócio:** Nome da empresa ⚠️ **OBRIGATÓRIO**
   - **Setor:** Ramo de atuação (ex: "E-commerce", "Moda", "Serviços")
   - **Descrição:** Descrição detalhada da empresa
   - **Website:** URL do site institucional
   - **Telefone:** Telefone de contato
3. Clique em **"Salvar"**

---

### 5.3 Card do Negócio

Cada negócio é exibido em um card contendo:
- **Logo** (se cadastrado) e **nome** do negócio
- **Badge com o setor** de atuação
- **Descrição** resumida
- **Links rápidos** para:
  - 🌐 Website (abre em nova aba)
  - ✉️ Email (abre cliente de email)
  - 📞 Telefone (abre discador em dispositivos móveis)

**Ações disponíveis:**
- ✏️ **Editar:** Alterar informações do negócio
- 🗑️ **Excluir:** Remover negócio

⚠️ **Observação:** Não é possível excluir um negócio que possui funcionárias vinculadas. Primeiro, remova ou transfira as funcionárias.

---

## 6. MENSAGENS

**Caminho:** Menu → Mensagens (ícone 💬)

### 6.1 Estrutura da Tela

A tela é dividida em duas partes:

- **Lado esquerdo:** Lista de conversas
- **Lado direito:** Histórico de mensagens da conversa selecionada

---

### 6.2 Lista de Conversas

**Filtrar por agente:**
- Use as **abas no topo** para filtrar conversas por funcionária
- A aba **"Todos"** mostra conversas de todas as funcionárias

**Informações exibidas em cada conversa:**
- Avatar do agente responsável
- Nome e telefone do cliente
- Prévia da última mensagem
- Tempo desde a última mensagem (ex: "há 5 minutos")
- **Status da conversa:**
  - 🟢 **Ativa:** Em andamento
  - 🔵 **Fechada:** Finalizada
  - 📦 **Arquivada:** Arquivada para histórico
- **Badge "Manual":** Aparece quando você assumiu o atendimento

---

### 6.3 Assumir Atendimento (Handover)

**O que é:** Pausar a IA e responder manualmente ao cliente.

**Quando usar:**
- Situações complexas que requerem julgamento humano
- Cliente solicita falar com atendente
- Negociações ou tratativas especiais

**Passo a passo:**
1. Selecione a conversa na lista
2. Clique no botão **"Assumir Atendimento"** (ícone de mão ✋)
3. A IA para de responder automaticamente
4. Você pode digitar suas respostas manualmente
5. Um badge **"Manual"** aparece na lista de conversas

**Para devolver para a IA:**
1. Clique em **"Retornar para Agente"** (ícone de robô 🤖)
2. A IA volta a responder automaticamente
3. O badge "Manual" é removido

---

### 6.4 Visualizar Mensagens

Ao selecionar uma conversa, o histórico completo é exibido:

**Layout das mensagens:**
- **Mensagens do cliente:** 
  - Fundo cinza claro
  - Alinhadas à esquerda
  - Avatar do cliente

- **Mensagens da IA/suas:** 
  - Fundo roxo (cor primária)
  - Alinhadas à direita
  - Avatar da funcionária

**Indicadores de status (mensagens enviadas):**
- ✓ (um check cinza): Mensagem **enviada**
- ✓✓ (dois checks azuis): Mensagem **entregue**
- ✓✓ (dois checks azuis preenchidos): Mensagem **lida**

**Informações exibidas:**
- Texto da mensagem
- Data e hora de envio
- Status de entrega (para mensagens enviadas)

---

### 6.5 Enviar Mensagem Manual

**Passo a passo:**
1. Clique em uma conversa (lado esquerdo)
2. Digite sua mensagem no **campo de texto** (parte inferior)
3. Opções para enviar:
   - Pressione **Enter** para enviar
   - Clique no botão **Enviar** (ícone ➡️)

**💡 Dicas:**
- Use **Shift+Enter** para quebrar linha sem enviar
- Mensagens podem ter até 4096 caracteres

---

## 7. CONFIGURAÇÕES

**Caminho:** Menu → Configurações (ícone ⚙️)

A tela de configurações é dividida em **3 abas:**

### 7.1 Aba: Perfil

**O que você pode fazer:**
- **Alterar avatar:** Clique no ícone de câmera sobre a foto de perfil
- **Alterar nome completo:** Edite o campo "Nome Completo"
- **Visualizar email:** O email é exibido, mas não pode ser alterado

**Passo a passo para salvar:**
1. Faça as alterações desejadas
2. Clique em **"Salvar Alterações"**
3. Aguarde a confirmação "Perfil atualizado com sucesso"

---

### 7.2 Aba: Segurança

**Alterar senha:**

| Campo | Descrição |
|-------|-----------|
| **Senha Atual** | Digite sua senha atual para confirmar identidade |
| **Nova Senha** | Mínimo de 6 caracteres |
| **Confirmar Nova Senha** | Repetir a nova senha (deve ser igual) |

**Passo a passo:**
1. Clique na aba **"Segurança"**
2. Preencha os três campos
3. Clique em **"Alterar Senha"**
4. Aguarde a confirmação

**Requisitos de senha:**
- ✅ Mínimo 6 caracteres
- ✅ Recomendado: Combinar letras, números e símbolos

---

### 7.3 Aba: Zona de Perigo

⚠️ **ATENÇÃO: Ações irreversíveis e permanentes!**

**Deletar Conta:**
Esta ação irá:
- ❌ Remover permanentemente sua conta
- ❌ Excluir todos os negócios cadastrados
- ❌ Excluir todas as funcionárias IA
- ❌ Apagar todas as conversas e mensagens
- ❌ Remover todos os dados vinculados

**Passo a passo:**
1. Clique na aba **"Zona de Perigo"**
2. Clique no botão vermelho **"Deletar Minha Conta"**
3. Um diálogo de confirmação aparecerá
4. Digite sua **senha** para confirmar
5. Clique em **"Sim, Deletar Conta"**
6. Você será deslogado imediatamente

⚠️ **Esta ação NÃO PODE ser desfeita. Todos os dados serão perdidos permanentemente.**

---

## 8. FLUXO RECOMENDADO PARA INICIANTES

Siga este passo a passo para começar a usar o sistema:

```
1️⃣ Criar conta (Signup)
      ↓
2️⃣ Fazer login
      ↓
3️⃣ Cadastrar seu primeiro NEGÓCIO
      ↓
4️⃣ Criar sua primeira FUNCIONÁRIA IA
      ↓
5️⃣ Conectar o WhatsApp (escanear QR Code)
      ↓
6️⃣ Aguardar clientes enviarem mensagens
      ↓
7️⃣ Acompanhar métricas no DASHBOARD
      ↓
8️⃣ Intervir manualmente quando necessário (MENSAGENS)
      ↓
9️⃣ Otimizar com base nas métricas
```

### Dicas para primeiros passos:

**✅ Configure seu negócio com informações completas**
- Logo profissional
- Descrição clara do que faz
- Links de contato atualizados

**✅ Treine sua funcionária IA**
- Use descrições detalhadas
- Configure instruções específicas (se disponível)
- Defina o cargo/função claramente

**✅ Teste antes de divulgar**
- Envie mensagens de teste
- Verifique se as respostas fazem sentido
- Ajuste conforme necessário

**✅ Monitore regularmente**
- Acesse o Dashboard diariamente
- Identifique padrões nas métricas
- Intervenha quando necessário

---

## 9. GLOSSÁRIO

### Termos Técnicos

| Termo | Significado |
|-------|-------------|
| **Agente / Funcionária IA** | Robô virtual que responde automaticamente no WhatsApp usando Inteligência Artificial |
| **Handover** | Transferência de atendimento da IA para um atendente humano |
| **Pausa Global** | Recurso para desativar temporariamente todas as respostas automáticas de um agente específico |
| **Taxa de Automação** | Percentual de conversas que foram resolvidas 100% pela IA, sem necessidade de intervenção humana |
| **Primeiro Tempo de Resposta** | Tempo decorrido entre a primeira mensagem do cliente e a primeira resposta do sistema |
| **Heatmap / Mapa de Calor** | Visualização gráfica que mostra o volume de conversas por hora e dia da semana, usando cores para intensidade |
| **KPI** | Key Performance Indicator (Indicador-chave de performance) - métricas essenciais para avaliar sucesso |
| **Boxplot** | Gráfico estatístico que mostra a distribuição de dados (mediana, quartis, valores máximo e mínimo) |
| **QR Code** | Código de barras bidimensional usado para conectar o WhatsApp Web |
| **Badge** | Etiqueta visual (como "Ativo", "Manual", "E-commerce") que indica status ou categoria |

### Status e Estados

| Status | Descrição |
|--------|-----------|
| **Ativo** | Agente ou negócio em funcionamento normal |
| **Inativo** | Agente ou negócio desativado temporariamente |
| **Em Treinamento** | Agente sendo configurado ou testado |
| **Conectado** | WhatsApp vinculado e funcionando |
| **Desconectado** | WhatsApp precisa ser reconectado |
| **Conectando** | Processo de conexão em andamento |
| **Conversa Ativa** | Conversa em andamento |
| **Conversa Fechada** | Conversa finalizada |
| **Conversa Arquivada** | Conversa arquivada para histórico |

### Conceitos de Negócio

| Conceito | Explicação |
|----------|------------|
| **Tempo Economizado** | Cálculo de horas economizadas pela automação, considerando o tempo que seria gasto em atendimento manual (2min para primeira resposta + 5min para tratamento) |
| **SLA** | Service Level Agreement - tempo máximo acordado para primeira resposta |
| **ROI** | Return on Investment - retorno sobre investimento da automação |
| **Handover Rate** | Percentual de conversas que precisaram ser transferidas para atendente humano |

---

## PERGUNTAS FREQUENTES (FAQ)

### 1. Posso ter mais de uma funcionária IA?
**Sim!** Você pode criar quantas funcionárias quiser, cada uma com seu próprio número de WhatsApp.

### 2. Preciso ter um chip/número diferente para cada funcionária?
**Sim.** Cada funcionária IA precisa estar vinculada a um número de WhatsApp exclusivo.

### 3. A IA responde a mensagens de grupo?
Por padrão, o sistema filtra mensagens de grupo. Verifique as configurações do seu agente.

### 4. O que acontece se eu desconectar o WhatsApp?
O agente para de funcionar. Os clientes não receberão respostas até você reconectar.

### 5. Posso editar as respostas da IA?
No momento, você pode assumir o atendimento manualmente. Personalização avançada depende da configuração do agente.

### 6. As conversas antigas são salvas?
**Sim.** Use o botão "Sincronizar Histórico" no card da funcionária para importar mensagens antigas.

### 7. Posso exportar os dados/relatórios?
Atualmente, os dados são visualizados no Dashboard. Recursos de exportação podem ser adicionados futuramente.

### 8. Como sei se a IA está funcionando bem?
Monitore a **Taxa de Automação** no Dashboard. Acima de 70-80% é considerado bom desempenho.

---

## SUPORTE E CONTATO

Em caso de dúvidas, problemas técnicos ou sugestões, entre em contato através dos canais oficiais de suporte:

- 📧 **Email:** suporte@legadoassessoria.com
- 💬 **WhatsApp:** Contate o administrador do sistema
- 📚 **Documentação:** Consulte este manual

---

## INFORMAÇÕES DO DOCUMENTO

- **Título:** Manual do Usuário - Legado AI
- **Versão:** 1.0
- **Data de Criação:** Novembro/2025
- **Última Atualização:** Novembro/2025
- **Público-alvo:** Usuários finais (clientes)
- **Exclusões:** Funcionalidades de Super Admin não estão cobertas neste manual

---

**© 2025 Legado AI - Todos os direitos reservados**
