# **Goris German**

## Contact information 
* Location: Saint Petersburg, Russian Federation
* E-mail: goris404g@gmail.com
* GitHub: [Goris German](https://github.com/GorisGerman)
* Discord: Goris German#9478

## About Me
 I'm taking my first steps towards becoming a front-end developer. Although I don't have much programming experience, I'm always willing to learn new things that will help me reach my goal. I work well in a team but also on my own, I have good listening and communication skills. I am well organized and always plan ahead to make sure I manage my time well.

## Skills and Proficiency
beginner level
* С#
* HTML
* CSS
* Git
* Figma

## Code Example
Program for calculating the Ackermann function using recursion. C#

```
int InputNumbers(string input)
{
    Console.Write(input);
    int output = Convert.ToInt32(Console.ReadLine());
    return output;
}

Console.WriteLine("Enter two non-negative numbers m и n ");
int m = InputNumbers("Enter m: ");
int n = InputNumbers("Enter n: ");

int result = AckermannFunction(m, n);

Console.Write($"Result = {result}");

int AckermannFunction(int m, int n)
{
    if (m == 0) return n + 1;
    else if (m > 0 && n == 0) return AckermannFunction(m - 1, 1);
    else return AckermannFunction(m - 1, AckermannFunction(m, n - 1));
}
```
## Education
Emperor Alexander I St. Petersburg State Transport University: specialist’s degree in Economics and Management

## Courses
RS Schools Course «JavaScript/Front-end. Stage 0» (in progress)

## Languages
* Russian - native
* English - C2 proficient (EF SET)
[Certificate](https://www.efset.org/cert/VWP7cX)