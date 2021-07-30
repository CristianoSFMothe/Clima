# ☁️ Clima


Projeto da B7Web de um site para informa o tempo, consumindo uma API do site [openWeather](openweathermap.org) para obter esses dados. No qual podemos obter algumas informações importantes.

## 🔑 Obtendo a API

Para obter acesso aos dados da API do **Open Weather**:
  - primeiramente é necessário fazer cadastro, 
  - depois de ter acesso, será necessário espera o tempo de aproximadamente 1 hora para ter o acesso,
  - depois no menu **API** acessar a documentação como na demostração abaixo
  

![Desmostração de obteção da API](https://github.com/CristianoDaSilvaFerreira/Clima/blob/main/obtendo-api.gif)
  
  - tento acessoa há mesmo, basta entrar no perfil da conta para obter a Key da API

~~~JavaScript
API
api.openweathermap.org/data/2.5/weather?q={city name}&appid={API key}
~~~

## 🆙 Transformando a API em um JSON

Depois de ter os dados da API vamos transforma essas informações em um **json** para ser melhor a forma de compreensão 

~~~ JavaScript
JavaScript
  document.querySelector('.temp img').setAttribute('src', `http://openweathermap.org/img/wn/${json.tempIcon}@2x.png`);
~~~


![image](https://user-images.githubusercontent.com/68359459/127707657-8c3e8c33-f3e2-4914-835b-57045b2981ba.png)

## 🎥 Vídeo demostrativo

Uma desmostração do funcionamento do site do clima

![vídeo demostrativo](https://github.com/CristianoDaSilvaFerreira/Clima/blob/main/clima.gif)


