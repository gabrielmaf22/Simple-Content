# Simple-Content
uma abordagem de conteúdo ( C# / .NET ) de maneira simples.



## Enumerables

          <> Iterator          : termo que designa pegar cada item de algo
      
          <> Enumerable        : objeto que pode ser iterado
          <> Enumerator        : item de um conjunto que pode ser iterado 
          
          <> IEnumerable       : interface que requer que o objeto implemente "Enumerable"
          <> IEnumerator       : interface que requer que o objeto implemente "Enumerator"

  ### Estrutura - IEnumerable

          <> GetEnumerator()   : método deve retornar a instância de um objeto que implementa IEnumerator

![alt text](assets/images/img2.png)

  ### Estrutura - IEnumerator

          <> MoveNext()        : método deve retornar o próximo Enumerator
          <> Current()         : método deve retornar o atual Enumerator
          
![alt text](assets/images/img1.png)
