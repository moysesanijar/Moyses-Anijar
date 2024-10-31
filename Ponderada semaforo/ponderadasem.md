# Moyses-Anijar

### Tabela de Avaliação entre Pares
#### Avaliador: Leonardo Martins
|Critério|	Contempla (3 Pontos)|	Contempla Parcialmente (1,5 Pontos)	|Não Contempla (0 Pontos)	|Observações do Avaliador|
|-|-|-|-|-|
|Montagem física com cores corretas, boa disposição dos fios e uso adequado de resistores	|X	|-	|- | 3 |	
|Temporização adequada conforme tempos medidos com auxílio de algum instrumento externo	|X| - | - |	3 |
|Código implementa corretamente as fases do semáforo e estrutura do código (variáveis representativas e comentários) |X| - | - | 3|	
|Ir além: Implementou um componente de extra, fez com millis() ao invés do delay() e/ou usou ponteiros no código |	X | - |	- |1 | 
| | | | |Pontuação Total: 10|

### Código

const int ledVermelho = 8;
const int ledAmarelo = 9;
const int ledVerde = 7;

void setup() {
  pinMode(ledVermelho, OUTPUT);
  pinMode(ledAmarelo, OUTPUT);
  pinMode(ledVerde, OUTPUT);
}

void loop() {
  digitalWrite(ledVermelho, HIGH);
  digitalWrite(ledAmarelo, LOW);
  digitalWrite(ledVerde, LOW);
  delay(6000);

  digitalWrite(ledVermelho, LOW);
  digitalWrite(ledAmarelo, HIGH);
  digitalWrite(ledVerde, LOW);
  delay(2000);

  digitalWrite(ledVermelho, LOW);
  digitalWrite(ledAmarelo, LOW);
  digitalWrite(ledVerde, HIGH);
  delay(2000);

  digitalWrite(ledVerde, HIGH);
  delay(2000);

  digitalWrite(ledVermelho, LOW);
  digitalWrite(ledAmarelo, HIGH);
  digitalWrite(ledVerde, LOW);
  delay(2000);
}
______________________________________________

Video: https://drive.google.com/file/d/1Gqx5M39N0clYIhlhl5xsGZkkPE04q5S4/view?usp=sharing
