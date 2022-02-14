# Codebuch #

## EDGE-Attribute

**id**  
(eindeutige Codierung des Knoten)   
codiert von 1 bis xx, jede ID entspricht PolitikerInnen oder einer politischen Institution (siehe Nodeattribute)

**from**    
initiierender Knoten, in diesem Fall: PolitikerIn

**to**   
Zielknoten, in diesem Fall: Unternehmen, Orte, Verbände, Institutionen usw.




**relationship**  
Beziehungssart (xxx)

1 = Ministerium/ Staatssekretär    
2 = politische Funktionen     
3 = Ehrenamt		    
4 = Unternehmen und Aufsichtsräte        
5 = Stipendien	         
6 = Berufstätigkeiten	             
7 = Studien- bzw. längere Aufenthalte in In- und Ausland.




*Codebuch Relationship:*

1 = Achtung: Regierung umfasst auch Staatsekretäre und das Bundeskanzleramt, etc. hier sollte als Knoten das entsprechende Ministerium angegeben werden.       

2 = aktuelle und ehemalige politische Funktionen in politischen Ausschüssen, Gremien und der Partei. etc. Das können auch frühere Stationen gewesen sein, z.B. Geschäftsführer:in einer Partei, etc.

3 = umfasst alle Mitgliedschaften in NGOs, Stiftungen, Gedenkstätten, etc: werden im Bundestagsprofil als Körperschaften öffentlichen Rechts bezeichnet.

4 = Beteiligung an Unternehmen durch Mandate, etwa Aufsichtsratsmandate, Gremien, etc.

5 = erhalten Stipendien (egal wann), etwa Deutsche Studienstiftung, Parteinahe Stiftungen, Internationale Organisationen im In- und Ausland etc.

6 = ausgeübte Berufstätigkeiten, falls vorhanden

7 = Studien- bzw. (längere) Aufenthaltsort(e) in In- und Ausland


**Jahr der Erhebung**    
(Bezieht sich auf das Jahr, in dem die Variable relationship erhoben wurde)





# NODE-Attribute  
  
**id**  
Identische ID wie aus der edgelist zur Identifikation der Knoten. 


**type**   
Knotentyp 

0 = Person   
1 = Institution, Ort, Verband

**name**      
numerische ID

**name_short**     
Vorname abgekürzt, z.B. für Visualiserung, falls der Name zu lange ist

**sex**    
(Geschlecht)   
1 = weiblich  
2 = männlich  
3 = divers

**birth**    
Geburtsjahr eintragen


**religion**   
(Religionszugehörigkeit)      
1 = römisch-katholisch   
2 = protestantisch   
3 = islamisch    



**education**    
(höchster Bildungsabschluss)    
1 = mittlere Reife   
2 = Fachhochschulreife   
3 = Abitur    
4 = Fachhochschulabschluss  
5 = universitärer Abschluss   
6 = Promotion   
7 = abgeschlossene Berufsausbildung    



**subject**   
(Fachrichtung bei Studium/Promotion)   
1 = Politikwissenschaften   
2 = Jura     
3 = BWL    
4 = Medien, Werbung, Marketing, PR  
5 = Soziales     
6 = Beamtentum (Verwaltung)   
   



**position**       
(jetzige Position)   
1 = MinisterIn    
2 = ParlamentarischeR StaatssekretärIn  


**party**     
(Parteizugehörigkeit)   
S = SPD   
G = Grüne    
F = FDP     
    



**kids**     
Anzahl der Kinder eintragen


**twitter**   
Anzahl der FollowerInnen eintragen


**instagram**   
Anzahl FollowerInnen eintragen


**facebook**   
Anzahl FollowerInnen eintragen


**youtube**   
Anzahl AbonenntInnen eintragen


