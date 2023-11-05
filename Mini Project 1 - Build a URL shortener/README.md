
# Build URL Shortener with API Implementation

This projects creates simple POST API for creating and storing a shortened URL endpoint for a long URL as well as a GET api to get the long URL when hitting short URL endpoint.

We require two additional libraries for the same: -
1. [cpp-httplib library](https://github.com/yhirose/cpp-httplib) for creating server and handling GET and POST requests.
2. [nlohmann/json library](https://github.com/nlohmann/json) for creating and serializing a JSON object.

You can download zip file from the given links and extract them into your project directory.

Make sure to link the libraries when compiling the code.

Command to link libraries when compiling code:
`g++ -I./cpp-httplib-master/ -I./json-develop/include -o shortenurl shortenurl.cpp -lws2_32`

The above command is for a windows system.

