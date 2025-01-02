Password Generator Script

This Python script generates secure, customizable passwords that meet specific constraints for length and character composition. The generated password ensures a mix of uppercase letters, lowercase letters, numbers, and special characters based on the user-defined requirements.
Key Features

    Customizable Length:
        Default length is 16 characters.
        You can specify any desired length.

    Character Constraints:
        Ensures the password contains:
            At least n numbers.
            At least n special characters.
            At least n uppercase letters.
            At least n lowercase letters.
        Default constraints are:
            nums=1
            special_chars=1
            uppercase=1
            lowercase=1

    Secure Randomness:
        Utilizes the secrets module for generating cryptographically secure random passwords.

    Validation:
        Verifies that the password meets all specified constraints before returning it.
