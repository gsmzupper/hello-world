# Hello World

Este repositório contém as atividades realizadas por **Gabriel Samersla Merçoni** durante as aulas do Módulo 2. O objetivo é praticar conceitos básicos de programação em Java, como estrutura de classes, declaração de variáveis e uso do método `printf`.

## Estrutura do Projeto

O projeto possui duas classes principais:

### 1. **Classe `Main`**
- Esta classe contém um simples programa que exibe a mensagem "Hello, World!" no console.
- Exemplo de código:
    ```java
    public class Main {
        public static void main(String[] args) {
            System.out.println("Hello world!");
        }
    }
    ```
- Exemplo de saída:
    ```plaintext
    Hello world!
    ```

### 2. **Classe `DeclarandoVariaveis`**
- Esta classe demonstra a declaração e uso de diferentes tipos de variáveis em Java:
  - **String**: para armazenar o nome.
  - **int**: para armazenar a idade.
  - **double**: para armazenar a altura.
  - **boolean**: para indicar se o aluno está matriculado.
- As informações são exibidas no console utilizando o método `printf`.

#### Exemplo de Código:
```java
public class DeclarandoVariaveis {
    public static void main(String[] args) {
        String name = "Gabriel Samersla Merçoni";
        int idade = 27;
        double altura = 1.67;
        boolean matriculado = true;

        System.out.printf("Nome: %s \n idade: %d \n Altura: %.2f \n Matriculado: %b", name, idade, altura, matriculado);
    }
}
Exemplo de Saída:
1Nome: Gabriel Samersla Merçoni 
2idade: 27 
3Altura: 1.67 
4Matriculado: true
Como Executar
1. Certifique-se de ter o Java JDK instalado em sua máquina.
2. Clone este repositório:
1git clone [https:github.com/gsmzupper/hello-world.git]
3. Compile as classes:
1javac Main.java DeclarandoVariaveis.java
4. Execute a classe desejada:
Para a classe Main:
1java Main
Para a classe DeclarandoVariaveis:
1java DeclarandoVariaveis
Ferramentas Utilizadas
Java: Linguagem de programação utilizada para desenvolver as atividades.
JDK: Ambiente de desenvolvimento Java.
IntelliJ IDEA: IDE utilizada para escrever e executar o código.
Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.
