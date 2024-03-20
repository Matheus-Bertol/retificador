# Retificador:

Retificador feito para a aula de Sistemas Embarcados na aula do Prof. Rafael Barbosa na aula do dia 19/03

## Funcionamento de Retificador

Um retificador é um componente usado para converter corrente alternada para corrente contínua. Pode-se citar como exemplo um carregador de celular. 
O processo permite que dispositivos eletrônicos operem com uma fonte de energia estável e previsível, através da ponte retificadora, que "força" com que a corrente só passe através de uma direção.
 
- **Entrada de CA (J1)**: A corrente alternada entra no circuito.
- **Retificador de Ponte (BR1)**: Converte a CA em CC pulsante, sempre positiva.
- **Filtro de Capacitor (C1 - 1000uF)**: Suaviza a CC pulsante para diminuir as variações.
- **Regulador de Tensão (U1 - 7805)**: Estabiliza a tensão de saída em 5 volts.
- **Filtros Adicionais (C2 e C3 - 22nF)**: Removem ruídos de alta frequência.
- **Indicador de Saída (D1 - LED com R1 - 130Ω)**: Mostra se a tensão está presente.
Basicamente, o circuito transforma corrente alternada em corrente contínua estável, com um LED como indicador de funcionamento.

![image](https://github.com/Matheus-Bertol/retificador/assets/141282448/a389a264-14ff-4aa1-8802-5a88434e3ecc)
![image](https://github.com/Matheus-Bertol/retificador/assets/141282448/2ba4a286-ce01-414a-92a9-d435b57887e6)
![image](https://github.com/Matheus-Bertol/retificador/assets/141282448/b684e2cc-023d-43ac-9e8f-9c221495c87f)
