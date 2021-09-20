**Pico e Giga falam com a extensão Fala**: [Ver interior](https://scratch.mit.edu/projects/499373708/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499373708/?autostart=false" frameborder="0"></iframe>
</div>

Clique em **Adicionar Extensão**:

![Ícone 'Adicionar Extensão'.](images/add-extension.png)

Escolha **Texto para Fala**:

![Extensão 'Texto para fala' em destaque.](images/text-to-speech.png)

Você obterá um novo menu de blocos `Texto para Fala`{:class="block3extensions"}:

![Blocos de menu 'Texto para Fala'.](images/text-to-speech-blocks.png)

Você pode usar os blocos dentro do blocos de menu `Texto para Fala`{:class="block3extensions"} para fazer os seus atores falarem em voz alta.

Você pode fazer um ator falar em voz alta quando clicado:

```blocks3
when this sprite clicked
set voice to (alto v) :: tts
set language to (Spanish v) :: tts
speak [Hola] :: tts
```

Você pode até mesmo fazer o seu ator falar com uma voz de gatinho!

```blocks3
set voice to (kitten v) :: tts
speak [Cat gotta haz milk.] :: tts
```
