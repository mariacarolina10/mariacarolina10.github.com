mariacarolina10.github.com
==========================
<!DOCTYPE>
<html>
<head><title> </title>
</head>
<body>
<h1>QUIZ MUSICAL
</h1>
<img src="http://otvfoco.com.br/audiencia/wp-content/uploads/2014/09/2ulZWuq.jpg">

<p>teste seus conhecimentos musicais</p>
<p>você conhece as musicas atuais?</p>
<p>prove isso!</p>
<a href="https://github.com/mariacarolina10/mariacarolina10.github.com/blob/master/README.md">minha página!</a>

<a href="https://github.com/mariacarolina10/mariacarolina10.github.com/blob/master/README.md"> my page!</a>
</html>

import random
perguntas_fácil = (
    "Em que ano a banda One Direction começou?",
    "Somebody to you é a música da banda the vamps com...",
    "A cantora Miley Cyrus começou em que programa?",
    "De quem é a música Amnisia?",
    "One Direction lançou quantos cd's até hoje?",
    "A banda One Direction é formada por quantos integrantes?",
    "Qual foi o clipe mais polêmico de Miley Cyrus?",
    "A cantora Lorde lançou uma música para trilha sonora de um filme.Qual a música?",
    "O cantor Avicci fez sucesso com qual música?",
    "Que música foi gravada em uma parada gay?",

)
    
respostas_fácil = (
# ["RESPOSTA CERTA","RESPOSTA ERRADA","RESPOSTA ERRADA"]
    ["2010","2011","2012"],
    ["Demi Lovato","5sos","R5"],
    ["Hanna Montana","Drake e Josh","Zac e Cody gêmeos a bordo"],
    ["5sos","the vamps","meghan treinor"],
    ["4","5","6"],
    ["5","4","3"],
    ["wrecking ball","we can't stop","party in usa"],
    ["yellow flicker beat","400 lux","royals"],
    ["wake me up","hey brother","the days"],
    ["really don't care","come get bae","firework"],
)

# ---------------------------
def main():
    for índice,pergunta in enumerate(perguntas_fácil):
        print(str(índice+1) + ": " + pergunta)

        # shuffle embaralha só pra mostrar na tela
        respostas_embaralhas = list(respostas_fácil[índice])
        random.shuffle(respostas_embaralhas)

        for respostas in respostas_embaralhas:
            print(respostas)

        # entrada do usuário
        resposta = input("Qual a resposta? ")
        if resposta == respostas_fácil[índice][0]:
            print("+------------+")
            print("|Você acertou|")
            print("+------------+")
        else:
            print("+--------------+")
            print("|Tente de novo |")
            print("+--------------+")


if __name__ == '__main__':
    main()
</html>
