# PACIENTE

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

### 2. Como paciente Eu quero remarcar consultas Para evitar sair de casa. 

#### Critérios de aceitação: 
- O paciente deve ter acesso a opção de remarcar consulta através do botão na tela inicial de lista de consultas. 
- O paciente deve poder selecionar uma nova data e hora para a consulta. 
- O paciente deve confirmar a nova data e hora da consulta. 
- O sistema deve atualizar automaticamente a nova data e hora.
- O sistema deve confirmar ao paciente a remarcação da consulta através de uma mensagem na tela de confirmação
#### Regras de Negócio
- O paciente só poderá remarcar uma consulta com 24 horas de antecedência.

### 3. Como paciente Eu quero cancelar consultas Para evitar ir a locais físicos para fazer isso. 

#### Critérios de aceitação: 
- O paciente deve ter acesso a opção de cancelar consulta através do botão na tela inicial de lista de consultas.
-  O sistema deverá solicitar ao paciente os motivos do cancelamento através de campo que ele poderá preencher escrevendo seus motivos.
- O paciente deve confirmar o cancelamento da consulta. 

#### Regras de Negócio: 
- As consultas canceladas deverão ser registradas no sistema com o 
motivo do cancelamento e com a data e a hora do cancelamento.
- O paciente só poderá cancelar uma consulta com 24 horas de
antecedência.
- O sistema deverá mostrar uma mensagem de alerta na tela caso o
paciente tente cancelar a consulta dentro de 24 horas antes da
consulta ser iniciada, impedindo ele de cancelar.

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

