Sistema de Heróis
Este projeto simula a criação de heróis com diferentes tipos e habilidades de ataque, usando a programação orientada a objetos em JavaScript. O código define uma classe Heroi, que permite criar instâncias de heróis com atributos como nome, idade e tipo. Dependendo do tipo de herói, o ataque será definido de forma diferente.

Estrutura do Código
1. Classe Heroi
A classe Heroi possui:

Atributos:

nome: o nome do herói.
idade: a idade do herói.
tipo: o tipo de herói, que pode ser 'mago', 'guerreiro', 'monge' ou 'ninja'.
Métodos:

atacar(): Simula um ataque do herói, chamando o método definirAtaque() para determinar o tipo de ataque baseado no tipo de herói.
definirAtaque(): Retorna o tipo de ataque específico para cada herói, com base no seu tipo. Se o tipo não for reconhecido, retorna um ataque genérico.
2. Instanciação e Uso
São criados quatro heróis com diferentes tipos de ataques:

Mago: Usa magia.
Guerreiro: Usa espada.
Monge: Usa artes marciais.
Ninja: Usa shuriken.
Os heróis podem realizar ataques, e o tipo de ataque é determinado pela função definirAtaque().
