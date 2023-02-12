# seminar 
Console.Write("Введите первое число: ");
int firstValue = Convert.ToInt32(Console.ReadLine());

Console.Write("Введите второе число: ");
int secondValue = Convert.ToInt32(Console.ReadLine());

if(firstValue > secondValue)
{
  Console.WriteLine("Число" + firstValue + "max");
}
else
{
  Console.WriteLine("Число" + firstValue + "min");
}
if(firstValue > secondValue)
{
  Console.WriteLine("Число" + secondValue + "max");
}
else
{
  Console.WriteLine("Число" + secondValue + "min");
}

# 4
Console.Write("Введите первое число: ");
int firstValue = Convert.ToInt32(Console.ReadLine());

Console.Write("Введите второе число: ");
int secondValue = Convert.ToInt32(Console.ReadLine());

Console.Write("Введите третье число: ");
int numberValue = Convert.ToInt32(Console.ReadLine());
int max = 0;
if (firstValue > max)max = firstValue;
if (secondValue > max)max = secondValue;
if (numberValue> max)max = numberValue;
Console.Write("max = ");
Console.Write(max);

# 6
Console.Write("Введите число: ");
int firstValue = Convert.ToInt32(Console.ReadLine());
if (firstValue % 2 == 0)
{
  Console.Write("Число четное: ");  
}
else
   Console.Write("Число нечетное: ");
   
   
   # 8
Console.Write("Введите число N: ");
int N = Convert.ToInt32(Console.ReadLine());
int numberValue = 0;
while(numberValue < N)
{
numberValue = numberValue + 2;
Console.WriteLine(numberValue);
}

