# Levantamento de Requisitos

### Entrevistas:

<details>
  <summary style="font-size: 1em; font-weight: bold">Resumo da reunião 01</summary>
    <br>
    <p><strong>Data da Reunião:</strong> </p>
    <p><strong>Horário:</strong> </p>
    <p><strong>Local:</strong> </p>
    <h2>Equipe:</h2>
    <ol>
        <li>Ruan</li>
        <li>Kelly</li>
        <li>João</li>
        <li>Jociel</li>
    </ol>
    <h2>Tópicos debatidos:</h2>
    <ol>
        <li>Nome do grupo</li>
        <li>Nome do projeto</li>
        <li>Ideias de nomes do grupo e do projeto</li>
    </ol>
    <h2>Ideias e Discussões:</h2>
    <h3>Nome do Projeto:</h3>
    <ul>
        <li>"Opus"</li>
    </ul>
    <p><strong>Decisão:</strong> </p>
    <h2>Próximos Passos:</h2>
    <ol>
        <li>Criação da logo do projeto</li>
        <li>Escolha da paleta de cores</li>
        <li>Criação da logo para o grupo (ainda indefinido)</li>
    </ol>
    <h2>Observações:</h2>
    <ul>
        <li>Participação ativa de todos os membros na discussão e votação.</li>
    </ul>
</details>


<a></a>

### Técnica de Elicitação de Requisitos:

A coleta dos requisitos foi realizada por meio de contato e pesquisa com os responsáveis pela administração do grupo de ofertas de emprego no WhatsApp. Os gráficos com os resultados da pesquisa estão anexados à documentação. Esse processo de contato com os requisitantes permitiu a construção das tabelas de requisitos apresentadas a seguir.

### Resumo dos Resultados da Pesquisa:

Os resultados coletados através da pesquisa aplicada com os requisitantes do projeto se mostraram positivas quanto a aceitação e usabilidade do website quando desenvolvido. Majoritariamente, as respostas e sugestões dos candidatos tendem a um website que atenderá boa parte dos que buscam novas oportunidades de entrar no mercado seja por meio de contratos do tipo integral, meio período ou estágios.

Embora os resultados de candidatos tenha sido positivo, as respostas de empregadores carecem de dados consistentes, apenas 1 resposta. Com isso, sugere-se a busca por mais respostas e sugestões deste nível de usuário para o website.

A seguir, um levantamento dos requisitos construído a partir dos diálogos e pesquisas realizadas:

### Requisitos Funcionais:

|Código |Identificação |Classificação |Ator |Objetivo|
|--------|--------------|--------------|--------|--------|
|[RF01] |Cadastro de Candidatos|Essencial |Candidato| O sistema web deverá permitir o cadastro de candidatos por meio de Nome Completo, Data de Nascimento, Email, Senha, Telefone, Endereço, Sobre, Experiências, Formações e Currículo.|
|[RF02] |Cadastro de Empregadores|Essencial |Empregador| O sistema web deverá permitir o cadastro de empregadores por meio de Nome da Empresa / Empregador, Data de Nascimento, Email, Telefone, Endereço, Sobre.|
|[RF03] |Login de Candidatos / Empregadores|Essencial |Candidato / Empregador| O sistema web deverá permitir o login dos candidatos e empregadores por meio de email e senha.|
|[RF04] |Recuperar Senha |Essencial |Candidato / Empregador| O sistema web deverá permitir que o Candidato e Empregador recuperem e redefinam a senha de seu cadastro através do e-mail.|
|[RF05] |Excluir Cadastro |Essencial |Candidato / Empregador| O sistema web deverá permitir que o Candidato e o empregador façam a exclusão de seu cadastro.|
|[RF06] |Edição de Cadastro |Essencial |Candidato / Empregador| O sistema web deverá permitir que o Candidato e o Empregador atualizem as informações de cadastro.|
|[RF07] |Perfil de Candidato |Essencial |Candidato| O sistema web deverá possuir uma rota com todas as informações cadastradas do Candidato.|
|[RF08] |Postar Vagas |Essencial |Empregador| O sistema web deverá permitir que o empregador faça a puclicação de novas vagas com as seguintes informações: Nome da vaga, Nome da empresa, Logo da empresa, Localização, Data de postagem, Tipo de contrato e Sobre a vaga.|
|[RF09] |Listagem de Vagas |Essencial |Sistema| O sistema web deverá possuir uma seção com as vagas disponiveis e destaques na seção inicial.|
|[RF10] |Buscar Vagas |Importante |Candidato| O sistema web deverá permitir a busca por vagas, pelo nome, localização ou categoria.|
|[RF11] |Notificar Vagas |Importante |Sistema| O sistema web deverá notificar o Candidato referente a novas vagas e sobre vagas em que o Candidato se candidatou.|




### Requisitos Não Funcionais:

|Código  |Identificação |Classificação |Ator |Objetivo|
|--------|--------------|--------------|--------|--------|
|[RNF01] |Usabilidade |Essencial |UX/UI Designer|O site deve ser projetado com foco na usabilidade, proporcionando uma experiência de usuário intuitiva e agradável seguindo sempre o guia de estilos. Deve ser fácil de navegar e de entender, com interfaces de usuário amigáveis, eficientes e responsivas|
|[RNF02] |Desempenho |Importante |Desenvolvedor |O site deve ser rápido para garantir que os usuários não fiquem esperando muito tempo para carregar as páginas.|
|[RNF03] |Segurança |Importante |Desenvolvedor |O site deve implementar medidas de segurança eficazes para proteger as informações dos usuários, incluindo dados pessoais e de pagamento. Isso inclui criptografia de dados, autenticação segura e proteção contra ameaças cibernéticas.|
|[RNF04] |Manutenibilidade |Importante |Desenvolvedor| O site deve ser de fácil manutenibilidade para facilitar a correção de bugs.|
|[RNF05] |Escalabilidade |Importante |Desenvolvedor|O site deve ser projetado com escalabilidade em mente, garantindo que possa lidar com um aumento no número de usuários e conteúdos sem comprometer o desempenho. A arquitetura do site deve ser robusta e flexível|
|[RNF06] |Atualizações Contínuas |Importante |Desenvolvedor|O site deve ser atualizada regularmente.|
|[RNF07] |Compatibilidade |Essencial |Desenvolvedor|O site deve ser compatível com diversos dispositivos.|
|[RNF08] |Disponibilidade |Essencial |Desenvolvedor|O site deve estar disponivel 24 hrs por dia.|
|[RNF09] |Conformidades com a legislação local |Essencial |Desenvolvedor|O site deve seguir a legislação do país em que se encontra.|