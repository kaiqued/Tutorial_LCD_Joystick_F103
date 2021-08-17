Autor: [Kaique Dognani](https://github.com/kaiqued)
# Tutorial LCD Joystick na F103

# Objetivo
  Primeiros passos com o LCD e o Joystick utilizando a NUCLEO F103RB como microcontrolador.
  
# Materiais
* NUCLEO F103RB
* Display LCD 16X2
* Joystick
* Compilador [Mbed](https://ide.mbed.com/)

# Primeiros passos
  Para iniciar primeiro entre no link de [exemplo](https://os.mbed.com/users/kaiquedog/code/LCD_JOYSTICK/) e clique no botão para importar este código no seu compiler:
  
  ![image](https://user-images.githubusercontent.com/26482377/129739791-b8eb0141-6a6d-4165-a8ff-5e17bed2d5c4.png)
  
# Introdução do código e explicações
  Esta pasta contém duas bibliotecas, uma para o Joystick e outra para o LCD. A biblioteca do Joystick simplifica a leitura dos potenciômetros. A biblioteca do LCD facilita a   comunicação entre o LCD e a F103.
  
## Funções Joystick
  Na biblioteca do Joystick temos três funções principais:
  * ler_x() --> Retorna 1 ou 0 dependendo da direção acionada, retorna 2 caso não seja acionado
  * ler_y() --> Retorna 1 ou 0 dependendo da direção acionada, retorna 2 caso não seja acionado
  * bot_select() --> Retorna 1 se o botão for apertado e 0 se o botão estiver desapertado
  
