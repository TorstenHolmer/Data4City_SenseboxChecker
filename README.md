# Data4City_SenseboxChecker
Ein Livecode-Serverscript zur Aquise und Anzeige von Sensebox-Daten

Zeigt die Sensordaten von Senseboxen anhand der übergebenden BodIds an.
* Erkennung von Offline-Sensoren, die geraume Zeit keine Daten mehr gesendet haben (graue Hintergrundfarbe und Anzeige der Totzeit als Tooltip) 
* Erkennung von auffälligen Daten (unplausible, ausserhalb der bekannten Grenzen liegende Daten)
* Automatischer Refresh nach einer Minute (dadurch eignet sich das Script für das Monitoring der Boxen)

https://www.crowdlistener.com/data4city/boxsense.lc?BoxID=5d11e84030bde6001ace9bf9,5d15c00830bde6001ae7dacf,5d15b30630bde6001ae40be4,5d1b816230bde6001a943ea0,59dbae74b6d1250011e0b926,5abfa28b850005001b72a9b1,58d42511c877fb0011ad4597,594641e8a4ad5900111fd357,5bfdaffd3e34fc0019a6b5b1,5a25780037b73700109b5ba3,5cb0a764c9e9ab001ab3d3f9,58fcc8c15ba9e50011c238ee,5c3505412c80100019185c0b,5b3608231fef04001bfe5d63,5cf7d99407460b001b0b4144,5bab3c2b043f3f001b6c3fdc,5c1e02a1919bf8001a09cbbe,594c1567be7782001179f790,5c9bce49cbf9ae001aa3e52d,5bd70c202eee410019c60387,5ac9e0c7c4edec0019093bc3,5c24e267919bf8001a788f49
