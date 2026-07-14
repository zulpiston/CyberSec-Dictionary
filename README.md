# PORT SCANNER

Asynchroniczny skaner portow TCP w C++ z uzyciem Boost.Asio.


##

Co sie dowiedzialem?

- 3 way TCP handshake i jak wyglada roznica miedzy portem CLOSED a FILTERTED

##

Moje rozszerzenia

- dodalem pomiar czasu calego skanu (std::chrono)

##

Uruchomienie

cmake .. && make && ./simplePortScanner - i <target> -p <zakres>

##

Zrodlo

Bazowy szkielet projektu: [Cybesecurity-Projects](https://github.com/CarterPerez-dev/Cybersecurity-Projects)  (AGPL3.0)