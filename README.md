# test-IT
# https://github.com/iteklic/test-IT.git
# SELECT ime_prezime FROM `zaposlenik` WHERE id IN( 
  SELECT id FROM `evidencija` WHERE broj_sati IN ( 
  SELECT MAX(broj_sati)));
