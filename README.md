[POL]  Program, stworzony w Node-RED służący do wizualizacji danych z czujników Ela Innovation:

  - Blue PUCK RHT czujnik temperatury i wilgotności
  - Blue PUCK T EN12830 czujnik temperatury
  - Blue PUCK MAG czujnik magnetyczny
  - Blue PUCK MOV czujnik ruchu i drgań dla modelu MOV
  - Blue PUCK MOV czujnik ruchu i drgań dla modelu ANG

Dane odbierane przez MQTT są przetwarzane za pomocą węzłów funkcji i następnie wizualizowane w aplikacji node-red-dashboard.
Wizualizacja danych jest realizowana za pomocą wykresów, które umożliwiają użytkownikowi łatwe śledzenie i analizowanie trendów.
Aplikacja dashboard składa się ze strony głównej, gdzie znajdziemy dane z wszystkich 4 czujników oraz ze osobnych stron dla każdego z czujników.
Przez aplikacje można także moitorować status połączenia z MQTT oraz wyświetlać stan baterii czujników.
Całość tworzy rozbudowany system IoT, który może być używany do monitorowania i sterowania danymi z wielu źródeł w czasie rzeczywistym.


[ENG]  The program created in Node-RED serves to visualize data from Ela Innovation sensors:

  - Blue PUCK RHT temperature and humidity sensor
  - Blue PUCK T EN12830 temperature sensor
  - Blue PUCK MAG magnetic sensor
  - Blue PUCK MOV motion and vibration sensor for MOV model
  - Blue PUCK MOV motion and vibration sensor for ANG model

Data received via MQTT is processed using function nodes and then visualized in the node-red-dashboard application.
Data visualization is achieved through charts, allowing users to easily track and analyze trends.
The dashboard application consists of a main page displaying data from all four sensors, along with separate pages for each sensor.
Users can also monitor the MQTT connection status and view sensor battery levels through the application.
Overall, this comprises an advanced IoT system capable of monitoring and managing data from multiple sources in real-time.
