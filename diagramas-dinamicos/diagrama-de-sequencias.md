# Diagramas de Sequência para o Médico
## DS Médico (adicionarHorarioDisponivel)
Neste diagrama de sequência o ator médico inicia o fluxo solicitando ao sistema a adição de um horário, colocando ou enviando como parâmetro os dados de Data e Hora, após isso, o sistema entra no processo de tratar as condições: 1 - Horário livre de conflito: onde o horário está livre e o sistema grava os dados informados pelo ator. 2 - Horário em conflito: o sistema informa ao ator que o horário não está disponível.

![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/imagens/diagramas-de-sequ%C3%AAncia/DS%20M%C3%A9dico%20(cancelarConsulta).jpg?raw=true)

## DS Médico (cancelarConsulta)
O ator solicita o cancelamento passando como parâmetro o motivo do cancelamento, após isso, o sistema irá verificar no banco de dados a consulta e então valida o cancelamento e exibe uma mensagem de sucesso ao ator.

![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/imagens/diagramas-de-sequ%C3%AAncia/DS%20M%C3%A9dico%20(cancelarConsulta).jpg?raw=true)

## DS Médico (remarcarConsulta)
o ator médico inicia o fluxo solicitando ao sistema a remarcação de consulta, colocando ou enviando como parâmetro os dados de novaData e novaHora, após isso, o sistema entra no processo de verificar a disponibilidade da nova data e novo horário: 1 - Horário livre de conflito: onde o horário está livre e o sistema grava os dados informados pelo ator. 2 - Horário em conflito: o sistema informa ao ator que o horário não está disponível.

![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/imagens/diagramas-de-sequ%C3%AAncia/DS%20M%C3%A9dico%20(remarcarConsulta).jpg?raw=true)

## DS Médico (removerHorarioDisponivel)
O ator solicita a remoção de horário passando como parâmetro o motivo da remoção, após isso, o sistema irá verificar no banco de dados o horário e então valida a remoção e exibe uma mensagem de sucesso ao ator.

![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/imagens/diagramas-de-sequ%C3%AAncia/DS%20M%C3%A9dico%20(removerHorarioDisponivel).jpg?raw=true)

## DS Médico (visualizarConsultas)
O ator médico solicita a visualização de consultas agendadas ao sistema e ele retorna uma lista das consultas, após isso, o ator pode selecionar uma consulta para visualizar seus detalhes, o sistema solicita ao banco de dados esses detalhes que retorna os dados e o sistema exibe ao ator.

![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/imagens/diagramas-de-sequ%C3%AAncia/DS%20M%C3%A9dico%20(visualizarConsultas).jpg?raw=true)

## DS Médico (visualizarProntuario)
o ator médico inicia o fluxo solicitando ao sistema a visualização do prontuário, colocando ou enviando como parâmetro os dados do paciente, após isso, o sistema entra no processo de verificar o prontuário no banco de dados: 1 - prontuário encontrado: onde o sistema exibe o prontuário ao ator. 2 - prontuário não encontrado: o sistema informa ao ator através de uma mensagem que o prontuário não foi encontrado.

![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/imagens/diagramas-de-sequ%C3%AAncia/DS%20M%C3%A9dico%20(visualizarProntuario).jpg?raw=true)

# Diagrama de Sequência para o Paciente
## DS Paciente (cancelarConsulta)
Esse diagrama mostra como será feita a solicitação de cancelamento pelo ator paciente.

![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/imagens/diagramas-de-sequ%C3%AAncia/DS%20Paciente%20(cancelarConsulta).jpg?raw=true)

## DS Paciente (marcarConsulta)
Esse diagrama mostra como o ator paciente irá marcar uma consulta dentro do aplicativo.

![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/imagens/diagramas-de-sequ%C3%AAncia/DS%20Paciente%20(marcarConsulta).jpg?raw=true)

## DS Paciente (remarcarConsulta)
Esse diagrama mostra como o ator paciente irá remarcar uma consulta caso seja necessário.

![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/imagens/diagramas-de-sequ%C3%AAncia/DS%20Paciente%20(remarcarConsulta).jpg?raw=true)

## DS Paciente (visualizarConsultas)
Esse diagrama mostra como o ator paciente poderá visualizar as suas consultas marcadas.

![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/imagens/diagramas-de-sequ%C3%AAncia/DS%20Paciente%20(visualizarConsultas).jpg?raw=true)

## DS Paciente (visualizarFilaAtendimento)
Esse digrama mostra como o ator paciente poderá visualizar a fila de atendimento para saber quando será a sua vez de ser atendido.

![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/imagens/diagramas-de-sequ%C3%AAncia/DS%20Paciente%20(visualizarFilaAtendimento).jpg?raw=true)

## DS Paciente (visualizarProntuário)
Esse diagrama mostra como o ator paciente conseguirá visualizar o seu prontuário médico.

![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/imagens/diagramas-de-sequ%C3%AAncia/DS%20Paciente%20(visualizarProntu%C3%A1rio).jpg?raw=true)
