# StarWarsAPI
Website Link: https://codepen.io/tirthraj07/full/PoLNBOM<br>
Source Code: https://replit.com/@tirthraj07/Star-Wars-API<br>

## Star Wars API with jQuery and AJAX Request<br>

I used Bootstrap to make it more neat and responsive<br>

Further I added a search feature that searches the characters by name. Everytime you press a key, it searches for that character<br>

To reduce the API Calls, i scanned through the entire database first and stored them in a JavaScript Object, with names as keys and their ids as values (Note: id=7 does not have an API Endpoint) <br>

Then I just check if the input value is a substring of any of the keys and then display the items<br>

