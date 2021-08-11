**حديث بيكو وجيجا مع ملحق الكلام**: [انظر في الداخل](https://scratch.mit.edu/projects/559753694/editor){:target="_blank"}

<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/559753694/?autostart=false" frameborder="0"></iframe>
</div>

انقر على **ادراج اضافة**:

![رمز "إضافة ملحق".](images/add-extension.png)

اختر **نص الى كلام**:

![تمييز ملحق "نص إلى كلام".](images/text-to-speech.png)

ستحصل على قائمة كتل `نص الى كلام`{:class="block3extensions"} جديدة:

![قائمة كتل "نص إلى كلام".](images/text-to-speech-blocks.png)

يمكنك استخدام الكتل الموجودة في قائمة الكتل `نص الى كلام`{:class="block3extensions"} لجعل الكائنات تتحدث بصوت عالٍ.

يمكنك جعل كائن ما يتحدث بصوت عالٍ عند النقر عليه:

```blocks3
when this sprite clicked
set voice to (alto v) :: tts
set language to (Arabic v) :: tts
speak [مرحباً] :: tts
```

يمكنك حتى أن تعطي كائنك صوت قطة!

```blocks3
set voice to (kitten v) :: tts
speak [القطة يجب ان تحصل على حليب.] :: tts
```
