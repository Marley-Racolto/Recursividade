class Program
{
static int nums(int x)
 {
   if (x == 1) return 1;
   return (x + nums(x - 1));
 }
   static void Main(string[] args)
 {
 
 int x;
 
   Console.Write("Digite um numero: ");
   x = int.Parse(Console.ReadLine());

   Console.WriteLine("Com recursividade");
   Console.WriteLine(nums(x));
 }
}
