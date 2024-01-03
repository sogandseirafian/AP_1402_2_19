# AP_1402_2_19
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp15
{
    internal class Program
    {
        static void Main(string[] args)
        {
            int x = Convert.ToInt32(Console.ReadLine());
            int y = Convert.ToInt32(Console.ReadLine());
            double Result = Math.Sqrt(Math.Cos(x)*(Math.Abs(y - x) + Math.Sqrt(Math.Sin(x))));
            Console.WriteLine(Result);
            Console.ReadKey();
        }
    }
}
