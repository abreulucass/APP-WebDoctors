# Consistência com o Backlog

## Histórias de Usúarios do Paciente

### 1. Como paciente Eu quero marcar consultas online Para que eu não precise sair de casa e ir a locais físicos me consultar.

#### Critérios de aceitação: 
- Deve ser disponibilizado um calendário para o paciente selecionar o dia da consulta a partir do botão de marcar consultas aparecendo outro botão de calendário com dias disponíveis.
- Deve ser disponibilizado ao paciente apenas horários e datas disponíveis. 
- Deve ser disponibilizado ao paciente um campo onde ele deve escrever o motivo prévio da consulta. 
- Deve ser fornecido ao usuário uma tela com todos os dados informados por ele, para que ele possa confirmar todas as informações.
- O paciente deve poder editar as informações caso estejam erradas antes de confirmar o agendamento da consulta.
- O paciente deve ser cadastrado e verificado na plataforma.

#### Regras de Negócio: 
- Todas as consultas online devem ser asseguradas através da Lei da Telemedicina (Lei nº 14.510) que estabelece os critérios para atendimento médico a distância.

![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_paciente/Agendamento%201.png?raw=true)
![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_paciente/Agendamento%202.png?raw=true)
![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_paciente/Agendamento%203.png?raw=true)
![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_paciente/Agendamento%204.png?raw=true)
![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_paciente/Agendamento%205.png?raw=true)


### 2. Como paciente Eu quero remarcar consultas Para evitar sair de casa. 

#### Critérios de aceitação: 
- O paciente deve ter acesso a opção de remarcar consulta através do botão na tela inicial de lista de consultas. 
- O paciente deve poder selecionar uma nova data e hora para a consulta. 
- O paciente deve confirmar a nova data e hora da consulta. 
- O sistema deve atualizar automaticamente a nova data e hora.
- O sistema deve confirmar ao paciente a remarcação da consulta através de uma mensagem na tela de confirmação
#### Regras de Negócio
- O paciente só poderá remarcar uma consulta com 24 horas de antecedência.

![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_paciente/Remarcar1.png?raw=true)
![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_paciente/Remarcar2.png?raw=true)
![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_paciente/Remarcar3.png?raw=true)

### 3. Como paciente Eu quero cancelar consultas Para evitar ir a locais físicos para fazer isso. 

#### Critérios de aceitação: 
- O paciente deve ter acesso a opção de cancelar consulta através do botão na tela inicial de lista de consultas.
- O sistema deverá solicitar ao paciente os motivos do cancelamento através de campo que ele poderá preencher escrevendo seus motivos.
- O paciente deve confirmar o cancelamento da consulta. 

#### Regras de Negócio: 
- As consultas canceladas deverão ser registradas no sistema com o 
motivo do cancelamento e com a data e a hora do cancelamento.
- O paciente só poderá cancelar uma consulta com 24 horas de
antecedência.
- O sistema deverá mostrar uma mensagem de alerta na tela caso o
paciente tente cancelar a consulta dentro de 24 horas antes da
consulta ser iniciada, impedindo ele de cancelar.

![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_paciente/Cancelar1.png?raw=true)
![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_paciente/Cancelar2.png?raw=true)
![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_paciente/Cancelar3.png?raw=true)

### 4. Como paciente Eu quero ver consultas marcadas Para que eu possa ter o controle das minhas consultas agendadas. 
#### Critérios de aceitação: 
- A partir da tela inicial do aplicativo o paciente deve ter acesso a lista de consultas apertando um botão que levará para a lista de consultas
marcadas. 
- O paciente deve visualizar todas as informações da consulta, como data, hora e o motivo da consulta. 
-  As consultas marcadas devem ser mostradas em ordem cronológica,
começando pelas consultas mais próximas agendadas em relação a
data. 
- O paciente deve ver o status da consulta, como cancelada, confirmada 
ou remarcada.

![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_paciente/ConsultasMarcadas.png?raw=true)

### 5. Como paciente Eu quero receber um lembrete de que uma consulta está próxima Para que eu não esqueça das consultas futuras.
#### Critérios de aceitação: 
- O paciente deve poder selecionar nas configurações se deseja ou não receber lembretes.
- O paciente deve poder selecionar nas configurações o intervalo de
recebimento dos lembretes.
- O paciente deve receber um lembrete 24 horas antes da consulta agendada e 1 hora antes da consulta agendada. 
- Os lembretes devem ser enviados por email e/ou notificação push, a depender da escolha do paciente. 
- No conteúdo do lembrete deve constar a data, hora, nome do médico e o motivo da consulta. 

![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_paciente/Lembrete1.png?raw=true)
![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_paciente/Lembrete2.png?raw=true)

### 6. Como paciente Eu quero enviar exames Para facilitar o acesso do médico aos meus exames. 
#### Critérios de aceitação: 
- O paciente deve poder enviar os exames necessários para cada
consulta ao entrar nos detalhes da consulta e clicar no botão de
“enviar arquivo”. 
- O paciente deve poder enviar seus arquivos de exames nos formatos de JPEG, PNG, PDF, DICOM a partir do próprio dispositivo.
- O paciente deve enviar arquivos (imagem, PDF) de no máximo 20 MB por arquivo. 
- O paciente deve ter uma prévia visualização dos arquivos a serem
enviados para a confirmação dos dados, podendo cancelar o envio e
refazer esse processo se achar necessário

#### Regras de negócio: 
- Os dados pessoais dos pacientes devem ser protegidos contra acesso não autorizado e em conformidade com a Lei Geral de Proteção de Dados Pessoais (nº 13.709/2018). 
- O médico deve ser notificado através de e-mail ou notificação push no 
momento em que o paciente confirmou o envio do exame.

![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_paciente/AnexarExame1.png?raw=true)
![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_paciente/AnexarExame2.png?raw=true)
![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_paciente/AnexarExame3.png?raw=true)
![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_paciente/AnexarExame4.png?raw=true)

### 7. Como paciente Eu quero ver meu prontuário Para ter acesso fácil as minhas informações médicas. 
#### Critérios de aceitação: 
- O paciente deve ter acesso ao prontuário a partir de um botão na
página inicial do aplicativo
- O prontuário deve incluir informações como histórico de consulta, diagnósticos, tratamentos, receitas médicas e resultados de exames. 
- O prontuário deve estar disponível aos médicos para cada consulta.

![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_paciente/ProtuarioMedico.png?raw=true)

### 9. Como paciente Eu quero ver fila de atendimento Para eu poder saber quanto tempo falta para eu ser atendido.
#### Critérios de aceitação: 
- O paciente deve ter acesso a opção de ver fila de atendimento a partir
do botão de “lista de consultas” que estará na tela inicial e ao entrar na
lista de consultas poderá ver a fila de atendimento para sua consulta
que estará prestes a começar. 
- O paciente deve poder ver sua posição atual em tempo real na fila de atendimento. 
- O paciente deve poder ver o número de pessoas que tem à sua frente na fila. 
- O paciente deve receber uma notificação quando sua vez estiver próxima.

![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_paciente/FilaAtendimento.png?raw=true)

-------------

## Histórias de Usuários do Médico

### 1. Como médico Eu quero gerenciar meus horários Para um melhor controle dos meus atendimentos. 
#### Critérios de aceitação: 
- O médico deve ter acesso a opção de gerenciar seus horários a partir da página principal do aplicativo. 
- O médico deve poder adicionar novos horários de atendimento especificando data e hora. 
- O médico deve poder modificar seus horários e datas de consultas. 
- O sistema deve permitir ao médico visualizar as consultas agendadas
por meio de uma lista ordenada da consulta mais próxima.
- O médico deve receber notificações de novas marcações, cancelamentos ou alterações de consultas. 
- O sistema deve alertar possíveis conflitos de horários ao editar um
horário de atendimento com um lembrete de alerta que aparecerá na
tela.
- O médico deve ser cadastrado e verificado na plataforma.
#### Regras de Negócio
- O médico deve poder visualizar detalhes de um paciente de uma
consulta específica (Ex: Nome, Idade, Exames já feitos e etc).

![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_medico/GerenciarHorario1.png?raw=true)
![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_medico/GerenciarHorario2.png?raw=true)
![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_medico/GerenciarHorario3.png?raw=true)
![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_medico/GerenciarHorario4.png?raw=true)
![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_medico/GerenciarHorario5.png?raw=true)
![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_medico/GerenciarHorario6.png?raw=true)
![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_medico/GerenciarHorario7.png?raw=true)

### 2. Como médico Eu quero gerenciar o histórico de consultas dos pacientes Para visualizar informações de consultas já realizadas.
#### Critérios de aceitação: 
- O médico deve ter acesso a opção de gerenciar o histórico de
consultas dos pacientes a partir de um botão na página principal do
aplicativo.
- O médico deve ter acesso a informação completa de uma consulta, como receitas médicas fornecidas, exames feitos, nome do paciente, data, hora e o motivo da consulta. 
- O médico deve poder buscar consultas através do nome do paciente ou intervalos de data e hora. 
- O médico deve poder filtrar a busca por consultas através do motivo da consulta.

![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_medico/HistoricodeConsultas1.png?raw=true)
![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_medico/HistoricodeConsultas2.png?raw=true)
![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_medico/HistoricodeConsultas3.png?raw=true)

### 3. Como médico Eu quero remarcar consultas Para facilitar o gerenciamento de consultas com pacientes. 
#### Critérios de aceitação: 
-  O médico deve poder remarcar consultas a partir do botão de
gerenciamento de horários na página inicial do aplicativo.
- O médico deve poder selecionar a consulta específica que deseja 
remarcar. 
- O médico deve poder atualizar a nova data e horário da consulta a
partir do gerenciamento de horários na página inicial do aplicativo. 
- O médico deve confirmar a nova data e hora da consulta. 
- O sistema deve notificar o paciente a partir da confirmação da
remarcação da consulta ao paciente por meio de notificação via email
e notificação push
- O médico deverá receber uma notificação por email ou push de 
confirmação da remarcação de consulta.
#### Regras de Negócio
- O médico só poderá remarcar uma consulta com 24 horas de
antecedência

![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_medico/RemarcarConsulta1.png?raw=true)
![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_medico/RemarcarConsulta2.png?raw=true)
![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_medico/RemarcarConsulta3.png?raw=true)
![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_medico/RemarcarConsulta4.png?raw=true)
![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_medico/RemarcarConsulta5.png?raw=true)

### 4. Como médico Eu quero cancelar consultas agendadas Para caso eu não possa atender.
#### Critérios de aceitação: 
- O médico deve poder cancelar consultas a partir do botão de
gerenciamento de horários na página inicial do aplicativo 
- O médico deve poder selecionar uma consulta específica para cancelamento. 
- O sistema deverá solicitar ao médico os motivos do cancelamento. 
- O sistema deverá solicitar uma confirmação do médico para o 
cancelamento. 
- O médico deverá receber uma notificação por e-mail ou notificação 
push de confirmação do cancelamento da consulta. 

#### Regras de Negócio: 
- As consultas canceladas deverão ser registradas no sistema com o motivo do cancelamento e com a data e a hora do cancelamento. 
- O sistema deve notificar o paciente através de email ou notificação push a partir da confirmação do cancelamento da consulta.
- O médico só poderá cancelar uma consulta com 24 horas de
antecedência.
- O sistema deverá mostrar uma mensagem de alerta na tela caso o
médico tente cancelar a consulta dentro de 24 horas antes da consulta
ser iniciada, impedindo ele de cancelar.

![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_medico/CancelarConsulta1.png?raw=true)
![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_medico/CancelarConsulta2.png?raw=true)

### 5. Como médico Eu quero receber um lembrete de que uma consulta está próxima Para evitar que eu me esqueça de consultas futuras.
#### Critérios de aceitação: 
- O médico deve poder selecionar nas configurações se deseja ou não receber lembretes. 
- O médico deve receber um lembrete 24 horas antes da consulta agendada e 1 hora antes da consulta agendada. 
- Os lembretes devem ser enviados por email e/ou notificação push, a depender da escolha do médico. 
- No conteúdo do lembrete deve constar a data, hora, nome do paciente e o motivo da consulta. 

![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_medico/Lembrete1.png?raw=true)
![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_medico/Lembrete2.png?raw=true)


### 6. Como médico Eu quero ver prontuários de pacientes Para me manter informado a respeito dos pacientes. 
#### Critérios de aceitação: 
- O médico deve ter acesso ao prontuário dos pacientes a partir do
botão de gerenciamento dos seus horários na página inicial do
aplicativo. 
- O prontuário deve incluir informações como histórico de consulta, diagnósticos, tratamentos, receitas médicas e resultados de exames.

![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_medico/Prontuario1.png?raw=true)
![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_medico/Prontuario2.png?raw=true)

### 8. Como médico Eu quero realizar upload de receitas médicas Para facilitar o controle do paciente com seus arquivos médicos. 
#### Critérios de aceitação: 
- O médico deve poder realizar uploads de receitas médicas nos formatos de JPEG, PNG, PDF, DICOM a partir do próprio dispositivo. 
- O médico deve enviar arquivos (imagem, PDF) de no máximo 20 MB por arquivo. 
- O médico deve ter uma prévia visualização dos arquivos a serem
enviados para a confirmação dos dados, podendo cancelar o envio e
refazer esse processo se achar necessário. 

#### Regras de Negócio: 
- O paciente deve ser notificado através de e-mail ou notificação push no momento em que o médico confirmar o envio da receita médica. 
- Todas as receitas médicas fornecidas devem ser armazenadas no sistema. 
- Todas as receitas médicas devem seguir os modelos fornecidos pelo CRM (Conselho Federal de Medicina) para garantir a conformidade dos documentos.

![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_medico/UploadReceitas1.png?raw=true)
![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_medico/UploadReceitas2.png?raw=true)
![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_medico/UploadReceitas3.png?raw=true)
![img](https://github.com/abreulucass/APP-WebDoctors/blob/main/Telas_prototitpo/telas_medico/UploadReceitas4.png?raw=true)

