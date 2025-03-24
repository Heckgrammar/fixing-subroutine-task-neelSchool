namespace FixSubroutineTask
{
    internal class Program
    {
        static void Main(string[] args)
        {
            for(int i = 0;i < 8; i++) {
                Console.WriteLine(diffCurrencies(i));            
            }
        }
        static string diffCurrencies(int x)
        {
            string[] currencies = { "baht", "dollar", "euro", "koruna", "lira", "rand", "rupee", "yen" };
            return currencies[x];
        }
    }
}
![image](https://github.com/user-attachments/assets/7abd7b57-ccf0-4836-9d46-452c04a09734)
