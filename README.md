# MICROCONTROLLER-BASED-CURRENT-PROTECTION-CIRCUIT-WITH-WI-FI-MONITORING

Every circuit requires some kind of protection from the conditions such as overload and short 
circuit which occurs because of the overload on circuit or overcurrent flowing in a circuit. 
Over current or excess current is a condition where a larger than intended electric current 
exist. This leads to excessive generation of heat and risk of fire or damage to circuit. So in 
order to protect the circuit from these conditions we go for protection circuit which prevent 
both power supply and load from getting overloaded or short circuit.  
 
1 Overload 

 An overload condition occurs when there is an electric fault in a system that results in 
abnormally high amounts of current but far less than a short circuit.  In other words, 
an overload fault results in significantly reduced resistance, but resistance that also 
remains significantly above 0 – unlike a short circuit fault.

 Every electric circuit in a wiring system must be protected against overloads.  A 
circuit overload occurs when the amount of current flowing through the circuit 
exceeds the rating of a particular device. The amount of current flowing in a circuit is 
determined by the load for current. 

 For example, if a circuit is rated for 15 amps maximum, then a fuse or circuit breaker 
of that rating will be in that circuit. If the current exceeds 15 amps, the circuit breaker 
opens and cut off the current flow. Without the overload protection wires can get hot, 
or even melt the insulation and start a fire.

 There are two kinds of protection for electrical units that need to be considered 

1. The first is concerned with the protection of the actual electrical wires supplying 
the circuits against an overload above their carrying capacity

3. The second type is concerned with protecting the individual appliances and 
electrical equipment connected to a supply circuit from an overload.
 
 The effect of any overload is an increase in temperature of both load and power 
supply with a drastic reduction of its life time. With proper protection circuit we can 
prevent bad situations for power supply or loads and making them last long and 
efficient. 
                             
2 Short Circuit 

 A Short circuit is when a very low resistance path is created, causing enormous 
amount of current. For example, when a live wire touches a neutral wire, it creates a 
short circuit.

 When the human body is introduced as the path of least resistance, the current travels 
through the body. Short circuits can cause injury or death through electrical shock, 
electrocution, or fires. 

 More power is demanded during a short circuit, causing electrical arcs and extremely 
high temperatures that can melt plastics or set fire to flammable materials such as 
wood or fabrics. 

 As we know short circuit will damage power supply and the load or even creates 
a worse condition for the circuit if specific protection is not provided. This can occur 
due to improper design / connection of circuit or inadequate insulation in the circuit. 
 Due to the above determined effects of short-circuiting it is desirable and necessary 
to provide some kind of protection circuit.

Panal View

<img width="514" height="397" alt="image" src="https://github.com/user-attachments/assets/3ef833ac-9e9f-43f3-a3c6-82597f9290c5" />

Control Circuit

<img width="478" height="324" alt="image" src="https://github.com/user-attachments/assets/9c0ac4b1-455b-441a-8e46-abf3ae111e6d" />

<img width="682" height="866" alt="image" src="https://github.com/user-attachments/assets/f726459f-aa44-49a7-96ac-a3388333dbf8" />


 Flowchart 

<img width="471" height="857" alt="image" src="https://github.com/user-attachments/assets/df46d46f-65aa-4fce-97c0-85453c575438" />

 Working 
 
Current Protection Wi-Fi monitoring system is an integrated circuit which uses electronic 
based circuit for protection. It has a current sensor to determine the amount of current flowing 
through circuit. A microcontroller which communicate with the surrounding elements such as 
sensors, Relay, indicator, Node MCU, etc. The working of Circuit is simple and easy to 
understand.

Our protection circuit consists of two circuits one is power circuit and another one is control 
circuit. The Control circuit consists of Current sensor, Arduino UNO, Relay, Switch and a 
Node MCU. The power circuit consists of a Fuse, Relay contacts and a Load. 

When we give supply to the circuit the current starts flowing in the circuit the current sensor 
senses the amount of current flowing through the load and transfers the data collected from 
load to Microcontroller. Then Microcontroller calculate the received data in code, and if it 
found that the value is in normal operating current range then it will turn on Green indicator 
indicating normal condition. If Overload above normal range then it will turn on Orange 
Indicator indicating Overload condition. If it founds Short circuit condition then it will turn on 
Red indicator indicating Short circuit condition. 

The Circuit breaker in the circuit plays an important role to cut off the Load circuit from the 
input in case of Overload or Short circuit condition. 

After the fault is cleared we can reset circuit using a reset switch provided on panel. 

The data received from current sensor is transferred to cloud for monitoring and storing by 
NodeMCU which we can use to study the circuit to improve load sustainability by rectifying 
the causes before any breakdown of the equipment.

ThingSpeak Cloud Monitoring

<img width="573" height="391" alt="image" src="https://github.com/user-attachments/assets/5d4bbee8-5796-4002-ac2e-56080f5c292f" />



CONCLUSION 
 
I conclude that our Project "Microcontroller Based Current Protection with Wi-Fi 
Monitoring" will protect the equipment from overload current, short-circuit current under 
unsafe/ faulty conditions in any sector Industrial, commercial, domestic for both loads AC/DC 
supply. 

The microcontroller based current protection with a Wi-Fi monitoring system is easy to 
operate and use, and also protects the personnel from electrical shocks. The panel also gives 
visual indication of faulty condition and alarm sounds because of which the operators get 
alert. The panel also comes with interlocking technology which means without rectifying the 
fault the system will not give output. 

The wireless monitoring will help us to analyze the fluctuations in current and load graphs for 
modifying the design. This will improve the reliability and efficiency of the system. 
The microcontroller based current protection with a Wi-Fi monitoring system is integrated 
system which is one of the steps towards automation and smart monitoring which will be used 
in future circuit breakers for protection. 

