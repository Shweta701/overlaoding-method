# overlaoding-method


  class Program
    {
        static int plusint(int x, int y)
        {
            return x + y;

        }
        static double plusdouble(double x, double y)
        {
            return x + y;

        }
        static void Main(string[] args)
        {
            Program mynum = new Program();
            int mynum1 = plusint(2, 4);
            double mynum2 = plusdouble(2.5, 4.5);
            Console.WriteLine("int addition:"+mynum1);
            Console.WriteLine("double addiiton:"+mynum2);
            Console.ReadKey();
        }
