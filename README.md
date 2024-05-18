int n = 5; // Replace with user input for the number of rows/columns

// Draw the rectangle with stars
for (int i = 0; i < n; i++)
{
    // Print the first and last columns with stars
    Console.Write("*");

    // Print empty spaces for the remaining columns
    for (int j = 0; j < n - 2; j++)
    {
        Console.Write(" ");
    }

    // Print the last column with a star
    Console.Write("*");

    // Move to the next line
    Console.WriteLine();
}
