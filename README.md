# Description
Artillery tests configuration for EduardoChat

# About Artillery
http://artillery.io/
Artillery is a modern load-testing framework capable of testing the protocols
that EduardoChat uses (Http(s) and Sockets)

# Installation
Just run `npm install -g artillery`

To check if installation was succesful or if already installed, you can run:

`artillery dino`, which should show an ASCII dinosaur.

# Execute tests
You may use `artillery run <chosen-test>.yml` or

`artillery quick --duration 20 --rate 10 -n 10 http://app-url/resource` for a quick test.
