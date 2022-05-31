# AlgoBot
A C++ stock market algorithmic trading bot

Calculates Technical indicators from stock market, will eventually make automatic buy/sell/hold decisions.

To run this on your machine.

You'll also need to at least have some C++ knowledge to edit the code for your needs.

To compile and run:

Put all the files from this repo into one folder, and have the above mentioned dependencies installed.

Next, run this in your terminal:

g++ *.cpp -std=c++11 -ljsoncpp -lcurl -o exa.out && ./exa.out -I/usr/local/Cellar/boost/1.67.0_1/include/boost/
