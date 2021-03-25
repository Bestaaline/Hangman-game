#Module qui va etre utiliser au cours de ce jeu
import random


solution = "python"
tentatives = 7
#creation d'une variable qui va servir d'affichage 
affichage = ""

lettres_trouvees = ""



while tentatives > 0:
  print("\nMot à deviner : ", affichage)
  proposition = input("proposez une lettre : ")
  
    if proposition in solution:
      lettres_trouvees = lettres_trouvees + proposition
      print("-> very well ! carry on")
      

 
  
  
  

