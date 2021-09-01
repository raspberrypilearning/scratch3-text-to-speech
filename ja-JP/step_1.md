**ピコとギガはスピーチ拡張機能で話します**： [内部を参照](https://scratch.mit.edu/projects/499373708/editor){：target = "_ blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499373708/?autostart=false" frameborder="0"></iframe>
</div>

**拡張機能を追加**：をクリックします。

![「拡張機能を追加」アイコン。](images/add-extension.png)

**音声合成**を選択します。

![「音声合成」拡張機能が強調表示されます。](images/text-to-speech.png)

新しい `音声合成`{：class = "block3extensions"}ブロックメニューが表示されます。

![「音声合成」ブロックメニュー。](images/text-to-speech-blocks.png)

`音声合成`{：class = "block3extensions"}ブロックメニューのブロックを使用して、スプライトに話をさせることができます。

クリックすると、スプライトが声を出して話をします。

```blocks3
when this sprite clicked
set voice to (alto v) :: tts
set language to (Spanish v) :: tts
speak [Hola] :: tts
```

スプライトに子猫の声を出させることもできます！

```blocks3
set voice to (kitten v) :: tts
speak [Cat gotta haz milk.] :: tts
```
