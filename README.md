1) Please write smoke test for Sign Up form (yahoo.com). What HTTP-method (request) and status returned for Sign Up form? What tool can be used for catching?

**Test cases in this table:** https://docs.google.com/spreadsheets/d/1OQ9lSyw7e5x_kgnfIJ9Teu7pG0F83LJUc3Iquw8M9Nw/edit?folder=0AJzmFFJQwkKjUk9PVA#gid=0

*Test cases were writing without specification. All expected result is my point of view.

For catching can be used Browser Dev Tools. Tab “Network” has all information about requests. For "Sign Up" form returned this data:

Request Method: POST

Status Code: 204
***
2) Create JSON-file that contains information about employees.

JSON-file you can find in this repositiry.
***
3) Write SQL statement. Select subscribers with subscriptions from Omaha

SELECT p.lastName, p.firstName FROM Subscriptions s JOIN Subscribers p USING(id) WHERE s.newspaper = 'Omaha' AND s.status = 'Active';
