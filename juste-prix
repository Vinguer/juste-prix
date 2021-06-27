import random

jouer = "oui"
while jouer == "oui":
    justeprix = random.randint(0,200)
    essaie = 0
    prix = int(input("Choisissez un chiffre entre 0 et 200 : "))

    while prix != justeprix:
        if prix < justeprix:
            prix = int(input("le prix est inferieur au juste prix ! : "))
        else:
            prix = int(input("le prix est superieur au juste prix ! : "))
    essaie = essaie + 1

    print(f"Bravo ! vous avez trouver le justeprix en {essaie} essaies ! ")
    jouer = input("Voulez vous rejouer ? repondez par oui ou par non : ")

    if jouer != "oui":
        print("le jeu se termine")
