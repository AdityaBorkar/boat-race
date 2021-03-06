## الاصطدام

--- task ---

قم الآن بإضافة عبارة `if`إلى الرمز البرمجي الخاص بقاربك بحيث يربح اللاعب عندما يجعل القارب يصل إلى الجزيرة الصفراء.

عندما يصل القارب إلى الجزيرة، يجب أن تقول اللعبة 'نعم!'، ومن ثم يجب أن تنتهي.

--- hints ---
 --- hint ---

تحتاج إلى إضافة المزيد من كتل التعليمات البرمجية داخل حلقة `للأبد`{:class="block3control"} بحيث تستمر التعليمة البرمجية الخاص بك في التحقق مما إذا كان اللاعب قد فاز:

`if`{:class="block3control"} يكون القارب `لمس`{:class="block3sensing"} لون الجزيرة، تحتاج إلى `قول "نعم! لمدة 2 ثواني`{:class="block3looks"} ثم `إيقاف كل شيء`{:class="block3control"} لإنهاء اللعبة.

--- /hint --- --- hint ---

فيما يلي التعليمة البرمجية التي تحتاجها:

![كائن القارب](images/boat_resize.png)

```blocks3
say [نعم!] for (2) seconds

if <touching color [#FFFF99] ?> then
end

stop [all v]

```

--- /hint --- --- hint ---

هذا ما يجب أن يبدو البرنامج عليه:

![كائن القارب](images/boat_resize.png)

```blocks3
if <touching color [#FFFF99] ?> then
say [نعم!] for (2) seconds
stop [all v]
end
```

لا تنسى أن هذه التعليمات البرمجية الجديدة يجب أن تكون داخل حلقة `للأبد`{:class="block3control"}.

--- /hint ------ /hints --- --- /task ---