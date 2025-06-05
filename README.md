## DESAFIO: Modelo de domínio e ORM

<p>Você deve criar um projeto no Spring Boot com Java e banco de dados H2, e implementar o modelo
conceitual conforme especificação a seguir. Além disso, você deve fazer o seeding da base de dados
conforme diagrama de objetos que segue.</p>
<b>Como o trabalho será corrigido?</b>

<b>ESPECIFICAÇÃO - Sistema EVENTO:</b>
<p>Deseja-se construir um sistema para gerenciar as informações dos participantes das atividades de um
evento acadêmico. As atividades deste evento podem ser, por exemplo, palestras, cursos, oficinas
práticas, etc. Cada atividade que ocorre possui nome, descrição, preço, e pode ser dividida em vários
blocos de horários (por exemplo: um curso de HTML pode ocorrer em dois blocos, sendo necessário
armazenar o dia e os horários de início de fim do bloco daquele dia). Para cada participante, deseja-se
cadastrar seu nome e email.</p>

![diagrama_classe](https://github.com/user-attachments/assets/1a980d24-3d57-41ca-a469-e4f87881db25)

Instância dos dados para seeding (próxima página):

![seeding](https://github.com/user-attachments/assets/42bc7670-7a8f-4fd3-a205-fc6e227d991b)
