using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp1
{
    
          

class MainClass
    {
        static void Main()
        {

            int v, m;
            v = Convert.ToInt32(Console.ReadLine());
            m = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine(Math.Pow((v + m), 2));
            Console.ReadLine();

        }
    }

