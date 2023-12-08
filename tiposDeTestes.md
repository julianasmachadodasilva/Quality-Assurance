# TESTE MANUAL 
Teste manual é presencial, ao clicar no aplicativo ou interagir com o software e as APIs com as ferramentas adequadas. Mas o teste manual tem um custo muito alto, já que requer alguém para configurar um ambiente e executar os testes por si mesmo e pode estar propenso a erros humanos, uma vez que o testador pode cometer erros ortográficos ou omitir etapas no script de teste.

# TESTE AUTOMATIZADO
Testes automatizados, por outro lado, são realizados por uma máquina que executa um script de teste escrito com antecedência. Esses testes podem variar muito em termos de complexidade, indo desde a verificação de um único método em uma classe à garantia de que realizar uma sequência de ações complexas na interface do usuário leva aos mesmos resultados. São muito mais robustos e confiáveis que testes automatizados. Porém, a qualidade dos testes automatizados depende da qualidade com que seus scripts de teste foram escritos. 

# TESTES DE UNIDADE
Testes de unidade são feitos em um nível muito baixo, próximo ao código-fonte do aplicativo. Eles consistem em testar métodos e funções individuais de classes, componentes ou módulos usados pelo software. Testes de unidade, em geral, têm custo baixo para automatizar e podem ser executados com rapidez por um servidor de integração contínua.

# TESTES DE INTEGRAÇÃO
Testes de integração verificam se diferentes módulos ou serviços usados pelo seu aplicativo funcionam bem juntos. Por exemplo, pode ser testar a interação com o banco de dados ou garantir que os microsserviços funcionem juntos conforme o esperado. A execução desses tipos de testes tem um custo maior, uma vez que exigem que várias partes do aplicativo estejam ativas e em execução.

# TESTES FUNCIONAIS
Os testes funcionais têm como foco os requisitos de negócios de uma aplicação. Eles só verificam a saída de uma ação e não verificam os estados intermediários do sistema ao executar essa ação.

Às vezes há uma confusão entre testes de integração e testes funcionais, uma vez que ambos exigem vários componentes para interagirem entre si. A diferença é que um teste de integração pode simplesmente verificar que você pode consultar o banco de dados, enquanto um teste funcional esperaria obter um valor específico do banco de dados conforme definido pelos requisitos do produto.

# TESTES DE PONTA A PONTA (E2E)
Teste de ponta a ponta replica o comportamento de um usuário com o software em um ambiente de aplicativo completo. Ele verifica se vários fluxos de usuário funcionam como o esperado e podem ser tão simples quanto carregar uma página da web ou fazer login ou cenários muito mais complexos verificando notificações por e-mail, pagamentos on-line etc.

Testes de ponta a ponta são muito úteis, mas têm um alto custo e podem ser difíceis de atualizar quando automatizados. Recomendamos ter alguns testes de ponta a ponta essenciais e contar mais com tipos de testes de nível inferior (testes de unidade e de integração) para poder identificar rapidamente alterações que causam falha.

# TESTES DE ACEITAÇÃO
Os testes de aceitação são testes formais executados para verificar se um sistema atende aos requisitos de negócios. Eles exigem que todo o aplicativo esteja ativo e em execução e foca em replicar os comportamentos do usuário. Porém, também pode ir mais além e medir o desempenho do sistema e rejeitar alterações se determinadas metas não forem cumpridas.

# TESTES DE DESEMPENHO
Os testes de desempenho avaliam o desempenho de um sistema sob uma carga de trabalho específica. Esses testes ajudam a medir a confiabilidade, a velocidade, a escalabilidade e a capacidade de resposta de um aplicativo. Por exemplo, o teste de desempenho pode observar tempos de resposta ao executar um grande número de solicitações, ou ver como o sistema se comporta com quantidade significativa de dados. Ele pode determinar se um aplicativo atende aos requisitos de desempenho, localizar gargalos, medir a estabilidade durante picos de tráfego e muito mais.

# TESTE DE FUMAÇA (SMOKE TEST)
Testes de sanidade são testes básicos que verificam a funcionalidade básica do aplicativo. Eles são feitos para terem execução rápida e sua meta é garantir que os principais recursos do seu sistema estejam funcionando conforme o esperado.

Os testes de sanidade podem ser úteis logo após um novo build ser feito para decidir se você pode ou não executar testes mais caros, ou logo após uma implementação para garantir que o aplicativo esteja sendo executado como deveria no ambiente recém-implementado.

# TESTE EXPLORATÓRIO
Quanto mais recursos e melhorias forem incluídos no seu código, mais você precisará testar para garantir que seu sistema funcione adequadamente. Então, para cada bug que você corrigir, é bom verificar para que não voltem em novas versões. Automação é crucial para tornar isso possível e escrever testes mais cedo ou mais tarde se tornará parte do seu fluxo de desenvolvimento.

Assim, a pergunta é: ainda vale a pena realizar teste manual? A resposta curta é sim e talvez seja melhor realizar testes exploratórios para descobrir erros não óbvios.

Uma sessão de testes exploratórios não deve exceder duas horas e precisa ter um escopo claro para ajudar os testadores a se concentrar em uma área específica do software. Depois que todos os testadores tiverem sido informados, várias ações devem ser tomadas para verificar como o sistema se comporta.

## Fonte: https://www.atlassian.com/br/continuous-delivery/software-testing/continuous-deployment