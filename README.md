# CSharp-Strings

string Sajeev = "NANI";
Console.WriteLine("The length of the txt string is: " + txt.Length);                 //OUTPUT:The length of the txt string is:4

---------------
string Sajeev = "NANI";
Console.WriteLine(txt.ToUpper());   // Outputs: NANI
Console.WriteLine(txt.ToLower());   //OUTPUT: nani

-------------Concatination

string firstName = "Sajeev";
string lastName = "Darshanapu";
string name = firstName + lastName;                     //output: Sajeev Darshanapu
                                                       //string name = string.Concat(firstName, lastName);
Console.WriteLine(name);

-----------------

# string interpolation, which substitutes values of variables into placeholders in a string.

string firstName = "Sajeev";
string lastName = "Darshanapu";
string name = $"My full name is: {firstName} {lastName}";
Console.WriteLine(i);                                                  //output: Sajeev Darshanapu

-------------ACCessing strings


string myString = "Hey";
Console.WriteLine(myString[0]);                                     // Outputs "H"

-------------
string myString = "Darshanapu";
Console.WriteLine(myString.IndexOf("n"));  // Outputs "8"

----------Substring

// Full name
string name = "Sajeev Darshanapu";

// Location of the letter D
int charPos = name.IndexOf("j");

// Get last name
string lastName = name.Substring(charPos);              //Sajeev

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
