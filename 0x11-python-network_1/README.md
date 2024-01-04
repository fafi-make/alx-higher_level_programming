Python - Network #1

This project involved learning how to use the urllib and requests Python libraries to send and receive HTTP messages to URL's. I practiced sending GET and POST requests, fetching JSON resources, and interacting with API's (the Star Wars API, GitHub API, and Twitter API). Tasks page_with_curl

What's my status? #0 0-hbtn_status.py: Python script that fetches https://intranet.hbtn.io/status. Uses urllib.

Response header value #0 1-hbtn_header.py: Python script that displays the X-Request-Id response header variable of a request to a given URL. Usage: ./1-hbtn_header.py Uses urllib.

POST an email #0 2-post_email.py: Python script that sends a POST request to a given URL with a given email, and displays the response body. Usage: ./2-post_email.py . Uses urllib.

Error code #0 3-error_code.py: Python script sends a request to a given URL and displays the response body. Handles HTTP errors. Uses urllib.

What's my status? #1 4-hbtn_status.py: Python script that fetches https://intranet.hbtn.io/status. Uses requests.

Response header value #1 5-hbtn_header.py: Python script that displays the X-Request-Id response header variable of a request to a given URL. Usage: ./5-hbtn_header.py Uses requests.

POST an email #1 6-post_email.py: Python script that sends a POST request to a given URL with a given email, and displays the response body. Usage: ./6-post_email.py . Uses requests.

Error code #1 7-error_code.py: Python script sends a request to a given URL and displays the response body. Handles HTTP errors. Uses requests.

Search API 8-json_api.py: Python script that sends a POST request to http://0.0.0.0:5000/search_user with a letter passed as parameter. Usage: ./8-json_api.py The letter is sent as the value of the variable q. If no letter is given, sets q="". If the response body is properly formatted and non-empty, displays it as [] . Uses requests.

Star Wars API #0 9-starwars.py: Python script sends a search request to the Star Wars API people endpoint with a given string. Usage: ./9-starwars.py Displays the total number and name of each result. Uses requests.

My Github! 10-my_github.py: Python script that takes GitHub credentials (username and password) and uses the Github API to display the corresponding ID. Usage: ./10-my_github.py Uses requests.

Time for an interview! 100-github_commits.py: Python script that lists the 10 most recent comments of a given GitHub repository using the GitHub API. Usage: ./100-github_commits.py Uses requests.

Star Wars API #1 101-starwars.py: Python script that sends a search request to the Star Wars API people endpoint with a given string. Usage: ./101-starwars.py Displays the total number and name of each result. Manages pagination to display all results. Uses requests.

Star Wars API #2 102-starwars.py: Python script that sends a search request to the Star Wars API people endpoint with a given string. Usage: ./102-starwars.py Displays the total number and name of each result as well as the list of films associated with each character. Manages pagination to display all results. Uses requests.

Twitter Auth 103-search_twitter.py: Python script that sends a search request to the Twitter API search endpoint with a given string. Usage: ./103-search_twitter.py Displays the the top 5 results in the format [] by . Uses requests.