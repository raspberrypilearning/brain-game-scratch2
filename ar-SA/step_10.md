--- challenge ---
## التحدي: سباق حتى 10 نقاط
هل يمكنك تغيير لعبتك، بحيث يحاول اللاعب الإجابة عن 10 أسئلة إجابة صحيحة في أسرع وقت ممكن، بدلًا من الإجابة عن أكثر عدد ممكن من الأسئلة خلال 30 ثانية؟

لفعل ذلك، ستحتاج إلى تغيير التعليمة البرمجية للموقِّت. هل تعرف ما يحتاج إلى تغيير؟

```blocks
	عندما تستقبل [start v]
	اجعل [الساعة v] مساوياً (30)
	كرِّر حتى <(time) = [0]> 
	  انتظر (1) ثانية
	  غيِّر [الساعة v] بمقدار (-1)
	end
	بث [end v]
```




--- /challenge ---