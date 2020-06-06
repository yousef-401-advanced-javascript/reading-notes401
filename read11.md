# Authentication

### User Modeling
- Modern web applications need to model sensitive information about their users. When a users provides an applications with sensitive information, they are trusting that it will not be leaked are misused. This means that it is a developers responsibility to store that information responsibly.
- Some information, like emails, user names, and addresses can be stored in plain text, as long as the database is password protected and/or behind a firewall. 
-  Other information, like a users password, should be encrypted using a hashing algorithm before it is ever stored. this prevents anyone (including developers with database permissions) from ever getting access to their password.

### Cryptography
Cryptography is the science which studies methods for encoding messages so that they can be read only by a person who knows the secret information required for decoding, called the key; it includes cryptanalysis, the science of decoding encrypted messages without possessing the proper key, and has several other branches

### Hash Algorithms
-  Hash algorithms are often used for checking the integrity of data.
- If identical data is passed into the algorithm the same hash will always be produced.

### Cypher Algorithms
-  Cypher Algorithm takes a piece of data and a key and produces encrypted data. Later the encrypted data can be reversed into the original data by decrypting it using the same key.

### Basic Authorization

- Basic Authorization is a common method used to send a username and password in an HTTP request.
- The username and password are joined with a ‘:’ then “base64 encoded” and placed after the string ‘Basic ‘. The resulting string is set to the value of an Authorization header.
- A Server can decode the Basic Authorization header to retrieve the username and password.
- If the combination is validated, the server generally responds back to the client with some sort of validation response (token or key) so that the client can re-authenticate without having to continually send the username:password combination in plain text over the internet.
