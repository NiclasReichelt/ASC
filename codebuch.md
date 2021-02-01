# Datensatz Semesterverbund CRPR2 #
Codebuch Stand 2021-02-01  

## Inhalt
- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.rm (Codierung der Datensätze)

## Ursprung und Datenerhebung
Erste Recherche. Weitere durch das Buch "Crusade for Justice"

## EDGE-Attribute

**weight**

Beziehungsstärke
Schwach (1) - Stark (3)

**relation**

Beziehungsart zwischen den Personen

1 = *Freunde*

2 = *Neutral*

3 = *Konflikt*

**year**

Jahr/Zeitraum der Begegnung bzw. des Kontaktes

**location**

Ort der Begegnung bzw. des Kontaktes

**Weitere im Laufe der Recherche**


## NODE-Attribute  
  
**id**

Kürzel des Knotens

**name**

Ausgeschriebener Name oder Bezeichnung des Knotens.

**sex**

dichotome Ausprägung:

1 = *male*

2 = *female*

**skincolor**

dichotome Ausprägung:

1 = *Schwarz*

2 = *Weiss*		

**member**

Mitglied bei best. (suffrage) Club:

1 = *ASC*

2 = *NACWC*

3 = *WCTU*

4 = *NAWSA*

5 = *NAACP*

--> Ausgebaut bei tieferer Recherche							

**power**

Machtstatus/ Einfluss:

1 = *kaum einflussreich*

2 = *einflussreich*

3 = *sehr einflussreich*			
  
**class**

Gesellschaftliche Herkunft: 

1 = *Arbeiter*

2 = *Bürgertum*

3 = *Oberschicht*
