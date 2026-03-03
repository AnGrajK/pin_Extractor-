# pin_Extractor-
The pin_extractor function is designed to generate secret numeric codes (PINs) from one or more poems. It takes a list of poems as input and processes each poem individually to extract a unique code.

For each poem:

The poem is split into separate lines using the newline character (\n).

Each line is then split into individual words.

For every line, the function selects a word based on the line’s index number.

From line 0, it selects word 0.

From line 1, it selects word 1.

From line 2, it selects word 2.

And so on.

It calculates the length (number of characters) of that selected word.

That number is added to a string called secret_code.

If a line does not contain enough words for that index, the digit 0 is added instead.

After processing all lines of a poem, the generated secret code is added to a list called secret_codes.

Finally, the function returns a list containing all generated secret codes, one for each poem provided.
