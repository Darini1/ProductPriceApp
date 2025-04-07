Console.WriteLine("NewProductPrices");
string[] productNames = new string[10];
double[] productPrices = new double[10];


productNames[0] = "Apple";
productNames[1] = "Banana";
productNames[2] = "Orange";
productNames[3] = "Grapes";
productNames[4] = "Pineapple";
productNames[5] = "Mango";
productNames[6] = "Strawberry";
productNames[7] = "Watermelon";
productNames[8] = "Peach";
productNames[9] = "Kiwi";

productPrices[0] = 0.80;
productPrices[1] = 1.50;
productPrices[2] = 2;
productPrices[3] = 4.75;
productPrices[4] = 5;
productPrices[5] = 2.36;
productPrices[6] = 3;
productPrices[7] = 6.44;
productPrices[8] = 3.50;
productPrices[9] = 0.79;

//Add headings
Console.WriteLine("product Name " + "product Price");
Console.WriteLine("====================================" + " \t" + "====================");
for (int i =0; i < productNames.Length; i++)
{
    Console.WriteLine(productNames[i] + " \t\t" + productPrices[i]);
}
Console.ReadLine();
//a,b a+b

//for (int i = 0; i < productNames.Length; i++)
//{
//   Console.WriteLine(studentNames_2nd[i]);
//}
//Console.ReadLine();
using System;

class Program
{
    /*
    * Author: Darini Clark
    *Course: MISY2315 P01
    *Program Name: NewProductPrices
    Program Purpose: To display the product names and their prices
    */
}
