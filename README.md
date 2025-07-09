Aqui está um exemplo de código em Java que realiza a conversão de temperatura de Celsius para Fahrenheit e Kelvin, conforme solicitado:

```java
import java.util.Scanner;

public class ConversaoTemperatura {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        // Solicita ao usuário a temperatura em Celsius
        System.out.print("Digite a temperatura em graus Celsius: ");
        double celsius = scanner.nextDouble();
        
        // Realiza as conversões
        double fahrenheit = (celsius * 9 / 5) + 32;
        double kelvin = celsius + 273.15;
        
        // Exibe os resultados
        System.out.printf("Temperatura em Celsius: %.2f °C%n", celsius);
        System.out.printf("Temperatura em Fahrenheit: %.2f °F%n", fahrenheit);
        System.out.printf("Temperatura em Kelvin: %.2f K%n", kelvin);
        
        scanner.close();
    }
}
```

### Explicação do código:
1. **Importação da classe Scanner**: Para ler a entrada do usuário.
2. **Criação da classe `ConversaoTemperatura`**: Ponto de entrada do programa.
3. **Leitura da temperatura em Celsius**: O usuário é solicitado a inserir um valor.
4. **Cálculo das conversões**: Usando as fórmulas fornecidas.
5. **Exibição dos resultados**: Os valores são apresentados de forma formatada.

Você pode compilar e executar este código em um ambiente Java para realizar as conversões desejadas!
