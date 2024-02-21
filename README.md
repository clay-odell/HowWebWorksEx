In your own terms, define the following terms:
What is HTTP? Hypertext Transfer Protocol: establishes the rules by which websites transfer information on the web.
What is a URL? It is the address of a webpage, typically human readable.
What is DNS? Domain Name Server: this is what translates a url into a machine readable IP address
What is a query string? A query string is a part of a URL that contains data to be passed to web applications, typically in the form of parameters and values after a question mark.
What are two HTTP verbs and how are they different? GET and POST. Get: requests without side effects, meaning they don’t change server data. Post: requests with side effects, which might be information to be saved or changed on a server or database.
What is an HTTP request? A request is like sending a letter to a URL requisition some action you want to take, like viewing a specific webpage, downloading a file, or posting a comment. It is sent using the hypertext transfer protocol.
What is an HTTP response? It’s the message that a website sends back to your computer after it has received and processed your HTTP request. This response contains the information you asked for, like the webpage you want to view, along with a status code that tells you whether the request was successful or not.
What is an HTTP header? They are request and response headers that contain the metadata for an HTTP request or response, such as the language, or content type. Give a couple examples of request and response headers you have seen.
Accept-Language: en-US,en;q=0.9; or Content-Type: text/html; charset=UTF-8. They are generally specified in the head section of an HTML page.
What are the processes that happen when you type “http://somesite.com/some/page.html” into a browser?
The browser requests a DNS server for the IP address, establishes a connection with the server at that address, sends an HTTP GET request to the server asking for the resource files some/page.html. Then the server sends back the requested file along with an HTTP response. The browser renders the HTML file, displaying the requested page on the screen

Part Two:
Curl
$ curl -H "Accept: text/plain" "https://icanhazdadjoke.com/search?term=pirate"
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100   295  100   295    0     0   2574      0 --:--:-- --:--:-- --:--:--  2610
What does a pirate pay for his corn? A buccaneer!
What did the pirate say on his 80th birthday? Aye Matey!
Why couldn't the kid see the pirate movie? Because it was rated arrr!
Why do pirates not know the alphabet? They always get stuck at "C".
Why are pirates called pirates? Because they arrr!
Dig
icanhazdadjoke.com.	113	IN	A	104.21.66.15
icanhazdadjoke.com.	113	IN	A	172.67.198.173

