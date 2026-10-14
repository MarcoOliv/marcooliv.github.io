---
layout: default
title: Política de Privacidade — MarkFinance
---

# Política de Privacidade — MarkFinance

**Última atualização:** 14 de outubro de 2026

O **MarkFinance** é um aplicativo de controle financeiro pessoal desenvolvido por **Capucho Labs** ("nós", "nosso"). Esta Política de Privacidade descreve como coletamos, usamos, armazenamos e protegemos suas informações ao utilizar o aplicativo MarkFinance ("Aplicativo"), disponível para iOS, Android e macOS.

Ao utilizar o Aplicativo, você concorda com as práticas descritas nesta política.

---

## 1. Informações que Coletamos

### 1.1 Informações fornecidas por você

- **Dados de cadastro:** endereço de e-mail e senha ao criar uma conta.
- **Dados financeiros:** contas bancárias (nome, tipo, saldo inicial), cartões de crédito (nome, bandeira, limite, datas de fechamento/vencimento), transações (receitas, despesas, transferências), categorias, recorrências e orçamentos que você registra.
- **Sugestões:** título, descrição e nome do autor (opcional) ao enviar sugestões de funcionalidades.

### 1.2 Informações coletadas automaticamente

- **Métricas de uso (Firebase Analytics):** registramos eventos de uso anônimos quanto ao conteúdo — por exemplo, "criou uma conta", "fez um lançamento", "importou um extrato", "abriu o app hoje" —, além de informações do dispositivo (modelo, sistema operacional, versão do app). Os eventos **nunca** incluem nomes de contas ou categorias, descrições, valores ou qualquer texto digitado por você. Eles ficam ligados apenas a um código interno da sua conta (sem nome nem e-mail), para contarmos usuários ativos, entendermos onde o app fica difícil e oferecermos benefícios, como Premium de cortesia. Um resumo dessas contagens (dias em que o app foi aberto, quantas vezes cada evento ocorreu, plataforma, versão e situação da assinatura) fica guardado no nosso banco de dados. **Não usamos identificador de publicidade, não rastreamos você em outros apps ou sites e não vendemos esses dados.**
- **Dados de assinatura:** informações de compra processadas pela Apple App Store ou Google Play Store, gerenciadas pelo RevenueCat. Não temos acesso aos dados completos do seu cartão de crédito ou método de pagamento.

### 1.3 Informações que NÃO coletamos

- Localização geográfica
- Contatos do dispositivo
- Fotos, câmera ou microfone
- Dados de outros aplicativos
- Dados bancários reais (login, senha ou tokens de banco)
- Informações de saúde

---

## 2. Como Usamos suas Informações

Utilizamos suas informações para:

- Fornecer e manter o funcionamento do Aplicativo
- Sincronizar seus dados financeiros entre dispositivos (recurso Premium)
- Processar e gerenciar sua assinatura
- Fornecer assistência financeira via assistente de inteligência artificial (recurso Premium)
- Melhorar o Aplicativo com base em dados de uso agregados
- Gerenciar o sistema de sugestões da comunidade

---

## 3. Armazenamento e Segurança dos Dados

### 3.1 Armazenamento local

Seus dados financeiros, categorias e configurações são armazenados localmente no seu dispositivo usando SQLite. O Aplicativo funciona 100% offline.

### 3.2 Armazenamento na nuvem

Se você criar uma conta e possuir uma assinatura Premium, seus dados são sincronizados com o **Google Cloud Firestore** (serviço do Firebase/Google Cloud). Os servidores estão localizados nos Estados Unidos e seguem os padrões de segurança do Google Cloud Platform.

### 3.3 Autenticação

O gerenciamento de contas é feito pelo **Firebase Authentication**. Sua senha é criptografada e não temos acesso a ela em texto plano.

### 3.4 Pagamentos

As assinaturas são processadas diretamente pela **Apple App Store** ou **Google Play Store** e gerenciadas pelo **RevenueCat**. Não armazenamos dados de pagamento em nossos servidores.

### 3.5 Dados financeiros

Os dados financeiros que você registra no Aplicativo (contas, transações, cartões) são informações inseridas manualmente por você. O Aplicativo **não acessa** suas contas bancárias reais, não realiza transações financeiras e não se conecta a nenhuma instituição financeira.

---

## 4. Compartilhamento de Dados

Não vendemos, alugamos ou compartilhamos suas informações pessoais com terceiros, exceto:

- **Firebase (Google):** para autenticação, armazenamento na nuvem e analytics.
- **RevenueCat:** para gerenciamento de assinaturas.
- **Apple / Google:** para processamento de pagamentos nas respectivas lojas.
- **Provedor de IA escolhido por você:** para processamento de perguntas ao assistente de IA (veja seção 4.1 abaixo).

Todos os terceiros mencionados operam sob suas próprias políticas de privacidade e padrões de segurança.

### 4.1 Assistente de IA — Compartilhamento com o provedor de IA

O Aplicativo oferece um assistente financeiro de inteligência artificial chamado "Mark". O assistente funciona no modelo **"traga sua própria chave" (BYOK)**: você escolhe um provedor de IA de terceiros e fornece a sua própria chave de API. Os provedores suportados são **OpenAI (openai.com)**, **OpenRouter (openrouter.ai)**, **Anthropic (anthropic.com)** e **Google Gemini (ai.google.dev)**. A tela de consentimento dentro do Aplicativo identifica, pelo nome, o provedor que você selecionou antes de qualquer envio.

Ao utilizar esse recurso, os seguintes dados podem ser enviados ao provedor que você configurou:

- **Dados financeiros:** saldos de contas, valores de transações, nomes de categorias, datas de transações, recorrências e projeções financeiras — conforme suas configurações de privacidade no Aplicativo.
- **Descrições e notas:** textos de transações e observações pessoais — somente se você habilitar essas opções nas configurações de privacidade.
- **Mensagens da conversa:** suas perguntas e o histórico da conversa com o assistente.

**Controles do usuário:**
- O uso do assistente de IA requer seu **consentimento explícito** antes do primeiro uso, com o provedor selecionado identificado pelo nome.
- O assistente só funciona se você **configurar um provedor e a sua própria chave de API**. A chave é armazenada **apenas no seu aparelho** (armazenamento seguro do sistema operacional) e nunca é enviada aos nossos servidores.
- Você pode escolher **exatamente quais categorias de dados** são compartilhadas através das configurações de privacidade do Mark.
- Você pode **revogar o consentimento** a qualquer momento nas configurações, o que interrompe imediatamente o compartilhamento de dados.

**Retenção de dados pelo terceiro:**
- Cada provedor processa os dados conforme a **própria política de privacidade**. Consulte os termos do provedor que você escolher: [OpenAI](https://openai.com/policies/privacy-policy), [OpenRouter](https://openrouter.ai/privacy), [Anthropic](https://www.anthropic.com/legal/privacy), [Google](https://ai.google.dev/gemini-api/terms). Como você usa a sua própria chave, os dados são enviados diretamente ao provedor sob os termos que você aceitou ao obter a chave.

---

## 5. Seus Direitos

Você tem o direito de:

- **Acessar** seus dados a qualquer momento pelo Aplicativo.
- **Corrigir** seus dados editando suas contas, transações e categorias.
- **Excluir** seus dados removendo registros individuais ou utilizando a função "Apagar todos os dados" nas configurações.
- **Cancelar** sua assinatura a qualquer momento pelas configurações da loja (App Store ou Google Play).

Para solicitar a exclusão completa da sua conta e todos os dados associados, acesse a [página de exclusão de conta](delete-account) ou entre em contato pelo e-mail: **capucholabs@gmail.com**

---

## 6. Retenção de Dados

- **Dados locais:** permanecem no dispositivo até que você os exclua ou desinstale o Aplicativo.
- **Dados na nuvem:** permanecem armazenados enquanto sua conta existir. Ao solicitar a exclusão da conta, todos os dados serão removidos em até 30 dias.
- **Métricas de uso:** os eventos são retidos conforme as políticas do Firebase Analytics; o resumo de uso por conta é removido junto com a conta, quando você solicita a exclusão.

---

## 7. Menores de Idade

O MarkFinance não é direcionado a menores de 13 anos. Não coletamos intencionalmente dados de crianças menores de 13 anos. Se tomarmos conhecimento de que coletamos dados de uma criança menor de 13 anos, tomaremos medidas para excluí-los.

---

## 8. Alterações nesta Política

Podemos atualizar esta Política de Privacidade periodicamente. Notificaremos sobre alterações significativas por meio do Aplicativo ou por e-mail. A data de "última atualização" no topo indica quando a política foi revisada pela última vez.

---

## 9. Contato

Se você tiver dúvidas sobre esta Política de Privacidade, entre em contato:

- **E-mail:** capucholabs@gmail.com
- **Desenvolvedor:** Marco Capucho — Capucho Labs

---

*Esta política é válida a partir da data de sua última atualização.*
