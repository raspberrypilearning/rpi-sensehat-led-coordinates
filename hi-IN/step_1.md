Sense HAT का LED मैट्रिक्स x- और y- एक्सिस के साथ एक निर्देशांक(coordinate) प्रणाली का उपयोग करता है। दोनों एक्सेस की संख्या शीर्ष बाएं हाथ के कोने में `0` (1 नहीं) से शुरू होती है। प्रत्येक LED को एक छवि के एक पिक्सेल (pixel) के रूप में इस्तेमाल किया जा सकता है, और इसे `x, y` संकेतन का उपयोग करके संबोधित किया जा सकता है।

![निर्देशांक(Coordinates)](images/coordinates.png)

नीला पिक्सेल (pixel) `0, 2` निर्देशांक (coordinates) पर है । लाल पिक्सेल (pixel) `7, 4` निर्देशांक (coordinates) पर है ।

आप `set_pixel ()` विधि का उपयोग करके अलग-अलग पिक्सेल (pixel) (LEDs) सेट कर सकते हैं।

ऊपर दिए गए चित्र को दोहराने के लिए, आप इस तरह के एक कार्यक्रम में प्रवेश करेंगे: <iframe src="https://trinket.io/embed/python/c57565feac" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>
