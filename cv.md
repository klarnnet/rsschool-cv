# Анна Клепикова
## Контактs
* **Телефон:** +375 29 374-54-82
* **Электронная почта:** annaklepikovae@gmail.com
* **GitHub:** Klarnnet
* **Telegram:** Klarnnet
## Обо мне

Меня зовут Анна Егоровна Клепикова,
 Мне 18 лет и в данный момент я учусь
на 3 курсе Минского радиотехнического колледжа
(филиал БГУИР) по специальности «Программное обеспечение информационных технологий».
 Мне очень нравится сам процесс обучения, узнавать
 новое для самостоятельного изучения новых языков программирования и программ.
 Еще мне нравятся такие виды спорта, как теннис и плавание. Я люблю рисовать
и создавать что-нибудь.
Мне нравится видеть результат своей работы.

## Навыки и умения
* HTML
* CSS
* C++
* C#
* Photoshop, Illustrator,Figma
* Git/GitHub
## Пример кода
```
using System;

namespace laba15
{
    class Program
    {
        public static double tryInputDouble()
        {
            try
            {
                double a = Convert.ToDouble(Console.ReadLine());
                return a;
            }
            catch
            {
                Console.WriteLine("Введите не строоку, а число:");
                return tryInputDouble();
            }
        }


        static void Main(string[] args)
        {
            double a = 0;
            try
            {
                Console.WriteLine("Введите значение a: ");
                a = tryInputDouble();
            }
            catch
            {
                Console.WriteLine("Введите не строоку, а число: ");
                try
                {
                    a = Convert.ToInt32(Console.ReadLine());
                    if (a < 0)
                    {
                        throw new Exception("Введите положительное число");
                    }
                }
                catch (Exception iskl)
                {
                    Console.WriteLine(iskl.Message);
                    a = Convert.ToInt32(Console.ReadLine());
                }
               

            }
            finally
            {
                double tg2a;
                tg2a = (2 * Math.Tan(a)) / (1 - Math.Pow(Math.Tan(a), 2));
                Console.WriteLine("Значение тансенса двух альфа равно: " + tg2a);
            }

            Console.ReadKey();
        }
    }
}

```

## Образование
* Минский Радиотехнический колледж филиал БГУИР (программное обеспечение информационных технологий)
*  Компьютерная Академия ШАГ
## Языки
* Русский - носитель языка
* Белорусский - носитель языка
* Английский - B1
