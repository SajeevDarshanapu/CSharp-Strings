# CSharp-Strings

string Bongaina = "NANI";
Console.WriteLine("The length of the txt string is: " + txt.Length);                 //OUTPUT:The length of the txt string is:4

---------------
string Bongaina = "NANI";
Console.WriteLine(txt.ToUpper());   // Outputs: NANI
Console.WriteLine(txt.ToLower());   //OUTPUT: nani

-------------Concatination

string firstName = "Poornakanti";
string lastName = "Lahari";
string name = firstName + lastName;                     //output: Poornakanti Lahari
                                                       //string name = string.Concat(firstName, lastName);
Console.WriteLine(name);

-----------------

# string interpolation, which substitutes values of variables into placeholders in a string.

string firstName = "Poornakanti";
string lastName = "Lahari";
string name = $"My full name is: {firstName} {lastName}";
Console.WriteLine(i);                                                  //output: Poornakanti Lahari

-------------ACCessing strings


string myString = "Hey";
Console.WriteLine(myString[0]);                                     // Outputs "H"

-------------
string myString = "Shinthalli";
Console.WriteLine(myString.IndexOf("n"));  // Outputs "3"

----------Substring

// Full name
string name = "Poornakanti Lahari";

// Location of the letter D
int charPos = name.IndexOf("n");

// Get last name
string lastName = name.Substring(charPos);              //Lahari

// Print the result
Console.WriteLine(lastName);

-----------
# Escape character	Result	       Description
\'	                '	          Single quote
\"	                "	          Double quote
\\	                \	            Backslash

# Code	Result	
\n	  New Line	
\t	    Tab	
\b	  Backspace
