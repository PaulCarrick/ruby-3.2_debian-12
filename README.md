# Ruby 3.2.0 for Ddebian 12

These are the istructions to install Ruby 3.2.0 on Deain 12 using a package Paul Carrick built.

1) Install they public key for the jump-start-website repository:\
   **curl -fsSL https://jump-start-website.com:8443/distributions/jump-start-website.gpg | sudo tee /usr/share/keyrings/jump-start-website.gpg > /dev/null**
2) Add the repository to the apt source file:\
   **echo "deb [signed-by=/usr/share/keyrings/jump-start-website.gpg] https://jump-start-website.com:8443/distributions/debian/ stable main" | sudo tee /etc/apt/sources.list.d/jump-start-website.list**
3) Install the apt package:\
   **sudo apt update**\
   **sudo apt install ruby3.2**
