/**
 * Clase que calcula el factorial de un número
 */
public class Factorial {
    
    /**
     * Calcula el factorial de un número
     * @param n El número del que queremos calcular el factorial
     * @return El resultado del factorial, o -1 si el número es negativo
     */
    public static int calcularFactorial(int n) {
        // Si el número es negativo, devolvemos -1
        if (n < 0) {
            return -1;
        }
        // Variable para guardar el resultado
        int resultado = 1;
        
        // Multiplicamos todos los números desde 1 hasta n
        for(int i = 1; i <= n; i++) {
            resultado = resultado * i;
        }
        
        return resultado;
    }
    
    public static void main(String[] args) {
        // Probamos con el número 5
        int numero = 5;
        
        // Calculamos su factorial
        int resultado = calcularFactorial(numero);

        // Se muestra el resultado
        System.out.println("El factorial de " + numero + " es: " + resultado);
    }
}