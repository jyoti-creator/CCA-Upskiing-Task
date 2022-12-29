Introduction to C# Programming
hello world program:
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace HelloWorld //DO NOT change the namespace name
{
    public class Program //DO NOT change the class name
    {
        public static void Main(String[] args)//DO NOT change the method signature
        {
            Console.WriteLine("Hello World");
        }
    }
}
output:
"Hello World"

Getting Inputs:
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace GettingInputs //DO NOT change the namespace name
{
    public class Program //DO NOT change the class name
    {
        public static void Main(string[] args)  //DO NOT change the method signature
        {
            Console.WriteLine("Enter an integer value");
            int i=Convert.ToInt32(Console.ReadLine());
            
            Console.WriteLine("Enter an float value");
           float f=Convert.ToSingle(Console.ReadLine());
           
             Console.WriteLine("Enter an double value");
            double d=Convert.ToDouble(Console.ReadLine());
             Console.WriteLine("Enter an long value");
            long l=Convert.ToInt64(Console.ReadLine());
             Console.WriteLine("Enter an string");
            string s=Console.ReadLine();
            
            Console.WriteLine("int: "+i);
          Console.WriteLine("float: "+f);
            Console.WriteLine("double: "+d);
            Console.WriteLine("long: "+l);
            Console.WriteLine("string: "+s);
            
        }
    }
}
Output:
Enter an integer value
5
Enter a Float Value
1.05
Enter a double value
6.89989
Enter a string
Hello

Application Form:
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ApplicationForm //DO NOT change the namespace name
{
	public class Program //DO NOT change the class name
	{
	    public static void Main(string[] args)
	    {
	        Console.WriteLine("Enter name");
	        string name=Console.ReadLine();
	        
	          Console.WriteLine("Enter age");
	        int age=Convert.ToInt32(Console.ReadLine());
	        
	         Console.WriteLine("Enter qualification");
	        string qualification=Console.ReadLine();
	        
	          Console.WriteLine("Enter PG/UG percentage");
	        double percent=Convert.ToDouble(Console.ReadLine());
	        
	        Console.WriteLine($"I am {name} {age} years old. I have completed {qualification} with {percent} percentage.");
	        
	         
	    }
	}
}
Output
Enter Name
Kennedy
Enter Age
25
Enter Qualification
ME
Enter PG/UG percentage
89.50
I am kennedy I am 25 years old.I have completed ME with 89.50 percentage.
