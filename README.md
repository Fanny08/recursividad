//parte1
package Fibonacci;
 // Método fibonacci recursivo.
 public class CalculoFibonacci{
// declaración recursiva del método fibonacci
public long fibonacci( long numero ){
 if ( ( numero == 0 ) || ( numero == 1 ) ) // casos base
 return numero;
 else // paso recursivo
 return fibonacci( numero - 1 ) + fibonacci( numero - 2 );
 } // fin del método fibonacci
 public void mostrarFibonacci(){
 for ( int contador = 0; contador <= 16; contador++ )
 System.out.printf( "Fibonacci de %d es: %d\n", contador,
 fibonacci( contador ) );
 } // fin del método mostrarFibonacci
} // fin de la clase CalculoFibonacci
