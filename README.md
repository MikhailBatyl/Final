# Final
Console.WriteLine("Введите текст:");
string text = Console.ReadLine();
string [] Variable = text.Split(' ');
Console.WriteLine("меньше трех: ");

for (int i = 0; i < Variable.Length; i++)
{
    if (Variable[i].Length < 4)
    {
        Console.Write($"[{Variable[i]}] ");
    }
}
