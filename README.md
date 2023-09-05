# Projetomaiscodesenac
1. Introdução 

A empresa MaisCode é uma empresa de desenvolvimento de sistemas focada na criação de soluções para web, empenhada em impulsionar marcas e potencializar empreendimento. Sua missão é simplificar o desenvolvimento de soluções tecnológicas, entregando qualidade, autonomia e liberdade para os clientes, sem depender de terceiros no futuro. Com a visão de se tornar uma das principais referências em tecnologia da informação, a MaisCode baseia-se em valores éticos, honestidade e comprometimento, promovendo soluções inovadoras para uma diversidade de clientes e parceiros. A empresa desenvolve sites responsivos e com layouts personalizados, oferecendo suporte e manutenção para garantir a presença online eficaz. Com profissionais capacitados e utilizando as principais linguagens de programação, a MaisCode utiliza estratégias em Otimização para Mecanismos de Busca (SEO) e ferramentas analíticas para tomar decisões embasadas em dados de navegação. Confie na MaisCode para impulsionar o sucesso no mundo digital.  

1.1 Propósito 

O objetivo do projeto MaisCode é a criação de um sistema Web para o registro de comissões de vendas de produtos pelos colaboradores da MaisCode, permitindo ao departamento financeiro uma apuração rápida de valores a serem pagos a título de comissão aos vendedores.  

1.2 Escopo do produto 

O projeto visa desenvolver um sistema dedicado ao registro de comissões de vendas de produtos realizadas pelos colaboradores da empresa. Essa solução permitirá ao departamento financeiro efetuar uma apuração ágil e precisa dos valores a serem pagos em forma de títulos aos colaboradores. Através dessa plataforma, será possível automatizar o processo de registro de vendas, garantindo maior eficiência operacional, redução de erros e uma transparência exemplar aos vendedores, que terão acesso fácil e detalhado às suas comissões e relatórios de vendas. Com este sistema, a empresa alcançará maior motivação em sua equipe de vendas, impulsionando o alcance de metas e a obtenção de resultados sólidos, contribuindo para o sucesso sustentável e o crescimento no mercado altamente competitivo.  

 

2. Definições, siglas e abreviaturas 

RF (Requisito Funcional): É uma especificação de uma função ou serviço que um sistema de software deve fornecer. Ele descreve o comportamento do sistema em termos de entradas, processamento e saídas. Um requisito funcional pode ser pensado como um recurso do produto que o usuário detecta. Ele define o que o sistema deve fazer para atender às necessidades ou expectativas do usuário.  

RN (Regras de Negócio): São regras lógicas que traduzem uma necessidade do negócio, permitindo que desenvolvimento, produto e negócio de uma empresa se alinhem com relação a estas necessidades, se guiem por elas e apliquem as regras da forma mais clara possível, fazendo com que o desenvolvimento e o crescimento do produto possam fluir da melhor forma. A partir do momento em que as regras estão entendidas é possível iniciar o design do software, de acordo com o cronograma previsto para a sua execução.  

RNF (Requisito Não Funcional): São os requisitos relacionados às propriedades não funcionais do sistema, como desempenho, usabilidade, confiabilidade, segurança, disponibilidade e manutenção. Eles especificam as restrições e condições sob as quais o sistema deve operar. Os requisitos não funcionais são aqueles que não interferem diretamente no desenvolvimento do sistema propriamente dito, mas estabelecem como o sistema se comportará em determinadas situações.  

SENAC (Serviço Nacional de Aprendizagem Comercial): É uma instituição brasileira de educação profissional aberta a toda a sociedade subordinada à Confederação Nacional do Comércio, com a missão de desenvolver pessoas e organizações para o mundo do trabalho no setor do comércio de bens, serviços e turismo. Ele foi criado em 1946 e está presente em mais de 1.800 municípios, de Norte a Sul do Brasil.  

2.1 Referências 

RF (Requisito Funcional): Fonte: Adaptado de "Engenharia de Software: Uma Abordagem Profissional" (Roger S. Pressman) 

RN (Regras de Negócio): Fonte: Adaptado de "Engenharia de Software: Uma Abordagem Profissional" (Roger S. Pressman) 

RNF (Requisito Não Funcional): Fonte: Adaptado de "Engenharia de Software: Uma Abordagem Profissional" (Roger S. Pressman) 

SENAC (Serviço Nacional de Aprendizagem Comercial): Fonte: Website oficial do SENAC Brasil (https://www.senac.br/) 

3. Requisitos 

Em 5 de julho de 2023, foi conduzida uma reunião designada como "Dia da Integração", contando com a participação do representante da empresa MaisCode. No decorrer dessa reunião, foram identificados e analisados os requisitos essenciais do sistema em questão. De acordo com os resultados obtidos na entrevista, constatou-se uma demanda premente por parte da empresa no desenvolvimento de um sistema que visasse otimizar e agilizar o processo de apuração dos valores destinados ao pagamento de comissões aos vendedores. 

3.1 Requisitos Funcionais 

RF01- Cadastro de Usuário: O perfil do administrador permite cadastrar e classificar os usuários do sistema, identificando se são administradores, vendedores ou membros do setor financeiro. 

RF02- Cadastro de Cliente: Administradores e vendedores registram no banco de dados todas as informações necessárias dos clientes envolvidos em vendas. 

RF03- Cadastro da Venda: Detalhamento completo das informações de vendas, incluindo detalhes do contrato, como valor total, número de parcelas, entre outros. 

RF04- Campo de Busca para Usuários: Uma aba de pesquisa permite que o administrador identifique outros usuários com base em critérios como data, CPF/CNPJ e nome. 

RF05- Edição de Cadastros (Apenas ADM): O administrador pode atualizar informações e modificar o status de cadastros. 

RF06- Visualização de Relatórios: Visão abrangente dos motivos de contato e comissões, com a capacidade de acessar relatórios. 

RF07- Campo de Busca para Vendas: Uma aba de busca ajuda a identificar vendas com base em critérios como data, vendedor e cliente. 

RF08- Cancelamento de Vendas: Habilidade de inativar uma venda é concedida ao administrador e financeiro. 

RF09- Campo de Busca para Cliente: Uma aba de busca permite identificar clientes com base em CPF/CNPJ, Nome, razão social e nome fantasia da empresa. 

RF10- Login: Usuários efetuam login no sistema utilizando suas credenciais. 

RF11- Logout: Usuários encerram o acesso ao sistema. 

RF12- Ajuste de Comissões e Glosa pelo ADM: O administrador pode modificar os valores das comissões e limites para desconto. 

RF13- Listagem de Vendas: Exibição de lista de vendas. 

RF14- Especificar Condição de Pagamento: Definição da forma de pagamento já cadastrada (à vista, parcelado sem entrada, parcelado com entrada). 

RF15- Informar Valor das Parcelas (Venda a Prazo): Quando a venda é a prazo sem entrada, é possível inserir o valor total da venda, a quantidade de parcelas acordada entre cliente e vendedor e o valor das parcelas. Quando a venda é a prazo com entrada, é possível inserir o valor total da venda, o valor de entrada, quantidade de parcelas acordada entre cliente e vendedor, e o valor das parcelas. 

RF16- Cálculo de Valor da Comissão e Glosa: O sistema realiza automaticamente o cálculo do valor da comissão e glosa. 

3.2 Requisitos Não Funcionais 

RNF01- Segurança: O sistema deve garantir a segurança das informações, incluindo proteção contra acessos não autorizados, autenticação adequada e criptografia dos dados sensíveis.  

RNF02- Confiabilidade: O sistema deve ser altamente confiável, minimizando falhas e erros. Deve possuir mecanismos de recuperação em caso de falhas, garantindo a integridade dos dados.  

RNF03- Escalabilidade: O sistema deve ser facilmente escalável para acomodar o crescimento futuro, tanto em termos de usuários quanto de volume de dados.  

RNF04- Manutenibilidade: O sistema deve ser projetado de forma a permitir uma manutenção fácil e rápida, com documentação clara e código bem estruturado.  

RNF05- Integração: O sistema deve ser capaz de se integrar com outros sistemas ou serviços de forma eficiente, facilitando a troca de informações entre eles.  

RNF06- Localização e Internacionalização: O sistema deve suportar diferentes idiomas, formatos de data, moedas e outros aspectos relacionados à localização e internacionalização.  

RNF07- Monitoramento: O sistema deve ter recursos de monitoramento para acompanhar o desempenho, uso e disponibilidade, permitindo uma análise detalhada da sua operação.  

RNF08- Permissão de exportação de dados: O sistema deve permitir que os usuários com permissões adequadas possam exportar os dados armazenados no sistema para outros formatos, por exemplo, XLS ou PDF.  

RNF09- Interface simples e responsiva: A interface do sistema deve ser projetada de forma simples e intuitiva, facilitando o uso e a navegação para os usuários e responsiva para permitir um bom manuseio em diferentes dispositivos.  

RNF10- Sem exclusão de dados: O sistema deve ser projetado de forma a evitar a exclusão acidental ou não autorizada de dados importantes.  

RNF11- Portabilidade: O sistema deve ser desenvolvido de maneira que possa ser facilmente portado para diferentes ambientes, plataformas ou sistemas operacionais.  

RNF12- Disponibilidade de dados de forma atemporal: O sistema deve garantir que os dados estejam disponíveis sempre que necessário, sem restrições de horário ou dias da semana.  

RNF13- Proteção de dados: O sistema deve implementar medidas de segurança robustas para proteger os dados armazenados contra acesso não autorizado, roubo, perda ou alteração indevida.  

RNF14- Sistema orientado por permissões: O sistema deve ser projetado com base em um modelo de permissões, garantindo que cada usuário tenha acesso somente às funcionalidades e dados permitidos para o seu perfil. 

 

3.3 Regra de Negócio 

 

RN01- Apenas usuários autenticados e autorizados podem acessar o sistema.  

RN02- Não será permitida a exclusão de dados do sistema.  

RN03- Para o cadastro da venda deverão ser informados: Número do contrato (código alfanumérico),  tipo de contrato (se é um contrato de continuidade ou pontual), valor global, comissão e glosa, forma de pagamento (se será a vista, parcelado, se terá entrada), condição de pagamento (preencher data e valor da parcela), tipagem para primeira parcela (entrada ou não), data de início do contrato, validade(data de encerramento do contrato), contato cliente responsável pelo contrato (preferencialmente e-mail ou celular), CPF/CNPJ, nome do cliente, campo de descrição do objeto da venda e contato da venda (nome, telefone e e-mail). 

RN04- Ao cadastrar uma venda a prazo com entrada, o sistema deve permitir a informação do valor da entrada, quantidade de parcelas e do valor de cada parcela com base no valor total da venda.  

RN05- Apenas o administrador tem permissão para editar os cadastros de usuários e atualizar informações como nome, senha e perfil de acesso.   

RN06- O sistema deve permitir o cadastro de usuários com diferentes perfis, incluindo administrador, vendedor e financeiro. 

RN07- Para o cadastro do vendedor e financeiro deverão ser informados: nome, e-mail (de preferência corporativo), senha e CPF/CNPJ. 

RN08- O sistema deve garantir que cada usuário tenha acesso apenas às funcionalidades e dados permitidos para o seu perfil, de acordo com as permissões estabelecidas.  

RN09- Os usuários devem fornecer credenciais válidas (e-mail corporativo e senha) para efetuar o login no sistema.  

RN10- O administrador pode ativar ou desativar contas de usuários, controlando seu acesso ao sistema.  

RN11- Caso um usuário esqueça sua senha, ele deve entrar em contato com o administrador para realizar a troca de senha.  

RN12- Vendedores e administradores podem cadastrar informações detalhadas sobre uma venda, incluindo dados do cliente, produtos/serviços vendidos, valor da venda e forma de pagamento.  

RN13- Apenas o administrador e financeiro poderá fazer a inativação da venda.   

RN14- O sistema deve calcular automaticamente a comissão e glosa do vendedor com base nas regras estabelecidas para cada tipo de venda.  

RN15- O sistema deve permitir que vendedores e financeiros visualizem uma lista de todas as vendas registradas, incluindo detalhes como data da venda, cliente, valor total, comissão gerada e a sua glosa.  

RN16- O sistema deve permitir a especificação da condição de pagamento para cada venda, incluindo opções como à vista, parcelado, com entrada ou sem. 

RN17- Ao cadastrar uma venda a prazo sem entrada, o sistema deve abrir campos para informar o valor de cada parcela de forma personalizada.  

RN18- A interface do sistema deve ser projetada de forma simples e intuitiva, facilitando o uso e a navegação para os usuários.  

RN19- Caso uma venda seja cancelada, o sistema deve manter um registro do motivo do cancelamento para fins de auditoria.  

RN20- O sistema deve permitir a busca e a listagem de informações relevantes, como vendas, vendedores, clientes, relatórios, facilitando a análise de dados.   
