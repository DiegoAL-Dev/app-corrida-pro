# App de Acompanhamento de Corrida
#### Funciona basicamente com o registro das atividades realizadas, por cada treino feito, onde tem a data da atividade, o km percorrido e o tempo realizado e o pace já é calculado automaticamente e tudo fica salvo dentro do próprio app. 

#### Autenticação de Usuários: O sistema possui uma tela inicial que permite a criação de contas e o login de usuários. Os dados e as credenciais são armazenados localmente no navegador (via ```localStorage```), garantindo que cada usuário tenha o seu próprio histórico isolado.


- Exemplo da logica para saber o pace percorrido.

```js
const dist = parseFloat(document.getElementById('distancia').value);
const tempo = parseFloat(document.getElementById('tempo').value);
const pace = tempo / dist;
```
