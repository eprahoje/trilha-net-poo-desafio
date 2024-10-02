# 💻 Desafio de projeto - Trilha .NET - Programação Orientada a Objetos com C#

## Desafio de projeto
Para este desafio, usei seus conhecimentos adquiridos no módulo de orientação a objetos, da trilha .NET da [DIO](https://www.dio.me).

## 💼 Contexto
Sou responsável por modelar um sistema que trabalha com celulares. Para isso, foi solicitado que fizesse uma abstração de um celular e disponibilizasse maneiras de diferentes marcas e modelos terem seu próprio comportamento, possibilitando um maior reuso de código e usando a orientação a objetos.

## 📝 Proposta
Precisei criar um sistema em .NET, do tipo console, mapeando uma classe abstrata e classes específicas para dois tipos de celulares: Nokia e iPhone. 
Preciso criar as suas classes de acordo com o diagrama abaixo:

![Diagrama classes](Imagens/diagrama.png)

## 📑 Regras e validações
1. A classe **Smartphone** deve ser abstrata, não permitindo instanciar e servindo apenas como modelo.
2. A classe **Nokia** e **Iphone** devem ser classes filhas de Smartphone.
3. O método **InstalarAplicativo** deve ser sobrescrito na classe Nokia e iPhone, pois ambos possuem diferentes maneiras de instalar um aplicativo.

## ✅ Solução
Implementei a solução proposta pelo instrutor nas classes presentes no código, além de realizar os testes no arquivo Program.cs para com as classes Nokia e Iphone.