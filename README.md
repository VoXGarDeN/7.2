using System;

public class Program
{
    public static void Main()
    {
        // Создание массива строк с именами пользователей
        string[] users = { "Егор", "Егор", "Егор", "Егор" }; // Егор

        // Вывод списка имен пользователей
        foreach (string user in users)
        {
            Console.WriteLine(user); 
        }
    }
}
