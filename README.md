
# Weather App in JavaScript

Neste aplicativo, você pode obter os detalhes do clima de uma determinada cidade digitando o nome da cidade. Você também pode obter os detalhes do clima da sua localização atual clicando no botão "Obter localização do dispositivo". Você obterá muitos detalhes climáticos, incluindo temperatura em graus Celsius, condições climáticas, localização, sensação e umidade.
 
## Modo de Usar

Cole sua chave de API no parâmetro appid dos URLs fornecidos. Esses URLs estão na linha 12 e 15 do arquivo script.js. Você pode obter uma chave de API [aqui](https://openweathermap.org/api).
```javascript
api = `https://api.openweathermap.org/data/2.5/weather?q=${city}&units=metric&appid=your_api_key`;
```
```javascript
api = `https://api.openweathermap.org/data/2.5/weather?lat=${latitude}&lon=${longitude}&units=metric&appid=your_api_key`;
```



