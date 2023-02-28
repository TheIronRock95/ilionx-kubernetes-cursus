# ilionx-webapp-example

Maak een Dockerfile in deze map die de volgende image creert:
- Gebruik als basis de image 'python:3.6-alpine'
- Installeer de 'Flask' Python module
- Plaats de data uit de map 'application' op de /app locatie in de container
- Zorg ervoor dat poort 8080 van de container bereikbaar wordt gemaakt
- Configureer als werklocatie '/app'
- Specificeer als container executable: 'python main.py'

Geef deze container de naam 'ilionx-webapp-example'