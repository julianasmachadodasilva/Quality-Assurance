# PIRÂMMIDE DE TESTES

Uma pirâmide de testes visa demonstrar os principais testes realizados na criação de um projeto, juntamente com seus níveis de dificuldade e importância.

No setor de tecnologia estes são três dos principais testes a serem realizados:

## Base - Testes de Unidades ou Unitário

São testes feitos pelos próprios desenvolvedores em pequenos pedaços de códigos ou na menor parte testável de uma aplicação. São realizados em grande escala em todo o processo de criação de forma simples, pequena e rápida, sendo considerado um dos mais importantes nas etapas de desenvolvimento.

## Meio - Teste de integração

Com as diferentes partes do código completas, as equipes responsáveis fazem o teste de integração juntando as diferentes unidades (interfaces, APIs, Banco de Dados) para localizar possíveis falhas em sua interação. Por isso se torna mais complexo do que um teste unitário e demanda mais tempo para localizar e corrigir eventuais bugs.

## Topo - Teste Operacional, de Sistemas, Ponta a Ponta ou End to End

É realizada uma análise em todo o sistema para ter certeza de sua operacionalidade. Este teste simula o comportamento do usuário final em nossa aplicação e determina se tudo está funcionando como deveria (utiliza muito do BDD, que será explicado mais abaixo). Por fim é um teste muito mais complexos e criterioso, demandando ainda mais tempo para finalmente os software ser liberado para uso.

## Testes complementares

Apesar de serem os mais importantes, não são os únicos, existem mais uma grande quantidade de testes que podem ser realizados. Deixarei abaixo um resumo dos destacados na mentoria:

- Teste de Regressão - Ao inserir novas funcionalidades em seu código, este teste é feito para garantir que não surgiram defeitos em unidades que já funcionavam antes das novas atualizações.
- Teste Funcional - Valida se cada uma das funcionalidades estão funcionando conforme o esperado.
- Teste de Interface - Verifica a funcionalidade da interface dos usuários.
- Teste de configuração e segurança - Analisa para ter certeza que as configurações do software funcionem em diferentes celulares (mais antigos, de diferentes marcas e modelos) ou navegadores (Chrome, Edge, Firefox) de forma segura.
- Teste de Performace, Carga e Stress - Testes que determina o quão bem o software processa os dados sua capacidade de resposa e estabilidade, quantos acessos o software aguenta ao mesmo tempo sem sobrecarregar e ao atingir ou superar esse limite, como o software se comporta.
- Teste de instalação/Desinstalação - Teste para verificar se a instalação e desinstalação estão operacionais.

# TDD (Test Driven Development) - Desenvolvimento Orientado a Testes

É um processo ao qual você escreve o teste para falhar seu código antes de escrever um que passe nesse teste. Assim que o código estiver operacional, é realizado sua limpeza e melhoria. Ele visa principalmente a qualidade do software em produção.

# BDD (Behavior Driven Development) - Desenvolvimento Orientado a Comportamento

É um processo de desenvolvimento ágil que visa a colaboração entre os desenvolvedores, os setores de qualidade e os clientes de determinado software, para que haja mais comunicação entre as partes.

Pode ser realizada como um complemento ao TDD, e seu intuito é melhorar a qualidade do software. Entre seus pontos positivos podemos frisar:

- No final o software está dentro da expectativa do cliente, deixando-o satisfeito.
- Melhora a comunicação do time de desenvolvimento e de outros setores.
- Torna a documentação do projeto mais dinâmica.

Uma das boas práticas do seu fluxo de teste pode ser definido em: Dado, Quando, Então.

Exemplo:
Dado que tenho um botão de retornar para a página principal, 
Quando eu clico no botão
Então ele me direciona para a página principal.

## Fonte: https://www.dio.me/articles/piramide-de-testes-tdd-e-bdd-os-principais-testes-realizados-em-projetos-de-desenvolvimento