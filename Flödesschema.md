# BoilerWeek39

Relation mellan frontend och backend:

Vi är inne på sidan https://users.premierleague.com/users/register/personal

Börjar i frontend: Frontend visar vart användaren ska skriva sina uppgifter för att registrera kontot, när användaren fyllt i alla fält klickar den på “Next”. 

Frontend skickar sedan den datan till backend med en HTTP POST-request, detta görs via API för att göra det enklare för frontend att hitta rätt i backend. 

Backend tar emot datan och validerar att det är ifyllt korrekt samt är säkert. Med säkert menas att det exempelvis inte innehåller några code-injections som kan skada backendstrukturen.  

Om den ifyllda informationen inte är ifylld korrekt eller ses som en säkerhetsrisk så skickas ett felmeddelande tillbaka till frontend och användaren får börja om från början. Om allt är ifyllt korrekt sparas datan i backend och sedan skickas ett bekräftelsemejl till den ifyllda e-postadressen samt att backend skickar tillbaka en HTTP respons till frontend.

När e-posten är verifierad och frontend tagit emot HTTP responsen så uppdateras sidan och användaren börjar nästa steg i registreringen. 

Visuell illustration av detta finns i bilden boilerroom.drawio.png.