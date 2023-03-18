# Store-Items

This is a simple program that allows the user to add and list store items. It uses file I/O to store the items in a binary file named "storeitem.dat".

The program begins by defining a structure called "items" which contains two fields, an integer for the item code and a character array for the item name.

The program then defines a character array called "filename" which stores the name of the file where the items will be stored.

The program then defines three functions, "Menu", "ListRecords", and "WriteaRecord".

The "Menu" function displays a menu to the user, allows the user to select an option, and performs the corresponding action based on the user's choice. It runs in an infinite loop until the user selects the "Exit" option.

The "ListRecords" function opens the file for reading in binary mode and reads the items from the file using a while loop and the "fread" function. It then prints the item code and item name for each item.

The "WriteaRecord" function prompts the user to enter an item code and item name and stores them in a structure of type "items". It then opens the file for writing in binary mode using the "fopen" function and writes the content of the structure to the file using the "fwrite" function. It then closes the file using the "fclose" function.

Finally, the "main" function simply calls the "Menu" function to start the program.

![p1](https://user-images.githubusercontent.com/76507378/226101134-53dd4ba4-1e87-45bc-ad02-714d6240efd4.png)
![p2](https://user-images.githubusercontent.com/76507378/226101141-a3614722-af8e-429b-9065-e6059d6dfe4b.png)
