# Política de Privacidade — Roleta Lúdica

**Versão da política:** 1.0  
**Última atualização:** 18 de julho de 2026

## 1. Apresentação

Esta Política de Privacidade descreve como o aplicativo **Roleta Lúdica** acessa, utiliza, armazena, protege e elimina dados relacionados aos seus usuários.

O Roleta Lúdica é um aplicativo independente destinado a consultar a coleção e o histórico de partidas do usuário na plataforma Ludopedia e, com base nessas informações, sugerir jogos que possam voltar à mesa.

Ao utilizar o aplicativo, o usuário pode autorizar o acesso aos dados de sua conta na Ludopedia por meio do sistema oficial de autenticação OAuth disponibilizado pela própria plataforma.

O Roleta Lúdica não solicita, recebe ou armazena a senha utilizada pelo usuário na Ludopedia.

## 2. Controlador e canal de privacidade

**Controlador dos dados:** Ícaro Maia Freire.

**Canal de Privacidade e Atendimento aos Titulares:**  
Maia Freire Sociedade Individual de Advocacia  
CNPJ nº 64.714.585/0001-94  
E-mail: [contato@maiafreireadvocacia.com.br](mailto:contato@maiafreireadvocacia.com.br)  
Localidade: Vitória da Conquista, Bahia, Brasil.

No cenário atual, não foi indicado encarregado pelo tratamento de dados pessoais. O canal acima está disponível para dúvidas, solicitações, reclamações e exercício dos direitos previstos na Lei Geral de Proteção de Dados Pessoais — LGPD.

## 3. Dados obtidos junto à Ludopedia

Após a autorização expressa do usuário no ambiente da Ludopedia, o aplicativo poderá consultar os seguintes dados:

### 3.1. Dados da coleção

- identificador dos jogos;
- nome dos jogos;
- imagens e capas;
- links para as páginas dos jogos;
- indicação de que o usuário possui determinado jogo;
- classificação como jogo-base ou expansão;
- quantidade mínima e máxima de jogadores;
- duração média informada para cada jogo.

### 3.2. Histórico de partidas

- jogos presentes no histórico;
- data das partidas;
- quantidade de partidas registradas;
- expansões associadas às partidas, quando informadas;
- data da última partida de cada jogo.

O Roleta Lúdica não consulta o nome civil, endereço, telefone, contatos, localização, câmera, microfone, arquivos pessoais ou dados financeiros do usuário.

O aplicativo também não acessa a senha da conta da Ludopedia.

## 4. Dados de autenticação

Durante o login, a Ludopedia fornece um código temporário de autorização. Esse código é encaminhado ao serviço de autenticação do Roleta Lúdica exclusivamente para ser trocado por um Access Token.

O código de autorização não é armazenado permanentemente.

O Access Token é utilizado exclusivamente para consultar, em nome do usuário, as rotas autorizadas da API da Ludopedia.

Quando necessário para a sincronização em segundo plano, o Access Token é armazenado temporariamente no aparelho de forma criptografada, com chave protegida pelo Android Keystore.

O token temporário é apagado após a conclusão, falha definitiva ou cancelamento da sincronização. Ele poderá permanecer armazenado enquanto houver uma tentativa automática de retomada da sincronização.

A autorização OAuth é um mecanismo técnico de acesso à conta da Ludopedia e não significa autorização para finalidades diferentes das descritas nesta política.

## 5. Finalidades do tratamento

Os dados são utilizados para:

1. autenticar o acesso autorizado pelo usuário;
2. obter a coleção cadastrada na Ludopedia;
3. obter o histórico de partidas;
4. identificar jogos nunca jogados;
5. identificar jogos que estão há mais tempo sem jogar;
6. identificar jogos com poucas partidas;
7. aplicar os filtros de quantidade de jogadores e duração;
8. apresentar informações, imagens e links dos jogos;
9. manter uma cópia local da coleção para carregamento mais rápido;
10. atualizar a coleção em segundo plano;
11. garantir segurança, estabilidade e prevenção de uso indevido;
12. atender solicitações relacionadas à privacidade e ao cumprimento de obrigações legais.

Os dados não são utilizados para publicidade comportamental, criação de perfil comercial, venda de informações ou envio de comunicações promocionais.

## 6. Bases legais

Conforme a situação concreta, o tratamento poderá ser realizado com fundamento:

- na execução das funcionalidades solicitadas pelo próprio usuário;
- na adoção de procedimentos necessários à prestação do serviço;
- no cumprimento de obrigações legais ou regulatórias;
- no legítimo interesse relacionado à segurança, prevenção de abuso e funcionamento do aplicativo, observados os direitos e as legítimas expectativas do titular.

O aplicativo utiliza somente os dados necessários para as funcionalidades informadas nesta política.

## 7. Armazenamento no aparelho

Os dados consolidados da coleção são armazenados localmente no aparelho em banco de dados interno do aplicativo.

Esse armazenamento permite:

- abrir a coleção sem repetir toda a sincronização;
- utilizar o aplicativo após a primeira sincronização;
- reduzir o número de consultas à Ludopedia;
- melhorar o desempenho;
- preservar as sugestões e informações essenciais dos jogos.

Também poderão ser armazenados localmente:

- o progresso da sincronização;
- informações técnicas necessárias ao WorkManager;
- o Access Token temporariamente criptografado durante uma sincronização ativa.

O banco local não é enviado integralmente ao controlador ou a servidores próprios do Roleta Lúdica.

## 8. Serviço de autenticação e infraestrutura

O Roleta Lúdica utiliza um serviço intermediário hospedado em infraestrutura da Cloudflare para realizar a troca segura do código de autorização pelo Access Token.

Esse serviço não foi programado para manter banco de dados de usuários nem para armazenar permanentemente códigos ou tokens.

A infraestrutura utilizada poderá processar dados técnicos necessários à transmissão, segurança e funcionamento do serviço, de acordo com suas próprias políticas e obrigações legais.

Em razão do funcionamento de serviços de nuvem e de distribuição de conteúdo, determinados dados técnicos poderão ser processados em infraestrutura localizada fora do Brasil, com adoção das medidas de segurança e salvaguardas aplicáveis.

## 9. Compartilhamento de dados

Os dados poderão transitar entre:

- o aparelho do usuário;
- a Ludopedia, para autenticação e consulta à API;
- o serviço intermediário de autenticação;
- provedores técnicos indispensáveis à transmissão e ao funcionamento seguro do serviço.

O Roleta Lúdica não vende, aluga ou comercializa dados pessoais.

O acesso aos dados também poderá ocorrer quando necessário para o cumprimento de obrigação legal, decisão judicial ou requisição válida de autoridade competente.

A Ludopedia é uma plataforma independente e possui seus próprios termos e práticas de privacidade. Alterações nos dados originais da conta ou do histórico devem ser realizadas diretamente na Ludopedia.

## 10. Retenção e eliminação

Os dados são mantidos pelos seguintes períodos:

- **código de autorização:** somente durante a troca pelo Access Token;
- **Access Token:** durante a sincronização e eventuais tentativas automáticas de retomada;
- **coleção e histórico consolidados:** até que os dados do aplicativo sejam apagados, o aplicativo seja desinstalado ou uma nova sincronização substitua as informações;
- **progresso da sincronização:** enquanto necessário para executar, acompanhar e concluir o trabalho em segundo plano.

Os dados armazenados localmente podem ser eliminados nas configurações do Android:

**Configurações → Aplicativos → Roleta Lúdica → Armazenamento → Limpar dados**

O aplicativo também disponibiliza a opção **“Apagar dados armazenados no aparelho”** em sua tela interna de Política de Privacidade. Essa função cancela eventual sincronização em andamento e elimina o cache local, o token temporário e os registros locais de sincronização.

A desinstalação do aplicativo também elimina os dados locais armazenados em seu espaço interno.

A exclusão dos dados locais do Roleta Lúdica não apaga a conta, a coleção ou o histórico mantidos pela Ludopedia.

## 11. Segurança

O Roleta Lúdica adota medidas destinadas a proteger os dados, incluindo:

- comunicação por conexões seguras;
- autenticação pelo fluxo oficial OAuth;
- ausência de armazenamento da senha da Ludopedia;
- criptografia temporária do Access Token;
- uso do Android Keystore;
- armazenamento da coleção no espaço interno do aplicativo;
- limitação do acesso aos dados necessários;
- exclusão do token ao término da sincronização;
- ausência de SDKs de publicidade ou rastreamento comportamental.

Apesar das medidas adotadas, nenhum sistema de informação é absolutamente imune a falhas, ataques ou indisponibilidades.

## 12. Direitos dos titulares

Nos termos da LGPD, o titular poderá solicitar, conforme aplicável:

- confirmação da existência de tratamento;
- acesso aos dados;
- correção de dados incompletos, inexatos ou desatualizados;
- anonimização, bloqueio ou eliminação de dados desnecessários ou tratados em desconformidade;
- informações sobre compartilhamentos;
- portabilidade, quando aplicável e regulamentada;
- eliminação dos dados tratados com fundamento em consentimento, ressalvadas as hipóteses legais de conservação;
- informação sobre a possibilidade de não fornecer consentimento e suas consequências;
- revogação do consentimento, quando essa for a base legal utilizada;
- oposição a tratamento realizado em desconformidade com a LGPD;
- peticionamento perante a Autoridade Nacional de Proteção de Dados.

As solicitações podem ser encaminhadas ao canal:

**contato@maiafreireadvocacia.com.br**

Para proteger o próprio titular, poderá ser necessária a confirmação de informações suficientes para verificar a legitimidade da solicitação.

Quando o pedido estiver relacionado a dados mantidos originalmente pela Ludopedia, o usuário poderá precisar apresentar a solicitação diretamente àquela plataforma.

## 13. Dados de crianças e adolescentes

O aplicativo não solicita deliberadamente idade, data de nascimento ou dados destinados a identificar crianças e adolescentes.

A utilização de uma conta da Ludopedia deve observar as regras, requisitos etários e responsabilidades estabelecidos pela própria plataforma e pelos responsáveis legais, quando aplicável.

## 14. Alterações desta política

Esta política poderá ser atualizada para refletir:

- novas funcionalidades;
- mudanças técnicas;
- alterações na forma de tratamento;
- novos fornecedores;
- exigências legais ou regulatórias;
- alterações nas políticas das lojas de aplicativos.

A data e a versão da política serão atualizadas sempre que houver modificação relevante.

## 15. Contato

Dúvidas ou solicitações relacionadas à privacidade podem ser encaminhadas para:

**Maia Freire Sociedade Individual de Advocacia**  
CNPJ nº 64.714.585/0001-94  
E-mail: [contato@maiafreireadvocacia.com.br](mailto:contato@maiafreireadvocacia.com.br)  
Vitória da Conquista, Bahia, Brasil.
