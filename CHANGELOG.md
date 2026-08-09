# Histórico de Alterações - AnalystPro

## [Versão V1.7.0] - 2026-08-09
- *Adicionado:* Recuperação de senha por e-mail com código de 6 dígitos, via EmailJS (sem backend), substituindo a caixa de confirmação genérica do navegador.
- *Adicionado:* Painel de Segurança em Configurações — trocar senha (com validação da senha atual), configurar e-mail de recuperação e credenciais do EmailJS.
- *Corrigido:* Atributos do campo de senha ajustados para reduzir a interferência de sugestões de autopreenchimento/gerenciador de senhas do navegador.

## [Versão V1.6.0] - 2026-08-08
- *Corrigido:* Bug crítico de persistência — a carteira de ativos agora é salva no dispositivo (localStorage); antes existia apenas na tela e se perdia ao recarregar a página.
- *Adicionado:* Nova aba Dashboard reunindo o Resumo Geral, o Raio-X Didático e o Simulador de Renda Passiva, que antes ficavam fixos em cima de todas as outras abas.
- *Corrigido:* Formato da URL usada no proxy CORS (corsproxy.io) para consulta à API Brapi, que estava quebrando as requisições do Gráfico Avançado de Cotação.
- *Adicionado:* Aviso visual explícito quando o Gráfico Avançado de Cotação está exibindo dados simulados (ausência de token válido ou API indisponível).
- *Corrigido:* Cálculo do Preço Justo (fórmula de Graham), que podia gerar "NaN" com EPS/VPA negativos; valores estimados agora são sinalizados com "*".
- *Adicionado:* Gráfico interativo de Proventos na aba Dividendos, com navegação Ano → Mês → Ativos que pagaram no período.

## [Versão V1.5.9] - 2026-08-08
- *Adicionado:* Remoção definitiva do banner global fixo de notificação de versão que se repetia de forma indesejada em todas as abas internas.
- *Ajustes:* Abas de navegação otimizadas e limpas para garantir foco total nas funcionalidades de cada seção sem ruídos visuais.

## [Versão V1.5.8] - 2026-08-08
- *Adicionado:* Diretrizes operacionais permanentes embutidas para assegurar integridade de dados reais, arquivos sempre completos de ponta a ponta e sincronia de changelog.
- *Ajustes:* Atualização do modal de novidades e painel de avisos da Versão V1.5.8.

## [Versão V1.5.7] - 2026-08-08
- *Adicionado:* Raio-X Didático Detalhado da Carteira, discriminando o desempenho de preço das ações versus o retorno líquido real com dividendos.
- *Ajustes:* Ordenação cronológica rigorosa e crescente por data de pagamento no histórico e tabelas de proventos.

## [Versão V1.3.0] - 2026-08-06
- *Adicionado:* Gráfico interativo de histórico de proventos e dividendos com filtros personalizados por Ativo, Ano e Mês na aba de Análise.
- *Ajustes:* Otimização da aba de Análise & Gráficos mantendo a alocação setorial e métricas de saúde da carteira.

## [Versão V1.2.0] - 2026-08-05
- *Adicionado:* Indicador visual do número da versão no topo da tela de login e no cabeçalho do sistema.
- *Adicionado:* Sistema de verificação automática de atualização de versão.
- *Ajustes:* Melhorias no layout mobile e responsividade em dispositivos celulares.

## [Versão V1.1.0] - 2026-08-01
- *Adicionado:* Histórico detalhado de proventos e dividendos separados por ativos.
- *Adicionado:* Simulador de renda passiva e juros compostos a longo prazo.
- *Ajustes:* Integração completa com a API Brapi para cotações em tempo real.
