
#Longest Common Substring

###Your first API w/ an Algo problem thrown in

Write a flask app in `longest_common_subtring.py`.
This app should simply return the longest common substring of the two strings passed in.

- The API call should accept a GET request to the url '/lcs'.
- Data should be passed in as a JSON and return the data as a JSON.

####JSON

- [Look up how to access the data in an HTTP request with Flask.](http://stackoverflow.com/questions/14112336/flask-request-and-application-json-content-type)
- Look up how to switch between Python dictionaries and JSON [with the json library](http://pymotw.com/2/json/).

```javascript
input = {
  "string1": "<first string>",
  "string2": "<second string>"
}

response = {
  "longest_common_substring": "<the longest common substring>"
}
```

A skeleton is provided. Implement the functions declared.

Test your app by running `longest_common_subtring_tests.py`.


####Longest Common Substring

This is the longest string found in both strings.
For instance, the longest common substring of `abc` & `bcd` is `bc`.
The longest common substring of `abc` and `def` should be an empty string.

###Need Help?

The [Flask website](http://flask.pocoo.org/) is a incredible resource.
[Stack Over](http://stackoverflow.com/) is great as well.

