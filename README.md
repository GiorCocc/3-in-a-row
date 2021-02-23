# 3-in-a-row
Secondo progetto del corso di Fondamenti di informatica e laboratorio di programmazione del corso di laurea in Ingegneria informatica, elettronica e delle telecomunicazioni dell'Università di Parma. \
Il gioco è basato su matrici. Le regole del gioco sono le seguenti:
1. Le celle bianche e le celle nere devono essere presenti nello stesso numero. Quindi, mezza matrice deve essere bianca e mezza nera
2. Non sono ammesse celle vuote (grige)
3. Non sono ammesse 3 celle dello stesso colore vicine

Il gioco prevede che l'utente selezioni la cella che vuole colorare cliccandola con il mouse e a ogni pressione il colore cambia secondo la sequenza grigio-bianco-nero-grigio etc. \
Per aggiare il gioco, aprire tutta la cartella nel prorpio ambiente di sviluppo e avviare il debug del file `three_in_a_row.py` e selezionare nella console la dimensione della matrice tra quelle disponibili (6x6, 8x8, 10x10, 12x12, 14x14) e giocare. 
Potrebbe essere necessario scaricare `pygame` se non è già presente nell'ambiente di sviluppo; in tal caso è possibile eseguire il debug del file `boardgamegui.py` per scaricarlo. \
**Le librerie `g2d.py`, `g2d_pyg.py`, `boardgame.py` e `boardgamegui.py` sono offerte dal docente [Michele Tomaiulo](https://github.com/tomamic)**

## Funzionalità aggiuntive
Con la pressione del tasto `a` sulla tastiera si ottiene il completamento di una cella alla volta della matrice di cui si sa già a priori di quale colore sarà seguendo le regole descritte sopra (è un aiuto per il giocatore). \
Con la pressione del tasto `u` sulla tastiera si controlla che le celle colorate rispettino le regole (vengono ignorate le celle grige, altrimenti ci sarebbe sempre un errore se si vuole l'aiuto durante l'esecuzione del gioco). \
Con la pressione del tasto `h` sulla tastiera si ottiene il completamento automatico della matrice, rispettando tutte le regole, utilizzando la tecnica del backtracking

# English 
Second project of the course of Fundamentals of computer science and programming laboratory of the degree course in Computer, Electronic and Telecommunications Engineering of the University of Parma. \
The game is based on matrices. The rules of the game are as follows:
1. White cells and black cells must be present in the same number. Hence, half matrix must be white and half black
2. Blank (gray) cells are not allowed
3. 3 neighboring cells of the same color are not allowed

The game requires the user to select the cell he wants to color by clicking on it with the mouse and at each press the color changes according to the gray-white-black-gray sequence etc. \
To update the game, open the whole folder in your development environment and start debugging the `three_in_a_row.py` file and select in the console the matrix size among those available (6x6, 8x8, 10x10, 12x12, 14x14) and play.
You may need to download `pygame` if it is not already present in the development environment; in that case you can debug the `boardgamegui.py` file to download it. \
**The libraries `g2d.py`,` g2d_pyg.py`, `boardgame.py` and `boardgamegui.py` are offered by the teacher [Michele Tomaiulo](https://github.com/tomamic)**

## Additional features
By pressing the `a` key on the keyboard you get the completion of one cell at a time of the matrix of which you already know in advance what color it will be following the rules described above (it is a help for the player). \
By pressing the `u` key on the keyboard you can check that the colored cells respect the rules (the gray cells are ignored, otherwise there would always be an error if you want help while playing the game). \
By pressing the `h` key on the keyboard you get the automatic completion of the matrix, respecting all the rules, using the backtracking technique
