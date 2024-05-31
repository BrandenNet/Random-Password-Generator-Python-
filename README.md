# Random-Password-Generator-Python-

## Introduction

In this project, I built a random number password generator using the coding language python. I put all sorts of commands and conditions like using if then statments, functions, and more.

## Code

<img src="https://cdn.discordapp.com/attachments/716795860234665987/1246147500159537253/Python_.png?ex=665b54cc&is=665a034c&hm=8329abe8bf824abd40117295213b08e23d1e75cf39a7f59a59ae8409695153a2&" alt="View."></a>

## Explanation of Code

The psswd function is designed to generate a random password based on the user’s preferences. It takes six parameters: length, use_lower, use_upper, use_digits, use_symbols, and use_letters, all of which default to True. These parameters determine whether the generated password should include lowercase letters, uppercase letters, digits, symbols, and letters in general (both uppercase and lowercase), respectively.

The function starts by initializing an empty string characters. Depending on the boolean flags provided, it appends the corresponding sets of characters from the string module to the characters string. For example, if use_lower is True, it adds all lowercase letters to characters. Similarly, if use_upper is True, it adds all uppercase letters, and so forth for digits and punctuation symbols. If use_letters is True, it adds both uppercase and lowercase letters, which can lead to redundancy if use_lower and use_upper are also True.

The password generation is performed using a list comprehension inside the join method. The comprehension iterates length times, each time randomly selecting a character from the characters string. The result is a string of random characters of the specified length, which is then returned by the function.

The code then includes a section to handle user input. It prompts the user to enter the desired length of the password and attempts to convert this input into an integer. If the input is not a valid integer, a ValueError is caught, and an error message is printed, though the subsequent function calls might fail if length is not correctly set.

The order function is responsible for gathering the user's preferences for the password. It asks the user whether they want to include letters, uppercase letters, lowercase letters, digits, and symbols in the password. Each input is converted to lowercase and checked if it is 'yes'. These inputs determine the values of the corresponding boolean flags that are passed to the psswd function. The generated password is then printed.

Finally, the order function is called to execute the sequence of prompts and generate the password based on the user’s choices. 

<img src="https://cdn.discordapp.com/attachments/716795860234665987/1246149897137291389/Screenshot_2024-05-31_121406.png?ex=665b5707&is=665a0587&hm=d1ce88d80ea40ac540a0cf8a4bf39298332fe7febdeb0af0998b4b00c27aa71c&" alt=""></a>


## Conclusion

To wrap this up, this was my first python project and I very much enjoyed it creating this random number password generator using different commands, functions, and many more and will hope to make more projects in the future.
