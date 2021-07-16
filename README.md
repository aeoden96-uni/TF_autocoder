# TF_autocoder_project
Autocoder supersampling project i did in TensorFlow, closely following similar topics on towardsdatascience.com, which i recommend as an excellent guide to convolutional networks.

## Instructions in Croatian
U Jupyter bilježnici je napisan sav kod koji sam radio ( na engleskom je dodana i dokumentacija ) 
te je napravljena prezentacija s generalnim opisom konvolucijskih mreža i mog projekta.


Radio sam supersampling slike pomoću auto enkodera.
Našao sam jednu dosta kompleksniju implementaciju modela,
pa sam ju usporedio sam svojom lakšom.

Dodano je također poglavlje koje sadrži jednostavne primjere autoencodera prije projekta da 
se vidi par primjena i kako se oni uopće koriste.

p.s. ukoliko želite rekonstruirati projekt napisat ću kratke upute:

1. skine se train set s linka http://vis-www.cs.umass.edu/lfw/lfw.tgz
2. doda se na google drive
3. na Google colabu se otvori biljeznica te se pomoću funkcije na pocetku prijavi na racun 
4. odkomentira se kod na pocetku te se unzipa slike iz fajla (to se ovako radi jer je uzasno mukotrpno stavljati na disk 13000 slika posebno)
5. postavi se google colab u Runtime > settings da koristi GPU
 
Dodana su također mini poglavlja u kojima sam dodao funkcije za spremanje međukoraka (varijabli) na Drive,
jer neke funkcije jako dugo traju da se izvrše. 
Znači prvi put pokrenete te funkcije (piše u kodu koje se trebaju pokrenuti bar jednom) zatim se spreme ,
te će te kopije živjeti na Disku. Na drugom pokretanju potrebno ih je samo loadati.
Isto vrijedi i za naučene modele (save i load). Sve piše u bilježnici kad je potrebno što napraviti.
