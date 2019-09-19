# Igor Lavorchik
## Contact information 
* Mobile: +375259216568 
* e-mail: igorlavorchik@gmail.com
* [Facebook.](https://www.facebook.com/igor.lavorchik.5) 
## Summary
* The goal is to get a job as a junior front-end developer in a big company and in 5 years grow to a team lead.
* Interested in gaining new knowledge, I like to solve complex problems and do what others cannot do.
## Skills
* HTML
* CSS
* Git
* JS
* A little bit C#
## Code examples
 
        using System;

        public class MainClass
        {
            public static void Main()
            {
                 double a = Convert.ToDouble(Console.ReadLine());
                double b = Convert.ToDouble(Console.ReadLine());
                double c = Convert.ToDouble(Console.ReadLine());
                double x = Math.Pow(a, 2);
                double y = Math.Pow(b, 2);
                double z = Math.Pow(c, 2);
        
                    if ((a>=b && a>=c && x==y+z && a<b+c) || (b>=a && b>=c && y==x+z && b<a+c) || (c>=a && c>=b && z==x+y && c<a+b)) Console.Write("right");
                    else if ((a>=b && a>=c && x<y+z && a<b+c) || (b>=a && b>=c && y<x+z && b<a+c) || (c>=a && c>=b && z<x+y && c<a+b)) Console.Write("acute");
                    else if ((a>=b && a>=c && x>y+z && a<b+c) || (b>=a && b>=c && y>x+z && b<a+c) || (c>=a && c>=b && z>x+y && c<a+b)) Console.Write("obtuse");
                    else Console.Write("impossible");
        
            } 
        }


        using System;

        public class MainClass
        {
            public static void Main()
            {
                int a = Convert.ToInt32(Console.ReadLine());
                int b = a/100;
                int c = (a%100)/10;
                int d = (a%100)%10;
        
                if (c>b && d>c) Console.WriteLine("YES");
                else Console.WriteLine("NO");
            }
        }


## Experience
Experience is being gained right now
