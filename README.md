Dette IoT-prosjektet går ut på å lage en Smart City løsning på liten skala. Vi har satt det 
sammen ved å dele prosjektet opp i ulike moduler. Vi benyttet oss av en Zumo32U4 
belterobot. Zumo’en blir programmert gjennom Arduino-IDE til å utføre en rekke 
oppgaver. Den har også mulighet til kommunikasjon gjennom en ESP-32 som er 
montert på toppen av Zumo’en. 
Hovedoppgaven til Zumo-roboten er at den skal ha mulighet til å følge en linje, samt 
utføre utfordringer langs denne linjen. I tillegg har den et software-basert batteri, som 
tømmer seg mens bilen kjører. Når dette batteriet faller under 20% eller en bruker 
forespør opplading skal bilen automatisk følge teipen til den kommer til ladestasjonen
som skal simulere at batteriet blir ladet. Alle modulene er sammenkoblet gjennom 
Node-RED og MQTT, og data blir vist på et brukergrensesnitt.
