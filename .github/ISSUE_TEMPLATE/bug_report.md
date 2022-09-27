*Describe the bug*
A rota */login, no verbo **post*, possui documentação incompleta na API Serverest: 

- Quando é feito um requested no PostMan, deixando e-mail e password em branco, é retornada uma mensagem não documentada.

*To Reproduce*
Steps to reproduce the behavior:

Go to **'serverest.dev/login'**
Click on *'POST'*
Scroll down to '*Responses*' - Code 200 e Code 400
See error

*Expected behavior*
Quando verificar a documentação do Serverest, e estiver no verbo POST/*login, um novo code **400* deve ser documentado dizendo que e-mail e password são obrigatórios para realizar um login:

{
    "*email*": "email não pode ficar em branco",
    "*password*": "password não pode ficar em branco"
}

Screenshot of *'EXPECTED:*
![_produtos - My Workspace e mais 5 páginas - Trabalho — Microsoft​ Edge 27_09_2022 10_41_27 (2)](https://user-images.githubusercontent.com/106711311/192542880-e1f049ca-ed01-440c-92c1-e11bc908c1aa.png)

Screenshot of *'GOT':*

![image](https://user-images.githubusercontent.com/106711311/192544808-0197e263-fd01-458f-9a24-3d7cdde8d39e.png)

*Desktop (please complete the following information):*
 - OS: [e.g. Windows]
 -  Version [e.g. 21H2]
 - Browser [e.g. Microsoft Edge]
 - Version [e.g. 105.0]

*Additional context*
A adicional resposta do code 400 deve ser documentada na API Serverest para a melhoria da mesma, podendo dar responses mais completos para o desenvolvedor.
