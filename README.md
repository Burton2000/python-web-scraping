# Web scraping example in Python

I wanted to get all the player names and their corresponding transfer fee from this url:
https://www.transfermarkt.com/premier-league/transfers/wettbewerb/GB1/plus/?saison_id=2017&s_w=&leihe=0&intern=0

To do this I use requests and beautifulsoup. Check the python notebook to see how it's done.

Result:
[('Álvaro Morata', '66,00 Mill. €'),
 ('Tiemoué Bakayoko', '40,00 Mill. €'),
 ('Danny Drinkwater', '37,90 Mill. €'),
 ('Antonio Rüdiger', '35,00 Mill. €'),
 ('Davide Zappacosta', '25,00 Mill. €'),
 ('Emerson', '20,00 Mill. €'),
 ('Olivier Giroud', '17,00 Mill. €'),
 ('Ross Barkley', '16,90 Mill. €'),
 ('Willy Caballero', 'Free transfer'),
 ('Diego Costa', '66,00 Mill. €'),
 ('Nemanja Matic', '44,70 Mill. €'),
 ('Nathan Aké', '22,80 Mill. €'),
 ('Juan Cuadrado', '20,00 Mill. €'),
 ('Asmir Begovic', '11,50 Mill. €'),
 ...


TODO: 
-Refactor out of notebook
