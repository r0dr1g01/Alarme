# 🚨 Alarme com Arduino

Alarme utilizando Arduino.

## 📜 Como Funciona?  
1. **Inicialização**: O sistema inicia e apaga o **LED de energia**.  
2. **Modo Standby**: O alarme fica desativado até que o botão seja pressionado.  
3. **Ativação do Alarme**:  
   - 🔵 **LED acende** para indicar que o alarme está ligado.  
   - ⏳ Aguarda **3 segundos** antes de entrar no modo de monitoramento.  
4. **Monitoramento de Movimento**:  
   - Se **nenhum movimento** for detectado, o sistema continua monitorando.  
   - Se **movimento for detectado**, o estado muda para **PIR_DETECT**.  
5. **Alerta Sonoro**:  
   - 🔊 **O buzzer toca** com uma frequência que diminui gradualmente.  
   - Após o alerta, o sistema retorna ao **modo de monitoramento**.  
6. **O ciclo se repete** continuamente enquanto o alarme estiver ativado. 


![image](https://github.com/user-attachments/assets/03e28a82-9871-4c5b-aa9a-74f37bc9ec5e)

## 🔌 Esquema de Ligações  

| Componente        | Pino no Arduino |
|------------------|----------------|
| **LED de Status** (VCC) | 2  |
| **Botão de Ativação** (Sinal) | 3  |
| **Sensor PIR** (Sinal) | 4  |
| **Buzzer** (Sinal) | 5  |
| **GND Geral** | GND  |
| **Alimentação (5V)** | 5V  |


## 📂 Docs   
O código-fonte pode ser acessado aqui:  
</> [Código](docs/Código)  
 


## 🔗 Simulação no Tinkercad
[Acesse aqui a simulação no Tinkercad](https://www.tinkercad.com/things/8Uh4PAeMXhI-spectacular-kieran)

