import turtle

# Configurações da janela
screen = turtle.Screen()
screen.title("Desenho do Logotipo do Java")
screen.bgcolor("white")

# Configurações da tartaruga
t = turtle.Turtle()
t.speed(2)

# Função para desenhar a chama do logo do Java
def draw_flame():
    t.color("orange")
    t.begin_fill()
    t.left(50)
    t.forward(60)
    t.circle(20, 180)
    t.forward(60)
    t.right(100)
    t.forward(60)
    t.circle(20, 180)
    t.forward(60)
    t.left(50)
    t.end_fill()

# Função para desenhar a base do logo do Java
def draw_base():
    t.color("black")
    t.pensize(5)
    t.penup()
    t.goto(-50, -50)
    t.pendown()
    t.circle(50, steps=3)
    t.penup()
    t.goto(0, -50)
    t.pendown()
    t.circle(50, steps=3)

# Função principal para desenhar o logotipo do Java
def draw_java_logo():
    t.penup()
    t.goto(-30, 100)
    t.pendown()
    draw_flame()
    t.penup()
    t.goto(30, 100)
    t.pendown()
    draw_flame()
    draw_base()

# Desenha o logotipo do Java
draw_java_logo()

# Esconde a tartaruga e exibe a janela
t.hideturtle()
turtle.done()



# Projeto EBOOK Gerado por I.A.s

Projeto com o objetivo de gerar um ebook digital com as facilidades das ferramentas de IA. todos os prompts
seguem abaixo.


## 💻 Tecnologias utilizadas no projeto

- [ChatGPT](https://chat.openai.com/) 
- [MidJourney](https://www.midjourney.com/app/)
- [PowerPoint](https://www.microsoft.com/en/microsoft-365/powerpoint)

## 🧠 Prompts


ChatGPT：

|   Ação   | prompt                                                                                                                                                                                                                                                                         |
| :------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
|  título  | Crie um título de um ebook sobre o tema de css, o ebookk é do nicho de programação e o subnicho é de css, o título deve ser épico e curto, e tenha uma temática de star wars no título, me liste 5 variações de títulos                                                        |
| conteúdo | Faça um texto para ebook , com foco em CSS, listando os principais seletores CSS com exemplos em código {REGRAS} Explique sempre de uma maneira simples Deixe o texto enxuto, Sempre traga exemplos de código em contextos reais , sempre deixe um título sugestivo por tópico |


Midjourney：

|  Ação  | prompt                                                                                 |
| :----: | -------------------------------------------------------------------------------------- |
| título | A jedi in meditation pose, with your blue lightsaber floating, pixel art style --v 5.1 |

## ✨ Features

- Conteúdo gerado via ChatGPT
- Imagens geradas via MidJourney

## 📚 Materiais

- Imagens utilizadas em `assets`
- ebook gerado durante as aulas em `output`

## 🛠️ Instruções de execução

Utilize os prompts acima nas ferramentas sugeridas para gerar o material base e utilize uma ferramenta de edição de documentos como power point, libreoffice , indesign para diagramação.

