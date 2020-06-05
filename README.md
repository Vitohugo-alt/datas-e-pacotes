# datas-e-pacotes
Lição de programação


using System;

namespace horaSistema
{
    class Program
    {
        static void Main(string[] args)
        {
            DateTime horaSistema = DateTime.Now; 
            Console.WriteLine($"Horado Sistema: {horaSistema}");
        }
    }
}




using System;

namespace IdadeAluno
{
    class Program
    {
        static void Main(string[] args)
        {
        
            DateTime nascimento = new DateTime(2004, 02, 07);
            Console.WriteLine($"{nascimento.ToLongDateString()}");

            //aniversario de 18 anos.

            DateTime maisvelho = new DateTime(2022, 02, 07);
            Console.WriteLine($"{maisvelho.ToLongDateString()}");
        }
    }
}


using System;
using Figgle;

namespace NomeASCIIArt
{
    class Program
    {
        static void Main(string[] args)
        {
            //Professor o senho poderia me dizer o que esta errado 

            Console.Write("Digite o seu nome: ");
            Console.ReadLine(FiggleFonts.DRPepper.Render("Nome2"));

        }
    }
}
