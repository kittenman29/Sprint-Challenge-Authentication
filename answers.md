What is the purpose of using sessions?

It's another security method because it makes it so that hackers aren't able to try to brute force passwords
because the passwords hashes are reset frequently enough.

What does bcrypt do to help us store passwords in a secure manner?

It incorporates a salt and hashing so that the passwords are not as easily brute forced.  This allows us
to use cookies to pass the token back and forth to verify credentials.

What does bcrypt do to slow down attackers?

It incorporates a salt and hashing of the password so that they're not stored in plaintext.

What are the three parts of the JSON Web Token?

The header, the payload, and the signature.