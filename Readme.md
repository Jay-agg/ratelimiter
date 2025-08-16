#Simple Rate Limiter in Go

This is a simple rate limiter implementation in Go that limits API requests using a token bucket algorithm.

## Installation

Make sure you have Go installed on your system. Then clone this repository, then:


Run : ```go run . ```

Test: ``` for i in {1..6}; do curl -i http://localhost:8080/ping; done ```