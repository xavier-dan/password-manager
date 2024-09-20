# Gerenciador de Senhas  (Password Manager)
###
## Introdução
Esse é um projeto para gerenciar as senhas que criamos no cadastro de websites. O projeto foi desenvolvido durante a realização do ["The Complete Python Pro Bootcamp"](https://www.udemy.com/course/100-days-of-code/?couponCode=OF83024E).

![image](https://github.com/user-attachments/assets/1efd5569-95c7-4d93-a099-1af63fbfe24f)
## Principais tecnologias utilizadas
* **Python (v3.12)**
* **JSON**
* **Tkinter**

## Principais Funcionalidades
### Armazenamento de usuário/e-mail e senha
O usuário/e-mail e senha inseridos no programa serão armazenados em um arquivo `data.json`. 
As informações são facilmente legíveis ao abrir o arquivo.

![image](https://github.com/user-attachments/assets/f6435aba-b39f-45d0-81be-ccfa945bd9c5)

### Geração de senhas
O botão "Generate Password" é capaz de gerar uma senha considerada "Forte". A senha contém de 8 a 10 letras; de 2 a 4 números; e de 2 a 4 símbolos, em ordem aleatória. 
Ao clicar no botão para gerar a senha ela automaticamente será copiada, podendo ser colada no site de interesse do usuário. 

![image](https://github.com/user-attachments/assets/ba3a88f9-39bd-47ef-a92a-6dec1b889665)


### Procurar senhas
O botão "Search" irá procurar dentro do arquivo `data.json` o website digitado, mostrando ao usuário o e-mail e a senha que foram utilizados e já cadastrados no programa.

![image](https://github.com/user-attachments/assets/4f83e572-37bf-440e-8ce7-3790d81393a5)

Caso não tenha nenhum registro do website digitado, o programa irá sinalizar ao usuário. 

![image](https://github.com/user-attachments/assets/d7e99b71-64fc-4b0b-87cb-afda99bdf8ac)


