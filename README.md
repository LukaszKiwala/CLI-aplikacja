# CLI-aplikacja

# Otrzymujemy listę kontaktów

node index.js --action list
![Wynik w konsoli](/images/action-list.jpg)

# Otrzymujemy kontakt po id

node index.js --action get --id 'vza2RIzNGIwutCVCs4mCL'
![Wynik w konsoli](/images/action-get.jpg)

# Dodajemy kontakt

node index.js --action add --name John Rambo --email johnrambo@gmail.com --phone 222-33-44
![Wynik w konsoli](/images/action-add.jpg)

# Usuwamy kontakt

node index.js --action remove --id 'vza2RIzNGIwutCVCs4mCL'
![Wynik w konsoli](/images/action-remove.jpg)
