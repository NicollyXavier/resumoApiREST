# API REST e RESTFul

Uma **API REST** (Interface de Programação de Aplicações utilizando Transferência de Estado Representacional) é uma abordagem arquitetural que utiliza um conjunto de princípios para criar serviços web eficientes e escaláveis. Esses princípios incluem a utilização de URIs (Uniform Resource Identifiers) para identificar recursos, métodos HTTP para definir as operações, representações de recursos para transmitir dados e hiperlinks para navegar entre recursos relacionados.

## Diferenças entre REST e RESTFul

A diferença fundamental entre **REST** e **RESTful** reside no fato de que REST é um conjunto de princípios teóricos, enquanto RESTful representa a implementação prática desses princípios. Uma **API RESTful** segue as diretrizes do REST, garantindo a criação de sistemas web interoperáveis e eficientes.

## HTTP Verbs

Os **verbos HTTP** (ou métodos) são utilizados para definir a ação que deve ser realizada em um recurso identificado pela URI. Aqui estão alguns dos principais verbos:

- **GET:** Recupera informações de um recurso.
- **POST:** Cria um novo recurso.
- **PUT:** Atualiza um recurso existente.
- **DELETE:** Remove um recurso.
- **PATCH:** Aplica modificações parciais a um recurso.
- **OPTIONS:** Fornece informações sobre a comunicação disponível com um recurso.

Cada verbo desempenha um papel específico na manipulação de recursos, proporcionando uma interface consistente e previsível.

## HTTP Status Code

Os **códigos de status HTTP** são retornados pelo servidor para indicar o resultado da solicitação do cliente. Alguns códigos comuns incluem:

- **2xx (Sucesso):** Indica que a solicitação foi recebida, compreendida e aceita com sucesso.
- **3xx (Redirecionamento):** Informa que a solicitação precisa de mais ações para ser concluída.
- **4xx (Erro do Cliente):** Indica que o cliente parece ter feito algo errado.
- **5xx (Erro do Servidor):** Indica que o servidor falhou ao atender uma solicitação aparentemente válida.

Compreender esses códigos é crucial para depurar e melhorar a interação entre clientes e servidores.

---

**Autor do resumo:** Nicolly Xavier - 01553411
