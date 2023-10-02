using System.ComponentModel.Design;

double a;
double b;
char znak;
Console.WriteLine("Введите первое число!");
a = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("Введите второе число!");
b = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("Введите знак операции, которую хотите произвести с числами!");
znak = Convert.ToChar(Console.ReadLine());
if (znak == '+')
{
    Console.WriteLine("Сумма чисел " + a + " и " + b + " равна " + (a + b));
}
else if (znak == '-')
{
    Console.WriteLine("Разность чисел " + a + " и " + b + " равна " + (a - b));
}
else if (znak == '*')
{
    Console.WriteLine("Произведение чисел " + a + " и " + b + " равно " + (a * b));
}
else if (znak == '/' && b!=0)
{
    Console.WriteLine("Частное чисел " + a + " и " + b + " равно " + (a / b));
}
else if (b==0)
{
    Console.WriteLine("Не дели на ноль,а что все к чертям собачим полетит!");
}
else
{
    Console.WriteLine("Неизвестный знак!");
}
Console.ReadKey();