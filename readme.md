exibir a listagem de seus médicos separados por especialidade em seu site para que seus pacientes tenham acesso. Essa clínica utiliza o Feegow que possui toda a api necessária para isso.

- 1) A tela inicial deve ser um SELECT contendo a listagem de todas as especialidades que a clínica trabalha (método na documentação: GET /specialties/list).

- 2) Quando o usuário escolhe uma especialidade, é executado um AJAX para buscar os profissionais que possuem aquela especialidade e exibido em tela (método na documentação: GET /professional/list).

- 3) Quando o usuário clica em "AGENDAR", será exibido um formulário que o usuário irá preencher e clicar em "ENVIAR".