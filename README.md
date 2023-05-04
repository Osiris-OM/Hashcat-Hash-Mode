# Hashcat-Hash-Mode

### my descriptioin:
you know the feeling when you need to use hascat but you have to google for 10min about what hash-mode you need to use, yeah i hate that too. so this is a small python script to search for hash modes.
this will save you almost 9 minutes which you can use to start memorizing the the 389+ hash modes.

### profisional description:
This is a Python script that defines a dictionary called hash_algorithms which contains various hashing algorithms as keys and their corresponding numerical mode as values.
Then, the script defines a function called search_hash_algorithms which takes a keyword as an input and searches for any matching key in the hash_algorithms dictionary. It uses a dictionary comprehension to create a new dictionary called matches which contains the hash algorithm names and their corresponding modes that contain the input keyword (case-insensitive).
If matches is not empty, the function prints out the names of the hash algorithms and their modes that contain the input keyword. Otherwise, it prints out a message indicating that no hash algorithms were found matching the input keyword.
Finally, the script prompts the user to enter a keyword and calls the search_hash_algorithms function with the input keyword to search for any matching hash algorithms in the hash_algorithms dictionary.

### use:
```
python3 hash_mode_lookup.py
Enter a keyword to search for hash algorithms: {put the hash mode you are looking for here}
Hash algorithms matching 'sha':
```
