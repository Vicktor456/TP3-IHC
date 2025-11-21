# Mapa de Objetivos dos Usuários

## Etapa 1 - Definição dos Objetivos
Para iniciar a elaboração do mapa de objetivos do nosso sistema, nossa equipe realizou uma reunião voltada exclusivamente para a definição das principais funções oferecidas pela plataforma. Após identificar todas essas funcionalidades, conduzimos um processo de filtragem para selecionar os objetivos mais relevantes, garantindo que apenas os elementos essenciais fossem utilizados na construção do mapa.

Durante a formulação das ações e metas, tivemos como referência todas as personas desenvolvidas na etapa anterior do projeto. Buscamos garantir que cada objetivo estivesse alinhado a pelo menos uma dessas personas, representando suas necessidades, comportamentos e preferências. Essa abordagem ajudou a manter o foco no usuário real e a assegurar que o mapa refletisse cenários concretos de interação com o sistema.

Com todos os objetivos principais definidos e descritos, avançamos para a segunda etapa: o desenho visual do mapa de objetivos. Essa representação gráfica permitiu organizar de forma clara as relações entre funções, intenções dos usuários e caminhos de uso, facilitando a compreensão geral do propósito de cada ação dentro do sistema.

## 
<details>
<summary><strong>Lista Limpa dos Objetivos</strong></summary>

**1.** Acessar histórico/extrato de transações.  
**2.** Fazer transação pix.  
**3.** Fazer portabilidade de chave pix.  
**4.** Cadastrar chave pix.  
**5.** Cadastrar biometria.  
**6.** Excluir ou desativar conta.  
**7.** Excluir chave pix.  

</details>


## Etapa 2 - Mapas de Objetivos dos Usuários

### **MP 1**
<img width="3684" height="1924" alt="image" src="https://github.com/user-attachments/assets/1fa71083-8adf-4abd-9940-ae5126c72b48" />
Explicação: Este diagrama, detalha a estrutura lógica para a realização de uma transação Pix, estabelecendo que a ação de acessar a opção de transação é o instrumento fundamental que habilita todas as tarefas subsequentes. Uma vez que o usuário entra nesta funcionalidade, o fluxo se desdobra em etapas manuais essenciais que incluem a escolha do destinatário, a definição do valor a ser transferido, a verificação cautelosa dos dados para evitar erros e a execução de uma autenticação dupla como medida de segurança.


### **MP 2**
<img width="3684" height="1924" alt="image" src="https://github.com/user-attachments/assets/eb7ab8ed-a225-4b17-8c32-13c62457360a" />
Explicação: O diagrama mapeia o processo de consulta financeira onde a funcionalidade de acesso ao histórico serve como instrumento para que o usuário (seja ele comum, com necessidades de acessibilidade ou um tutor) possa navegar pelo sistema. O fluxo de tarefas consiste em localizar a aba correta na interface, identificar o extrato do período desejado, selecionar uma transação individual dentro dessa lista e, por fim, verificar os dados detalhados daquela operação, sem que haja uma ação final de processamento por parte do sistema, caracterizando um processo de pura consulta.

### **MP 3**
<img width="3684" height="1924" alt="image" src="https://github.com/user-attachments/assets/8045d689-20ed-4624-91fd-8b2819e3ef95" />
Explicação: Este mapa de objetivos descreve o fluxo de solicitação de portabilidade de chave Pix, onde a funcionalidade de gerenciamento de chaves atua como o instrumento que habilita o usuário (incluindo perfis de acessibilidade e tutores) a transferir sua chave de outra instituição. O processo envolve etapas de navegação interna, como localizar o menu Pix e selecionar a opção de portabilidade, seguidas pela confirmação do pedido no banco atual. O diferencial deste fluxo é a etapa final obrigatória de validação externa, onde o usuário deve, proativamente, confirmar a liberação da chave no banco de origem para que o processo seja finalizado com sucesso.


### **MP 4**
<img width="3684" height="2124" alt="image" src="https://github.com/user-attachments/assets/d6ef5f56-8046-4b4b-9bad-31d0235a16b9" />
Explicação: Este mapa descreve o fluxo de cadastro de uma nova chave Pix, onde a interface de gerenciamento de chaves atua como o instrumento que permite ao usuário (incluindo perfis de acessibilidade e tutores) vincular um dado pessoal à conta. O processo inicia com a navegação até a área específica e a seleção da opção de novo cadastro, segue para a escolha do tipo de chave desejada (CPF, e-mail, etc.) e a conferência dos dados inseridos. O fluxo é finalizado obrigatoriamente com uma etapa de segurança, exigindo que o usuário autentique a operação com sua senha para efetivar o registro da chave no sistema.


### **MP 5**
<img width="3684" height="1924" alt="image" src="https://github.com/user-attachments/assets/38913904-d7bb-45d1-a597-389aa42662b4" />
Explicação: Este mapa de objetivos detalha o procedimento de cancelamento de vínculo de uma chave Pix. A funcionalidade de exclusão atua como instrumento que permite ao usuário (incluindo perfis com necessidades de acessibilidade e tutores) remover uma chave previamente cadastrada. O fluxo lógico inicia com a navegação até a área de gestão, exige a seleção precisa da chave específica a ser removida e o acionamento do comando de exclusão. O processo é finalizado obrigatoriamente com uma etapa de validação de segurança, onde o usuário deve inserir sua senha para confirmar e efetivar a remoção da chave do sistema.

### **MP 6**
<img width="3684" height="1924" alt="image" src="https://github.com/user-attachments/assets/ea9551a9-7a4c-47df-8d93-f225a2d902da" />
Explicação: Este mapa de objetivos descreve o processo de ativação de segurança biométrica. A funcionalidade de cadastro atua como o instrumento que permite ao usuário (incluindo perfis de acessibilidade e tutores) substituir ou complementar o uso de senhas. O fluxo inicia-se com a navegação até as configurações de segurança do perfil, seguida pela seleção da opção de ativação. O núcleo do processo é a captura física da biometria (facial ou digital), sendo finalizado por uma etapa prática de teste, onde o usuário verifica o login rápido para garantir que a leitura biométrica foi configurada com sucesso.


### **MP 7**
<img width="3684" height="1924" alt="image" src="https://github.com/user-attachments/assets/eaa4e656-9bd7-46f3-b74f-3c3e2ab25ac9" />
Explicação: Este mapa de objetivos detalha o procedimento de encerramento de vínculo com a plataforma. A funcionalidade de desativação ou exclusão atua como instrumento que permite ao usuário (bem como perfis de acessibilidade e tutores) solicitar o fechamento da conta. O fluxo é projetado com etapas de navegação hierárquica — acessando primeiro o perfil e depois as configurações de conta — para evitar acionamentos acidentais. O processo culmina obrigatoriamente em uma etapa de confirmação dupla, uma barreira de segurança crítica para assegurar a intencionalidade e a autenticidade da solicitação antes que a exclusão seja efetivada.

### **MP 8**
<img width="3684" height="1928" alt="image" src="https://github.com/user-attachments/assets/dc0e12da-0216-45c8-b65d-8de12c3f694c" />
Explicação: Este mapa de objetivos descreve o processo de configuração de limites financeiros, uma ferramenta de segurança preventiva. A funcionalidade atua como instrumento que permite ao usuário (incluindo perfis de acessibilidade e suporte de tutores) estipular tetos máximos para suas operações. O fluxo inicia-se com o acesso às configurações e, crucialmente, inclui uma etapa de visualização dos limites atuais para embasar a decisão. Após inserir os novos valores desejados, o processo exige obrigatoriamente uma autenticação da solicitação, garantindo que alterações sensíveis na segurança da conta sejam validadas pelo titular.

