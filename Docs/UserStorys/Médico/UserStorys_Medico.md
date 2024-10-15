# MÉDICO 
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

### 2. Como médico Eu quero gerenciar o histórico de consultas dos pacientes Para visualizar informações de consultas já realizadas.
#### Critérios de aceitação: 
- O médico deve ter acesso a opção de gerenciar o histórico de
consultas dos pacientes a partir de um botão na página principal do
aplicativo.
- O médico deve ter acesso a informação completa de uma consulta, como receitas médicas fornecidas, exames feitos, nome do paciente, data, hora e o motivo da consulta. 
- O médico deve poder buscar consultas através do nome do paciente ou intervalos de data e hora. 
- O médico deve poder filtrar a busca por consultas através do motivo da consulta. 

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

### 5. Como médico Eu quero receber um lembrete de que uma consulta está próxima Para evitar que eu me esqueça de consultas futuras.
#### Critérios de aceitação: 
- O médico deve poder selecionar nas configurações se deseja ou não receber lembretes. 
- O médico deve receber um lembrete 24 horas antes da consulta agendada e 1 hora antes da consulta agendada. 
- Os lembretes devem ser enviados por email e/ou notificação push, a depender da escolha do médico. 
- No conteúdo do lembrete deve constar a data, hora, nome do paciente e o motivo da consulta. 

### 6. Como médico Eu quero ver prontuários de pacientes Para me manter informado a respeito dos pacientes. 
#### Critérios de aceitação: 
- O médico deve ter acesso ao prontuário dos pacientes a partir do
botão de gerenciamento dos seus horários na página inicial do
aplicativo. 
- O prontuário deve incluir informações como histórico de consulta, diagnósticos, tratamentos, receitas médicas e resultados de exames.

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
