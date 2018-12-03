## ग्राफिक्स जोड़ना

आपके कैरेक्टर द्वारा खिलाड़ी को केवल `हाँ! :)` या `नहीं :(` कहने के बजाय, चलिए कुछ ग्राफिक्स जोड़ते हैं, जो खिलाड़ी को उसकी प्रगति के बारे में बताएंगे।

+ 'परिणाम' नामक स्प्राइट बनाएँ, जिसमें 'टिक' और 'क्रॉस' पोशाक दोनों शामिल हों।

	![screenshot](images/brain-result.png)

+ अपने कैरेक्टर का कोड बदल दें, ताकि खिलाड़ी को उसकी प्रगति के बारे में बताने के बजाय, यह `सही`{:class="blockevents"} और `गलत`{:class="blockevents"} संदेश प्रसारित करे।

	![screenshot](images/brain-broadcast-answer.png)

+ अब आप इन संदेशों का उपयोग 'टिक' और 'क्रॉस' पोशाक दिखाने के लिए कर सकते हैं। इस कोड को अपनी नए 'परिणाम' स्प्राइट में जोड़ें:

	![screenshot](images/brain-show-answer.png)

+ अपनी गेम का पुनः परीक्षण करें। प्रश्न का सही उत्तर देने पर आपको टिक, और गलत उत्तर के समय क्रॉस दिखाई देगा!

	![screenshot](images/brain-test-answer.png)

+ क्या आपने ध्यान दिया कि `जब मुझे [सही] मिले`{:class="blockevents"} और `जब मुझे [गलत] मिले`{:class="blockevents"} के कोड काफी हद तक समान हैं? चलिए आपको अपने कोड में परिवर्तन करना सरल बनाने के लिए फ़ंक्शन बनाते हैं।

	अपनी 'परिणाम' स्प्राइट पर, `अधिक ब्लॉक`{:class="blockmoreblocks"}, और फिर 'ब्लॉक बनाएँ' पर क्लिक करें। `एनिमेट`{:class="blockmoreblocks"} नामक नया फंक्शन बनाएँ।

	![screenshot](images/brain-animate-function.png)

+ फिर आप अपने नए एनिमेशन फ़ंक्शन में एनिमेशन कोड जोड़ सकते हैं, और फिर बस फंक्शन का दो बार उपयोग कर सकते हैं:

	![screenshot](images/brain-use-function.png)

+ अब, यदि आप कम या अधिक समय के लिए टिक और क्रॉस दिखाना चाहते हैं, तो आपको अपने कोड में केवल बदलाव करना होगा। इस आज़माएँ!

+ टिक और क्रॉस को दिखाने और छिपाने की बजाय, आप अपने एनिमेशन फ़ंक्शन को बदल सकते हैं, ताकि ग्राफिक्स फेड इन हो जाएँ।

	```blocks
		स्पष्ट अर्थ बताइए (animate)
		[ghost v] प्रभाव (100) में सेट करे
		दिखाएं
		(25) बार दोहराएं 
		  [ghost v] से (-4) प्रभाव बदले
		end
		छुपाएँ
	```


