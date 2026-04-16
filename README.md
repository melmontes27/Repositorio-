using System;
//class medico
public class Medico
{
    public string Especialidad {get; set;}
    public void Atender(Paciente p)
    {
        Console.WriteLine($"Atendiendo a {p.Nombre} en la clinica de {Especialidad}");
    }
}
//class paciente
public class Paciente
{
    public string Nombre{get; set;}
}
class Program
{
    static void Main()
    {
        Medico DrSimi=new Medico {Especialidad = "Pediatria"};
        Paciente boy=new Paciente {Nombre="Jaunito"};
        DrSimi.Atender(boy);
    }
    
}
