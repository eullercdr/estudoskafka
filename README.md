### TOPIC
 - Stream de dados que atua como um banco de dados (Recebe as informações e guarda no topico)  
 - Todos os dados ficam armazenados
 - Tópico possui diversas partições. (Distribui as informações em partições)
 - Cada partição é definido por um numero
 - Você é obrigado a definir o numero de partições ao criar o topico

### PRODUCERS
 - Quem está produzindo a informação e envia para a fila  

### Consumer
- Quem irá consumir a informação do producer  
- Posso ter vários consumers para o mesmo topico  

### Kafka Cluster
- Conjunto de Brokers  
- Cada Broker é um servidor  
- Cada Broker é responsavel por armazenar dados de uma partição  
- Cada partição de Topic está distribuido em diferentes Brokers  
- 
