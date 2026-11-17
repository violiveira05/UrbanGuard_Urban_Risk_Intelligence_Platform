UrbanGuard | Urban Risk Intelligence Platform
Global Solution 2026.2 · FIAP · Engenharia de Software
Protótipo acadêmico de uma plataforma de monitoramento e análise de riscos urbanos. As ocorrências e integrações demonstradas são simuladas; a solução não constitui um serviço oficial de alertas de emergência.

Sobre o projeto
O UrbanGuard foi concebido para concentrar informações sobre riscos cotidianos nas cidades, como alagamentos, ilhas de calor e interrupções de energia, água e transporte. A proposta é apoiar moradores e agentes locais com visualização de ocorrências, priorização de alertas e transparência quanto à origem e à confiabilidade dos dados.

O projeto foi desenvolvido para o desafio CitizenTech da Global Solution 2026.2, na disciplina de Engenharia de Software da FIAP.
Acesso ao projeto
- Protótipo navegável (Figma Make): UrbanGuard Risk Platform
- Documentação e diagramas (Miro): Quadro UrbanGuard
- Vídeo demonstrativo: link a adicionar após a gravação (duração máxima: 3 minutos).
Para consultar os materiais, abra os links acima no navegador. O acesso depende das permissões de compartilhamento definidas no Figma e no Miro.

Funcionalidades representadas
O protótipo foi estruturado para apresentar os seguintes módulos:
1. Login: tela de acesso demonstrativa.
2. Dashboard: visão geral de alertas ativos, áreas críticas, interrupções e confiabilidade dos dados.
3. Mapa de riscos: localização e identificação visual de ocorrências.
4. Central de alertas: consulta de eventos com categoria, gravidade e estado.
5. Detalhes do alerta: descrição, localização, origem da informação e nível de confiança.
6. Notificações: comunicação de novos alertas e atualizações.
7. Registro comunitário: envio simulado de ocorrências por moradores.
8. Origem e confiabilidade: explicação das fontes e dos critérios de classificação.
9. Histórico: acompanhamento da evolução dos registros e eventos.
10. Configurações: preferências de monitoramento, notificações e privacidade.
Fluxo principal de uma ocorrência
Registro recebido
       ↓
    Reportado
       ↓
  Em validação
    ↙       ↘
Descartado  Confirmado
                 ↓
       [alerta necessário?]
           ↙         ↘
     Alerta emitido   Em monitoramento
           ↓                ↑
     Em monitoramento ──────┘
           ↓
        Encerrado
Uma ocorrência comunitária não deve virar alerta público automaticamente. A confirmação e a emissão de alertas fazem parte do fluxo de validação previsto nas regras de negócio. No protótipo, essas etapas são demonstradas com dados e interações simulados.
Regras de classificação propostas
Nível de risco
Pontuação de 0 a 100:

Risco = 0,40 × Severidade + 0,35 × População afetada + 0,25 × Urgência
Pontuação	Classificação
0–24	Baixo
25–49	Moderado
50–74	Alto
75–100	Crítico


Nível de confiança
Pontuação de 0 a 100:

Confiança = 0,40 × Confiabilidade da fonte + 0,30 × Atualidade + 0,30 × Corroboração
Pontuação	Classificação
0–39	Baixa
40–69	Média
70–100	Alta


Essas fórmulas são critérios propostos para fins acadêmicos, não normas oficiais de órgãos de emergência. A interface pode utilizar valores fictícios para demonstrá-las.
Documentação técnica
A documentação do projeto, organizada no Miro, contempla:
- Apresentação, problema, objetivos e solução proposta;
- Público-alvo e três personas;
- 15 requisitos funcionais identificados (RF01 a RF15);
- 10 requisitos não funcionais classificados conforme a ISO/IEC 25010;
- 10 regras de negócio (RN01 a RN10);
- Diagrama UML de Sequência para o recebimento, validação e emissão de alertas;
- Diagrama UML de Estados para o ciclo de vida de uma ocorrência;
- Arquitetura em camadas, incluindo apresentação, aplicação/negócio, dados, fontes externas e segurança/LGPD.
A arquitetura documentada descreve uma proposta de implementação futura. Ela não significa que servidores, bancos de dados ou integrações externas estejam ativos no protótipo atual.
Ferramentas utilizadas
Ferramenta	Uso
Figma Make	Criação e navegação pelo protótipo de interface
Miro	Documentação técnica e diagramas de modelagem
UML	Modelagem de sequência e estados


Como visualizar e demonstrar
1. Acesse o link do Figma Make na seção Acesso ao projeto.
2. Abra a visualização do protótipo e comece pela tela de login.
3. Navegue pelo Dashboard, Mapa de Riscos e Central de Alertas.
4. Abra um alerta e consulte origem, nível de confiança e informações do evento.
5. Explore Notificações e Registro Comunitário.
6. Demonstre, quando disponível no protótipo, o envio de uma ocorrência e seu acompanhamento no Histórico.
7. Consulte o Miro para visualizar requisitos, regras de negócio, diagramas UML e arquitetura.
Não há instalação local obrigatória nem instruções de execução de backend, pois a entrega principal é um protótipo navegável hospedado no Figma Make.
Segurança e privacidade
O projeto considera, em nível de requisitos e proposta arquitetural, controles de acesso, minimização de dados pessoais, segurança da informação, rastreabilidade e princípios da Lei Geral de Proteção de Dados Pessoais (LGPD). Não foi realizada validação de segurança de um sistema de produção.
Equipe
Integrante	RM
Victor Augusto Ribeiro de Oliveira	558338
Pedro Henrique Garcia	558867


Instituição: FIAP
Curso: Engenharia da Computação
Turma: 3ECR
Disciplina: Engenharia de Software
Semestre: 2026.2
