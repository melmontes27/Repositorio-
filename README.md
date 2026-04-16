using System;

public class Computadora 
{
    private Procesador procesador;
    
    public Computadora()
    {
        procesador= new Procesador();
        procesador. Marca="AMD";
        
    }
    public void Encender()
    {
    Console.WriteLine("La computadora esta encendida");
    
    procesador.mostrarMarca();
    }
