/*
 Author : Peter Theobald Jr
Date:1/24/23
Description: Deliverable 2, Conditional Statements about letter grade expected
by students for ISM 4300
*/
using System;
using System.Diagnostics.Metrics;

namespace Deliverable_2_
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Enter a numeric grade: ");

            try
            {
                decimal grade = decimal.Parse(Console.ReadLine());

                

                if (grade >= 90)
                {
                    
                    Console.WriteLine("Your expected letter grade for ISM 4300 is A");
                    Console.ReadKey(true);
                }

                else if (grade >= 80 && grade < 90)
                {
                    
                    Console.WriteLine("Your expected letter grade for ISM 4300 is B");
                    Console.ReadKey(true);
                }
                else if (grade >= 70 && grade < 80)
                {
                    Console.WriteLine("Your expected grade for ISM 4300 is C");
                    Console.ReadKey(true);
                }
                else if (grade >= 60 && grade < 70)
                {
                    Console.WriteLine("Your expected letter grade for ISM 4300 is D");
                    Console.ReadKey(true);

                }
                else
                {
                    Console.WriteLine("Your expected letter grade for ISM 4300 is F");
                    Console.ReadKey(true);
                }   
            }
            catch
            {
                Console.WriteLine("Enter a numeric value");
                
            }

        }
    }
}