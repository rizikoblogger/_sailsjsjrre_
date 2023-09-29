# sailsjsjrre

Uma aplicação [Sails v1](https://sailsjs.com)

### Atalhos

+ [Documentação do Framework Sails](https://sailsjs.com/get-started)
+ [Notas da versão & atualizações](https://sailsjs.com/documentation/upgrading)
+ [Dicas para Lançamento em ambiente de produção](https://sailsjs.com/documentation/concepts/deployment)
+ [Opções de Suporte por Comunidades](https://sailsjs.com/support)
+ [Opções de Suporte Profissional / Corporativo](https://sailsjs.com/enterprise)
+ [Documentação, Dicas e Suporte em Português](https://www.sailsjs.tec.br/index.html)

### Informações desta versão

Este aplicativo foi gerado originalmente em 29 de setembro de 2023, às 13:46:08 GMT-0300 (Horário Padrão de Brasília)
utilizando o Sails v1.5.8, npm 8.x e Node 16.x em ambiente Windows 10.

<!-- Internamente, Sails utilizou o [`sails-generate@2.0.8`](https://github.com/balderdashy/sails-generate/tree/v2.0.8/lib/core-generators/new). -->


O modelo deste projeto é baseado em um aplicativo inicial expandido e fornecido
pelo [Time Central do Sails](https://sailsjs.com/about)
para facilitar a criação de recursos comuns, tais como autenticação, cadastro, verificação de e-mail e cobrança.
Para maiores informações, entre em contato com a equipe principal do
Sails [entre em contato](https://sailsjs.com/support) ou nosso time [RIZ | iko](https://www.riziko.com.br/contato)

## Informações do Protótipo

Este Protótipo tem por objeto servir de base de consulta e prova técnica do conteúdo apresentado no livro **"Javascript
Rápido, Robusto e Escalável - Uma abordagem prática do Sails.js 1.5.x"**,
Editora LUX São Paulo, 2024.

## Motivação:

O Sails, como ferramenta de desenvolvimento de sistemas digitais e de código aberto, facilita a criação de aplicativos
Web / Node.js personalizados e de nível empresarial. Cria aplicativos Node.js práticos e prontos para produção em
questão de semanas, não meses. Sails é um dos framework do tipo Modelo x Visão x Controle (MVC) mais populares para
Node.js e foi projetada para emular o padrão MVC como Ruby on Rails, mas com suporte para os requisitos de aplicativos
modernos: APIs orientadas a dados com uma arquitetura escalável e orientada a serviços.

## Abordagem Literária:

O livro conta a história de 3 personagens convivendo em uma empresa fictícia na qual João Sabido é o orientador de dois
estagiários e candidatos a uma vaga de “Programador JavaScript pleno” na Supersoftware LTDA. Os estagiários são Pedro
Brainiac e “você”, o Leitor do livro. O Leitor será exposto ao conteúdo e fará a absorção do conhecimento através de
técnicas de aprendizado por "gamificação", de acordo com o seguinte ciclo:

### Proposta de desafio tecnológico a resolver;

* Exposição do Resultados esperados do tópico;
* Orientações passadas pelo João Sabido aos estagiários quanto ao que se espera;
* Ações executadas pelo Pedro Brainiac;
* Resultado obtido pelo Pedro Brainiac;
* Perguntas dos Estagiários;
* Resposta da pergunta dada pelo Sabido, relatando como a tecnologia Sails.js foi capaz de produzir os resultados
  obtidos
* com a execução do desafio tecnológico resolvido;
* Ações executadas pelo Leitor;
* Resultado obtido pelo Leitor; e
* Pontuação obtida pelo Brainiac e pelo Leitor.

No final da leitura do livro, o leitor deverá somar todos os pontos obtidos e comparar com os pontos obtidos pelo Pedro
Brainiac. Se a pontuação do Leitor for maior do que a do outro estagiário, então “A vaga de emprego é dele!”.

Com o passo a passo, o leitor do livro será capaz de aprender a tecnologia de forma prática, completa, objetiva e
divertida.

### Exemplo de aplicação da abordagem:

> EXECUTAR A INSTALAÇÃO DO SAILS.JS

* Desafio: realizar a instalação da ferramenta Sails.js na estação de trabalho e identificar a versão instalada.
* Resultados Esperados: o estagiário deve ser capaz de realizar a instalação da ferramenta utilizando os comandos já
* existentes na plataforma JavaScript Node.js e identificar a versão instalada.
* Orientações do Supervisor: o estagiário poderá utilizar o comando [npm install sails -g] no terminal da estação de
* trabalho e, depois que a instalação for concluída, executar o comando [sails –version]
* Ação realizada pelo Pedro Brainiac: [npm i sails -g && sails –version]

> POSSO UTILIZAR OUTRAS VERSÕES DO SAILS.JS?

* Resposta do Supervisor:  sim, mas recomendo a versão 1.5.8, pois é a atual. Lembre-se que novas versões podem ser
  lançadas amanhã mesmo!

> RESULTADOS

* Resultado obtido por mim: [                                                                        ]
* Pontos obtidos por mim: [     ].
* Minha pontuação somada até agora é [     ]
* Resultado obtido pelo Pedro Brainiac: 1.5.8
* Pontos obtidos pelo Pedro Brainiac: 1
* A pontuação do outro estagiário está em: [     ]

### Desafio principal proposto:

Desenvolver o protótipo de um Sistema de Gerenciamento de Transporte (Transportation Management System - TMS) para o
cliente Transportador Logístico LTDA, contendo:

> Gestão da Frota (Dados do Veículo)

* Tipo: rodoviário, ferroviário, aéreo ou aquaviário
* Velocidade Média Carregado
* Velocidade Média Sem Carga
* Capacidade de Carga (ton)
* Consumo combustível carregado (Km/l)
* Consumo combustível sem carga
* Tipo combustível: diesel, gasolina, etanol, querosene ou carvão
* Custo Operacional (R$/h)
* Custo total Tripulante(s) (R$/h)
* Intervalo de Manutenção (Horas)

> Gestão da Rota

* Distâncias entre origem e destino (km);
* tipo de estrada (pavimentação e trânsito);
* topografia (rampa máxima e altitude);
* pesos máximos admitidos em pontes e viadutos;
* legislação de trânsito (federal, estadual, municipal).
* Cadastro da Tabela de Frete
* Emissão do Conhecimento de Transporte Eletrônico (CTE)
* Ordens / Coletas
* Manifesto de Carga
* hora e data do embarque;
* tipo de carga: pacote; pallet; maquinário; grão; líquido; líquido perigoso.
* metros cúbicos da carga (volume);
* temperatura da carga;
* prazo de validade
* quantidade e código de barra de cada pedido (ordem);
* data e hora de chegada planejada;
* descrição da carga,
* destino e data e hora de entrega de cada carga;
* localização da doca de descarga

### Sumário Proposto:

* Venha trabalhar conosco!
* Requisitos profissionais do candidato

* Executar a instalação do Sails.js
* Posso utilizar outras versões do Sails.js?
* Leia a Especificação do Protótipo “Sistema do Transportador (TMS)”
* Crie o primeiro protótipo
* O que aconteceu aqui?
* Execute seu protótipo pela primeira vez
* Que legal! Como o Sails.js funciona?

* Modifique a identidade visual do protótipo
* Posso personalizar o estilo das páginas?
* Modifique os termos em inglês para o português (i18n)
* E se eu desejar internacionalizar para o Espanhol também?

* Crie um repositório chamado Veículo para armazenar dados
* Onde foi criado o repositório?
* Introduza dados (FAKE) no “Cadastro”
* Como verificar os dados introduzidos?
* Crie a página “Lista Cadastro de Veículos” (EJS)
* Como o Sails fez isso?
* Crie um componente personalizado para mensagem de erro
* Quais componentes já estão prontos no Sails.js?
* Visualize os dados do “Veículo”
* Quais as operações eu posso realizar nos dados?
* Localize um único “Cadastro de Veículo” para edição
* Me explica como o Sails encontrou os dados?
* Crie uma ação POST para modificar os dados
* Qual a diferença entre action, action-2 e controller no routes.js?

* Crie a página “Editar Cadastro”
* Me explica melhor como o Sails.js torna isso mais fácil?
* Envie os dados modificados para o Repositório
* Cloud.js SDK! Como funciona?
* Envie cópia digital da apólice de seguro para o servidor de dados
* Posso enviar estes arquivos para uma pasta customizada?

* Crie a página “Precisa-se de Motorista”
* Sem senha não vejo o anúncio?!
* Receba os dados de geolocalização de um Veículo (API RESTFul)
* Como controlar o acesso de outros sistemas?
* Faça o protótipo acessar o sistema do Embarcador (API CLient)
* Então eu posso utilizar outras bibliotecas JavaScript?
* Conheça o recurso Blueprints do Sails.js
* Pergunta do estagiário: funcionou?

* Customize as variáveis locais
* Todos os outros desenvolvedores verão minhas senhas?
* Customize as variáveis corporativas
* Preciso colocar as senhas no Git?
* Customize para o ambiente de “produção”
* Como o Sails.js faz pra escolher qual configuração utilizará?
* Altere a tecnologia de banco de dados para MongoDB
* O que são e quais são os adaptadores de banco de dados?

* Produza uma versão final para distribuição
* Posso distribuir em qualquer plataforma de Sistema Operacional?
* Ative o sistema de envio de emails
* Posso modificar o provedor de email?

* Crie uma função para cálculo de autonomia do Veículo (Sails Helper)
* O que mais posso fazer com o Helpers do Sails.js?
* Utilize os recursos avançados do Sails.js
* Teste seus recursos usando o Sails.js Console
* O que mais posso fazer com o Console?
* Crie uma tela de Chat entre usuários
* Quais tecnologias devo utilizar para isso?

* Apresente ao cliente um protótipo que utilize Angular 2+ como frontend
* Posso utilizar o Vue 3 também?
* Apresente ao cliente um protótipo que utilize Vue como frontend.
* Pergunta do estagiário: funcionou?

* Afinal! Quem ficou com a vaga de desenvolvedor pleno?
* Resposta dos exercícios propostos.

## Evoluindo nos capítulos

Cada capítulo será finalizado com o Protótipo em um estágio de desenvolvimento e o capítulo seguinte conterá melhorias
ou adições em relação ao anterior.
**Desta forma**, o aluno poderá recuperar o código da versão anterior sempre que desejar recomeçar o aprendizado e/ou _
clonar_ todo o código da versão final.

- [Capítulo 1](https://github.com/rizikoblogger/_sailsjsjrre_/tree/feature/cap1) - Instalação do Sails;
- [Capítulo 2](https://github.com/rizikoblogger/_sailsjsjrre_/tree/feature/cap2) - Manipulação de _Layout_ e Localidade;
- [Capítulo 3](https://github.com/rizikoblogger/_sailsjsjrre_/tree/feature/cap3) - Leitura e carga de dados para teste;
- [Capítulo 4](https://github.com/rizikoblogger/_sailsjsjrre_/tree/feature/cap4) - Manipulação de Dados e arquivos;
- [Capítulo 5](https://github.com/rizikoblogger/_sailsjsjrre_/tree/feature/cap5) - Adição de novas funcionalidades;
- [Capítulo 6](https://github.com/rizikoblogger/_sailsjsjrre_/tree/feature/cap6) - Customização do Protótipo;
- [Capítulo 7](https://github.com/rizikoblogger/_sailsjsjrre_/tree/feature/cap7) - Publicando meu Protótipo / Produto de
  Software;
- [Capítulo 8](https://github.com/rizikoblogger/_sailsjsjrre_/tree/feature/cap8) - Recursos Avançados do Sails;
- Capítulo 9 - Separando o _frontend_ do _backend_
  com [Vue 3](https://github.com/rizikoblogger/_sailsjsjrre_/tree/feature/vue)
  ou [Angular 14+](https://github.com/rizikoblogger/_sailsjsjrre_/tree/feature/angular);
- [Capítulo 10](https://github.com/rizikoblogger/_sailsjsjrre_/tree/feature/final) - Versão Final;

_Observe que: a versão gerada pelo Sails Generator é dependente de plataforma, portanto, não há garantia de que a
simples cópia
deste código-fonte irá funcionar perfeitamente no seu computador. Recomenda-se criar um projeto com o
comando ````sails new meu-projeto````, executar o comando ``npm install`` e só então substituir os arquivos deste
protótipo sobre os originais._

# Bom Aprendizado!
