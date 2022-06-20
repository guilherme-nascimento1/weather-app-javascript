
# Weather App in JavaScript

Neste aplicativo, você pode obter os detalhes do clima de uma determinada cidade digitando o nome da cidade. Você também pode obter os detalhes do clima da sua localização atual clicando no botão "Obter localização do dispositivo". Você obterá muitos detalhes climáticos, incluindo temperatura em graus Celsius, condições climáticas, localização, sensação e umidade.

![App Screenshot](https://img.youtube.com/vi/c1r-NqYkFPc/maxresdefault.jpg);
 
## Usage

Cole sua chave de API no parâmetro appid dos URLs fornecidos. Esses URLs estão na linha 27 e 33 do arquivo script.js. Você pode obter uma chave de API [aqui](https://openweathermap.org/api).
```javascript
api = `https://api.openweathermap.org/data/2.5/weather?q=${city}&units=metric&appid=your_api_key`;
```
```javascript
api = `https://api.openweathermap.org/data/2.5/weather?lat=${latitude}&lon=${longitude}&units=metric&appid=your_api_key`;
```

## Related

Here are some related projects

[Get User Location in JavaScript](https://www.youtube.com/watch?v=J-lUOFXxG_0)

[Currency Converter in JavaScript](https://www.youtube.com/watch?v=UY7F37KHyI8)

[Create Todo List App in JavaScript](https://www.youtube.com/watch?v=2QIMUBilooc)

## Feedback


