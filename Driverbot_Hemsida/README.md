# Styrbasen

## Hur fungerar den?
Hemsidan har ett antal simpla funktioner som erbjuder tydlighet utan att frånta den komplexa kataktär som ingår i kontrollering av motorer via internet.
### Slider
Med hjälp av en slider kan användaren lätt ändra huruvida motorn i sin Driverbot snurrar i höger- eller vänstervarv samt ifall den stoppas. Detta då den genom tre lägen lägger till f(forward), s(stop) och b(backwards) i en string som sedan läggs upp i MQTT.
### Buttons
Genom knapparna kan användaren ändra hastigheten samt ifall Driverbot svänger åt höger eller vänster. Utöver det finns även en stopp-knapp ifall användaren tappar kontrollen över den där läget ändras till s(stop).

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
