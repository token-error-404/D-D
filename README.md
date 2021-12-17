using System;

namespace dungens_and_dragons
{
    class Program
    {
        static void Main(string[] args)
        {
            Start();
            
        }

        static void Start() 
        {
            string d2_1;
            string d2_2;
            string d2_3;
            string d1;
            string name;
            Console.WriteLine("=====================================");
            Console.WriteLine("||  WELCOME TO DUNGEONS & DRAGONS  ||");
            Console.WriteLine("=====================================");
            Console.WriteLine("    ");
            Console.WriteLine("Alaric: Hello stranger what is you'r name ?");
            Console.Write("Me: my name is  ");
            name = Console.ReadLine();
            Console.WriteLine("Alaric: Hello " + name +" my name is Alaric Ophiar" );

            Console.WriteLine("Alaric: welcome to bolivol village ");
            Console.WriteLine("Alaric: whate brings u here ?");
            Console.WriteLine("you can those between (u neet to write it EXACTLY like i did)");
            // dis 1
            Console.WriteLine("=================================================");
            Console.WriteLine("|traveling|on the run|going to the duke|not sure|");
            Console.WriteLine("=================================================");
            Console.Write(name + ": i am " );
            //''''''''''''''''''''''
            d1 = Console.ReadLine();
           
            if (d1 == "traveling")
            {
                Console.WriteLine("___________________________________________");
                Console.WriteLine("Alaric: i know somewhere where you can stay");
                Console.WriteLine("Alaric: its a good inn i stayt there when i came here for the first time");
                Console.WriteLine("Alaric: i can show u if u want");
                Console.WriteLine("you can those between (u neet to write it EXACTLY like i did)");
                Console.WriteLine("========================");
                Console.WriteLine("|yes show me|no thanks||");
                Console.WriteLine("========================");
                d2_1 = Console.ReadLine();
            }
            //''''''''''''''''''''''''''''''
            
            if (d1 == "on the run")
            {
                Console.WriteLine("___________________________________________");
                Console.WriteLine("Alaric: thats not good");
                Console.WriteLine("Alaric: i can do 2 things ");
                Console.WriteLine("Alaric: i can go to the knites or i can let u go");
                Console.WriteLine("you can those between (u neet to write it EXACTLY like i did)");
                Console.WriteLine("========================");
                Console.WriteLine("|take the risk|run away||");
                Console.WriteLine("========================");
                d2_2 = Console.ReadLine();
            }
            //...................
             
            if (d1 == "going to the duke")
            {
                Console.WriteLine("___________________________________________");
                Console.WriteLine("Alaric: o a frend of the duke ");
                Console.WriteLine("Alaric: well i will let u do ur thing");
                Console.WriteLine("________________________");
                Console.WriteLine("FAIL| u lost");
                Console.WriteLine("===========================");
                Console.WriteLine("=   MADE BY TIM MAESSEN   =");
                Console.WriteLine("===========================");
                Console.WriteLine("=   PRESS enter TO CLOSE  =");
                Console.WriteLine("===========================");
            }








        }
    }
}
