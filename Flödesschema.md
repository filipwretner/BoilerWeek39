# BoilerWeek39

Relation mellan frontend och backend:

Vi är inne på sidan https://users.premierleague.com/users/register/personal

Börjar i frontend: Frontend visar vart användaren ska skriva sina uppgifter för att registrera kontot, när användaren fyllt i alla fält klickar den på “Next”. 

Frontend skickar sedan den datan till backend med en HTTP POST-request. 

Backend tar emot datan och validerar att det är ifyllt korrekt samt är säkert. 

Om den ifyllda informationen inte är ifylld korrekt eller ses som en säkerhetsrisk så skickas ett felmeddelande tillbaka till frontend och användaren får börja om från början. Om allt är ifyllt korrekt sparas datan i backend och sedan skickas ett bekräftelsemejl till den ifyllda e-postadressen samt att backend skickar tillbaka en HTTP respons till frontend.

När e-posten är verifierad och frontend tagit emot HTTP responsen så uppdateras sidan och användaren börjar nästa steg i registreringen. 

Visuell illustration av detta finns i bilder boilerroom.drawio.png.

Gruppresentation, alla ska delta i presentationen:
Varje grupp ska presentera sin webbapplikation och reflektera över sin agila process och gruppdynamik.
Presentationen bör inkludera:
Demonstration av applikationen med fokus på responsiv design och moderna CSS-tekniker.
Beskrivning av den agila processen, inklusive hur ni planerade och genomförde projektet.
Reflektion över gruppdynamik, vad som fungerade bra och vad som kan förbättras.
Presentationslängd: Varje grupp har max 15 minuter för sin presentation.