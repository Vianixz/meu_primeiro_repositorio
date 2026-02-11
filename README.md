meme_dicio = {
            "CRINGE": "Algo vergonhoso ou constrangedor",
            "STALKEAR": "Investigar a vida de alguém online",
            "LOL": "Laughing Out Loud — rindo muito",
            "IDK": "I Don't Know — eu não sei",
            "HYPE": "Algo muito aguardado ou popular",
            "GOAT": "Greatest Of All Time — o melhor de todos",
            "GG": "Good Game — bom jogo / acabou",
            "NOOB": "Iniciante ruim em algo",
            }

word = input("Digite uma palavra moderna que você não entende (escreva todo a palavra em letras maiúsculas): ")

if word in meme_dicio.keys():
    print(word)

else:
    print("palavra nao encontrada")
    

