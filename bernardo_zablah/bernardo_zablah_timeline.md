# <h1 style="text-align: center;">Línea temporal de la evolución de la informática y mi relación con ella. </h1>


## Índice
- [**2010 - Primer contacto con la tecnologia**](#2010---primer-contacto-con-la-tecnologia)
- [**2011 - Primera consola**](#2011---primera-consola)
- [**2015 - Primera PC**](#2015---primera-pc)
- [**2016 - Primer iPad**](#2016---primer-ipad)
- [**2018 - Primer Móvil**](#2018---primer-móvil)
- [**2019 - Primer Lenguaje de Programación**](#2019---primer-lenguaje-de-programación)
- [**2020 - Primera PC que armé yo mismo**](#2020---primera-pc-que-armé-yo-mismo)
- [**2022 - Aprendizaje de más lenguajes de programación**](#2022---aprendizaje-de-más-lenguajes-de-programación)
- [**2024 - Ingreso al grado de Ingeniería Informática**](#2024---ingreso-al-grado-de-ingeniería-informática)

---

##  **2010 - Primer contacto con la tecnologia**
Mi primer contacto con un dispositivo fue la **Television**. Mas precisamente, mis padres me dicen que en esta epoca me gustaba ver *Barney*  en la TV.

![Foto de TV](https://s3.amazonaws.com/s3.timetoast.com/public/uploads/photo/20903600/image/medium-c4fc418051767c099a59b1f117d0f083.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAJB6ZCNNAN7BE7WDQ%2F20240921%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240921T233822Z&X-Amz-Expires=604800&X-Amz-SignedHeaders=host&X-Amz-Signature=05c7d593a75d0796c36f580a225b372b6bd4b61f36fdb7b136a9c68b6bd8145e)


##  **2011 - Primera consola**
Después de hacer el primer contacto con un dispositivo, el siguiente hito que alcancé fue jugar con una **consola**. Entonces, mi hermana y yo pedimos una consola [Wii](https://es.wikipedia.org/wiki/Wii) para **navidad**.

![Foto Wii](https://upload.wikimedia.org/wikipedia/commons/thumb/8/83/Wii_console.png/1200px-Wii_console.png)

##  **2015 - Primera PC**
Tiempo después de haber jugado en una consola, me entró la curiosidad de hacer algo en un **PC**. Entonces, le pedí permiso a mi padre para empezar a usar el ordenador que tenía en casa, y él me dijo que sí. Lo usaba sobretodo para **jugar videojuegos** o ver videos en **YouTube**. No me acuerdo del modelo exacto del ordenador pero era uno muy parecido al de la imagen.

![Foto PC](https://images.icecat.biz/img/gallery_mediums/img_938109_medium_1480984830_9647_5647.jpg)

##  **2016 - Primer iPad**
Mi primer **iPad** me lo compraron para que pudiera distraerme en casa (obviamente tenía un tiempo maximo al día para usarlo). El iPad era un iPad mini, aunque no recuerdo qué generación o modelo era.

![Foto del iPad](https://www.notebookcheck.org/uploads/tx_nbc2/4zu3_ipadmini4.jpg)


##  **2018 - Primer Móvil**
Mi primer móvil lo recuerdo bien. Me lo compraron cuando regresé de un viaje. Era un **Samsung J2** y me duró aproximadamente 2 años. Luego, fui actualizándolo. 

![Foto de movil](https://www.celulares.com/fotos/samsung-galaxy-j2-2018-66529-g-alt.jpg)

##  **2019 - Primer Lenguaje de Programación**

El primer lenguaje de programación que toqué fue [Scratch](https://scratch.mit.edu/). Creo que fue el primer lenguaje de programación para muchos. Este me permitió aprender las bases de la lógica de la programación.

![Foto Scratch](https://cursosinformatica.ucm.es/img/cursos/scratch2.png)

##  **2020 - Primera PC que armé yo mismo**
Llegó la pandemia y me quedé un poco aburrido. Ahí fue cuando empecé a gustar de la tecnología, pues me fascinaba ver cómo personas en Internet armaban sus ordenadores, y yo quería armar el mío. Además, ya necesitaba uno para los estudios, porque el que mi padre me había dejado ya estaba un poco viejo. Así que me puse a investigar los componentes más adecuados que se ajustaran a mis necesidades y presupuesto.  
Terminé armando la PC con los siguientes componentes:

| Componente | Pieza |
| ----- | --- |
| Motherboard | ASUS PRIME B360M |
| Procesador | Intel Core i7-8700 |
| Power Suply | EVGA 400W POWER SUPPLY |
| Almacentamiento | KINGSTON A400 SSD 480G |
| Tarjeta Grafica | ASUS PHOENIX GTX1650 |
| RAM | 2x HYPERX FURY 8GB DDR4 2666 Mhz. |

> Esa PC me duró casi 5 años, pero le actualicé los componentes un par de veces.


##  **2022 - Aprendizaje de más lenguajes de programación**
En mi primer año de bachillerato me dieron la opción de estudiar un poco de ciencias informáticas. Así fue como me familiaricé con los siguientes lenguajes de programación:

1.  *Python*: Python es el lenguaje con el que estoy más familiarizado. En este lenguaje, nuestro profesor nos enseñó tanto las **bases** como usos más **avanzados**.  Con el vimos:  
    1. Manipulacion de bases de datos (archivos CSV)
    2. Manipulacion y codaje de numeros binarios
    3. Manipulacion de imagenes 
    4. Proyectos. El proyecto que mas disfrute hacer fue un contador de puntos de volleyball, con la extension de tKinter.  
     Este es el codigo (esta en frances porque yo daba clases en frances):
```python
from tkinter import *
from tkinter.messagebox import*

root = Tk() #creation de la racine
window = Canvas(root, width=1000, height=800) #creation de la fenetre
window.pack() #on met la fenetre au centre

#creation des lignes du design
#horizontales
window.create_line(150,100,850,100)#borde
window.create_line(150,450,850,450)#borde
#verticales
window.create_line(150,100,150,450)#borde
window.create_line(850,100,850,450)#borde
window.create_line(500,100,500,450)#net
window.create_line(499,100,499,450)
window.create_line(501,100,501,450)
window.create_line(383,100,383,450)#zona de atacantes
window.create_line(617,100,617,450)#zona de atacantes

#couleurs du desing
frame1 = Frame(window, width=232, height=349, bg="#34495E" ) #definition de la couleur
frame1.place(x= 151, y = 101) #placement de la couleur
frame2 = Frame(window, width=232, height=349, bg="#34495E" ) #definition de la couleur
frame2.place(x= 618, y = 101) #placement de la couleur
frame3 = Frame(window, width=116, height=349, bg="#1F618D" ) #definition de la couleur
frame3.place(x= 384, y = 101) #placement de la couleur
frame4 = Frame(window, width=115, height=349, bg="#1F618D" ) #definition de la couleur
frame4.place(x= 502, y = 101) #placement de la couleur

#creation des fonctions pour pouvoir mettre un nom pour les equipes
def enter1 (): #creation de la fonction pour le bouton 
    window.create_text(350,50, text=entryEquipe1.get(), font= "Impact 16")
    entryEquipe1.config(state='disabled')

window.create_text(370,709, text= "NOM DU LOCAL", font= "Impact 12")#creation du texte "nom du local"
entryEquipe1 = Entry()#creation de la boite pour mettre le texte
entryEquipe1.get()#recolte l'information qui a ete mise dans la boite
entryEquipe1.place(x=450,y=700)#placement de la boite d'informations
enter1 = Button(window, text = "ACCEPTER", command = enter1, font="Impact 10")#bouton pour accepter le nom
enter1.place(x=600,y=695)#placement du bouton 
#la meme chose que le premier equipe mais pour pouvoir mettre le deuxieme
def enter2 ():
    window.create_text(650,50, text=entryEquipe2.get(), font= "Impact 16")
    entryEquipe2.config(state='disabled')

window.create_text(370,759, text= "NOM DU VISITEUR", font= "Impact 12")
entryEquipe2 = Entry()
entryEquipe2.get()
entryEquipe2.place(x=450,y=750)
enter2 = Button(window, text = "ACCEPTER", command = enter2, font="Impact 10")
enter2.place(x=600,y=750)

#PONCTUATION
#CREATION DES VARIABLES
scoreEquipe1 = 0 #score
scoreEquipe2 = 0 #score
setEquipe1 = 0 #set
setEquipe2 = 0 #set
#CREATION DES LABELS POUR LES COMTER LE SCORE ET LES SETS
label_scoreEquipe1 = Label(window, text = scoreEquipe1, font="Impact 30")
label_scoreEquipe1.place(x=255, y=250)
label_scoreEquipe2 = Label(window, text = scoreEquipe2, font="Impact 30")
label_scoreEquipe2.place(x=715, y=250)
label_setEquipe1 = Label(window, text = setEquipe1, font="Impact 12")
label_setEquipe1.place(x = 350, y = 60)
label_setEquipe2 = Label(window, text = setEquipe2, font="Impact 12")
label_setEquipe2.place(x = 650, y = 60)

#FONCTION POUR COMTER LES POINTS ET LES SETS DE L'EQUIPE 1
def PT1():
    global scoreEquipe1
    global scoreEquipe2
    global setEquipe1
    global setEquipe2
    scoreEquipe1 += 1 #ajouter 1 point
    label_scoreEquipe1.config(text=scoreEquipe1) #"actualisation" des label
    if scoreEquipe1 >= 25 and scoreEquipe1 - scoreEquipe2 >= 2: #condition pour compter un set
        setEquipe1 += 1 #ajouter 1 point
        label_setEquipe1.config(text=setEquipe1) #"actualisation" des label
        showinfo("SET","L'EQUIPE LOCAL GAGNE LE SET") #anonce que l'equipe gagne le set
        scoreEquipe1 = 0 #remet les score a 0 mais avec un set pour l'equipe 1
        label_scoreEquipe1.config(text=scoreEquipe1) #"actualisation" des label
        scoreEquipe2 = 0 #remet les score a 0 
        label_scoreEquipe2.config(text=scoreEquipe2) #"actualisation" des label
        if setEquipe1 == 3: #condition pour gagner le match
            showinfo("JEU","L'EQUIPE LOCAL GANGE") #annonce que l'equipe 1 gagne
            setEquipe1 = 0 #remet les set a 0 
            label_setEquipe1.config(text=setEquipe1) #"actualisation" des label
            setEquipe2 = 0 #remet les set a 0 
            label_setEquipe2.config(text=setEquipe2) #"actualisation" des label

#FONCTION POUR COMTER LES POINTS ET LES SETS DE L'EQUIPE 2
#meme chose que pour l'equipe 1 mais les conditions sont faites pour l'equipe 2
def PT2():
    global scoreEquipe1
    global scoreEquipe2
    global setEquipe2
    scoreEquipe2 +=1
    label_scoreEquipe2.config(text=scoreEquipe2)
    if scoreEquipe2 >= 25 and scoreEquipe2 - scoreEquipe1 >= 2:
        setEquipe2 += 1
        label_setEquipe2.config(text=setEquipe2)
        showinfo("1 SET","L'EQUIPE VISITEUR A GAGNE LE SET")
        scoreEquipe2 = 0
        label_scoreEquipe2.config(text=scoreEquipe2)
        scoreEquipe1 = 0
        label_scoreEquipe1.config(text=scoreEquipe2)
    if setEquipe2 == 3:
        showinfo("JEU","L'EQUIPE VISITEUR GANGE")
        setEquipe2 = 0
        label_setEquipe2.config(text=setEquipe2)
        setEquipe1 = 0
        label_setEquipe1.config(text=setEquipe1)




pointEquipe1 = Button(window, text = "POINT POUR l'EQUIPE LOCAL", command = PT1, font = "Impact 10") #boutons pour les points de l'equipe 1
pointEquipe1.place(x = 200, y= 475) #placement du bouton 
pointEquipe2 = Button(window, text ="POINT POUR l'EQUIPE VISITEUR", command = PT2, font="Impact 10") #boutons pour les points de l'equipe 2
pointEquipe2.place(x = 650, y= 475) #placement du bouton


root.mainloop()
```

2. *HTML-CSS-JS*: También me adentré un poco en el mundo de la creación de páginas web.  
[Aqui dejo una pagina web que hice](html/introduction.html)


##  **2024 - Ingreso al grado de Ingeniería Informática**
En el presente, me encuentro estudiando el grado de ingeniería informática en la Universidad Europea del Atlántico, para seguir desarrollando mi conocimiento sobre el tema.

![Foto UEA](https://upload.wikimedia.org/wikipedia/commons/2/2c/Logo-uneatlantico.jpg)

















