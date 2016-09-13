O que é REST
  Interação cliente - servidor
  Restrições: 
    1) Client Server: cliente envia um pedido para o servidor, o servidor por sua vez envia uma resposta para o cliente.
    2) Statelles Server: à medida que a carga aumenta a partir do cliente sobre o servidor temos que escalar nossos servidores para conseguir responder as requisições em tempo ábil. Nesta situação cada servidor que for escalado deve ter condições de responder as solicitação de clientes. Cada requisição do cliente precisa conter todas as informações necesárias para que qualquer server tenha condição de responder a requisição.
    3) Caching: Existe informações que não mudam frequentemente em nossa aplicação (cadastro de cliente, autores). Esta restrição diz que o cliente deve saber quanto tempo esses dados devem ser mantidos em cache antes de serem solicitados novamente ao servidor.
    4) Uniform Interface: Quando você está lidando com uma interface RESTful ela irá se comportar de uma maneira muito específica e para isso o REST define tres critérios que devemos seguir para manter nossa aplicação uniforme.
      4.1) Resources: Sempre que estiver lidando com um serviço RESTful você estará lidando com um recurso ou uma série de recursos. Isso significa que você está lidando com substantivos (livros, autores). Interfaces uniformes são construídos em torno de coisas e não ações.
      4.2) HTTP Verbs: Os verbos http vão ditar o tipo de atividade que estamos fazendo nos recursos. Por exemplo, o GET simplesmente solicita dados, uma lista de objetos ou um objeto específico.
      4.3) HATEOUS: Basicamente tudo o que isso significa é ue, em cada solicitação será um conjunto de hiperlinks que você pode usar para navegar na API.