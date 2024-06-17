# PACIENTE

### 1. Como paciente Eu quero marcar consultas online Para que eu não precise sair de casa e ir a locais físicos me consultar.

#### Critérios de aceitação: 
- Deve ser disponibilizado um calendário para o paciente selecionar o dia da consulta. 
- Deve ser disponibilizado ao paciente apenas horários disponíveis. 
- Deve ser disponibilizado ao paciente um campo onde ele deve escrever o motivo prévio da consulta. 
- Deve ser fornecido ao usuário uma tela com todos os dados informados por ele, para que ele possa confirmar todas as informações. 

#### Regras de Negócio: 
- Todas as consultas online devem ser asseguradas através da Lei da Telemedicina (Lei nº 14.510) que estabelece os critérios para atendimento médico a distância.

### 2. Como paciente Eu quero remarcar consultas Para evitar sair de casa. 

#### Critérios de aceitação: 
- O paciente deve ter acesso a opção de remarcar consulta através da lista de consultas. 
- O paciente deve poder selecionar uma nova data e hora para a consulta. 
- O paciente deve confirmar a nova data e hora da consulta. 
- O sistema deve atualizar automaticamente a nova data e hora. 

### 3. Como paciente Eu quero cancelar consultas Para evitar ir a locais físicos para fazer isso. 

#### Critérios de aceitação: 
- O paciente deve ter acesso a opção de cancelar consulta através da 
lista de consultas. 
- O paciente deve confirmar o cancelamento da consulta. 

#### Regras de Negócio: 
- As consultas canceladas deverão ser registradas no sistema com o 
motivo do cancelamento e com a data e a hora do cancelamento.
- O cancelamento da consulta só deverá ocorrer 24 horas antes da consulta. 

### 4. Como paciente Eu quero ver consultas marcadas Para que eu possa ter o controle das minhas consultas agendadas. 
#### Critérios de aceitação: 
- A partir da tela inicial do aplicativo o paciente deve ter acesso a lista de consultas. 
- O paciente deve visualizar todas as informações da consulta, como data, hora e o motivo da consulta. 
- As consultas marcadas devem ser mostradas em ordem cronológica, 
começando pela mais próxima. 
- O paciente deve ver o status da consulta, como cancelada, confirmada 
ou remarcada. 

### 5. Como paciente Eu quero receber lembretes de consultas agendadas para que eu não esqueça das consultas agendadas. 
#### Critérios de aceitação: 
- O paciente deve poder selecionar nas configurações se deseja ou não receber lembretes. 
- O paciente deve receber um lembrete 24 horas antes da consulta agendada e 1 hora antes da consulta agendada. 
- Os lembretes devem ser enviados por email e/ou notificação push, a depender da escolha do paciente. 
- No conteúdo do lembrete deve constar a data, hora, nome do médico e o motivo da consulta. 
- O paciente deve poder confirmar o recebimento do lembrete por email ou notificação. 

### 6. Como paciente Eu quero enviar exames Para facilitar o acesso do médico aos meus exames. 
#### Critérios de aceitação: 
- O paciente deve enviar os exames necessários para cada consulta ao 
entrar nos detalhes da consulta. 
- O paciente deve poder enviar seus arquivos de exames nos formatos de JPEG, PNG, PDF, DICOM a partir do próprio dispositivo.
- O paciente deve enviar arquivos (imagem, PDF) de no máximo 20 MB por arquivo. 
- O paciente deve ter uma prévia visualização dos arquivos enviados 
para a confirmação dos dados. 

#### Regras de negócio: 
- Os dados pessoais dos pacientes devem ser protegidos contra acesso não autorizado e em conformidade com a Lei Geral de Proteção de Dados Pessoais (nº 13.709/2018). 
- O médico deve ser notificado através de e-mail ou notificação push no 
momento em que o paciente confirmou o envio do exame. 
 
### 7. Como paciente Eu quero ver meu prontuário Para ter acesso fácil as minhas informações médicas. 
#### Critérios de aceitação: 
- O paciente deve ter acesso ao prontuário a partir da página inicial do aplicativo. 
- O prontuário deve incluir informações como histórico de consulta, diagnósticos, tratamentos, receitas médicas e resultados de exames. 
- Todas as informações devem estar listadas de cima para baixo. 
- O paciente deve poder realizar download do prontuário. 
- O prontuário deve estar disponível aos médicos para cada consulta. 

### 8. Como paciente Eu quero atualizar meu prontuário Para que minhas informações estejam sempre em dia para as consultas. 
#### Critérios de aceitação: 
- O paciente deve ter acesso a opção de atualizar seu prontuário a partir da página principal do aplicativo. 
- O paciente deve poder atualizar informações pessoais como nome, endereço e contato. 
- O paciente deve poder adicionar ou atualizar informações médicas. 
- O paciente deve ser informado da confirmação após a validação médica. 

#### Regras de Negócio:
- Todas as atualizações no prontuário do paciente devem ser revisadas e aprovadas por um médico antes de serem confirmadas e incorporadas permanentemente ao prontuário. 
- O médico responsável pela validação das atualizações deve ser notificado imediatamente após a submissão das alterações pelo paciente. 

### 9. Como paciente Eu quero ver fila de atendimento Para que eu possa me programar quanto às consultas. 
#### Critérios de aceitação: 
- O paciente deve ter acesso a opção de ver fila de atendimento a partir da página principal do aplicativo. 
- O paciente deve poder ver sua posição atual em tempo real na fila de atendimento. 
- O paciente deve poder ver o número de pessoas que tem à sua frente na fila. 
- O sistema deve fornecer ao paciente uma estimativa de espera na fila. 
- O paciente deve receber uma notificação quando sua vez estiver próxima. 

# MÉDICO 
### 1. Como médico Eu quero gerenciar meus horários Para um melhor controle dos meus atendimentos. 
#### Critérios de aceitação: 
- O médico deve ter acesso a opção de gerenciar seus horários a partir da página principal do aplicativo. 
- O médico deve ter acesso a todas as suas consultas marcadas. 
- O médico deve poder adicionar novos horários de atendimento especificando data e hora. 
- O médico deve poder modificar seus horários e datas de consultas. 
- O sistema deve permitir ao médico visualizar os horários do dia, 
semana e mês.
- O médico deve poder bloquear horários por indisponibilidade de atendimento. 
- O médico deve receber notificações de novas marcações, cancelamentos ou alterações de consultas. 
- O sistema deve alertar possíveis conflitos de horários ao editar um horário de atendimento. 

### 2. Como médico Eu quero gerenciar o histórico de consultas dos pacientes Para qualquer prévia informação importante que eu precise visualizar. 
#### Critérios de aceitação: 
- O médico deve ter acesso a opção de gerenciar o histórico de consultas dos pacientes a partir da página principal do aplicativo. 
- O médico deve ter acesso a informação completa de uma consulta, como receitas médicas fornecidas, exames feitos, nome do paciente, data, hora e o motivo da consulta. 
- O médico deve poder buscar consultas através do nome do paciente ou intervalos de data e hora. 
- O médico deve poder filtrar a busca por consultas através do motivo da consulta. 
- As consultas devem ser exibidas com a mais recente no topo. 
- O médico deve poder corrigir uma informação do detalhe da consulta. 

### 3. Como médico Eu quero remarcar consultas Para facilitar o gerenciamento de consultas com pacientes. 
#### Critérios de aceitação: 
- O médico deve poder remarcar a partir do gerenciamento de horários. 
- O médico deve poder selecionar a consulta específica que deseja 
remarcar. 
- O médico deve atualizar a nova data e horário da consulta. 
- O médico deve confirmar a nova data e hora da consulta. 
- O sistema deve notificar o paciente a partir da confirmação da 
remarcação da consulta ao paciente. 
- O médico deverá receber uma notificação por email ou push de 
confirmação da remarcação de consulta. 

### 4. Como médico Eu quero cancelar consultas agendadas Para o melhor gerenciamento dos meus horários.
#### Critérios de aceitação: 
- O médico deve poder remarcar a partir do gerenciamento de horários. 
- O médico deve poder selecionar uma consulta específica para cancelamento. 
- O sistema deverá solicitar ao médico os motivos do cancelamento. 
- O sistema deverá solicitar uma confirmação do médico para o 
cancelamento. 
- O médico deverá receber uma notificação por e-mail ou notificação 
push de confirmação do cancelamento da consulta. 

#### Regras de Negócio: 
- As consultas canceladas deverão ser registradas no sistema com o motivo do cancelamento e com a data e a hora do cancelamento. 
- O sistema deve notificar o paciente através de email ou notificação push a partir da confirmação do cancelamento da consulta. 

### 5. Como médico Eu quero receber lembretes de consultas agendadas Para evitar que eu me esqueça de futuras consultas. 
#### Critérios de aceitação: 
- O médico deve poder selecionar nas configurações se deseja ou não receber lembretes. 
- O médico deve receber um lembrete 24 horas antes da consulta agendada e 1 hora antes da consulta agendada. 
- Os lembretes devem ser enviados por email e/ou notificação push, a depender da escolha do médico. 
- No conteúdo do lembrete deve constar a data, hora, nome do paciente e o motivo da consulta. 
- O médico deve poder confirmar o recebimento do lembrete por email ou notificação. 

### 6. Como médico Eu quero ver prontuários de pacientes Para me manter informado a respeito dos pacientes. 
#### Critérios de aceitação: 
- O médico deve ter acesso ao prontuário dos pacientes na parte de gerenciamento dos seus horários. 
- O prontuário deve incluir informações como histórico de consulta, diagnósticos, tratamentos, receitas médicas e resultados de exames.
- O médico deve poder visualizar qualquer alteração feita pelo paciente no prontuário. 

### 7. Como médico Eu quero estabelecer uma duração máxima de tempo de uma consulta Para evitar que as consultas durem várias horas. 
#### Critérios de aceitação: 
- O médico deve poder estabelecer um tempo máximo de duração da consulta de acordo com o tipo da consulta. 
- O sistema deverá informar 15 minutos antes do fim da consulta ao médico que o fim da consulta está se aproximando. 
- O médico deve poder estender o tempo da consulta para mais 10 minutos se achar necessário. 
- O sistema deve armazenar o tempo total da consulta. 
- O sistema deverá informar 15 minutos antes do fim da consulta ao paciente que o fim da consulta está se aproximando. 

### 8. Como médico Eu quero realizar upload de receitas médicas Para facilitar o controle do paciente com seus arquivos médicos. 
#### Critérios de aceitação: 
- O médico deve poder realizar uploads de receitas médicas nos formatos de JPEG, PNG, PDF, DICOM a partir do próprio dispositivo. 
- O médico deve enviar arquivos (imagem, PDF) de no máximo 20 MB por arquivo. 
- O médico deve ter uma prévia visualização dos arquivos enviados para a confirmação dos dados. 

#### Regras de Negócio: 
- O paciente deve ser notificado através de e-mail ou notificação push no momento em que o médico confirmar o envio da receita médica. 
- Todas as receitas médicas fornecidas devem ser armazenadas no sistema. 
- Todas as receitas médicas devem seguir os modelos fornecidos pelo CRM (Conselho Federal de Medicina) para garantir a conformidade dos documentos.

