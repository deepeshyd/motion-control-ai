# Motion Control AI (Like Kling 2.6 Pro)

यह एक साधारण AI है जो एक इमेज को रेफरेंस वीडियो से मोशन देता है, रियलिस्टिक और स्मूथ एनीमेशन के लिए। व्यक्तिगत उपयोग के लिए बनाया गया, CPU पर रन होता है।

## फीचर्स
- इमेज को वीडियो से एनीमेट करें।
- मोशन कंट्रोल: रेफरेंस वीडियो का इस्तेमाल।
- UI: Gradio के साथ आसान इंटरफेस।

## इंस्टॉलेशन
1. Python 3.8+ इंस्टॉल करें।
2. रिपोजिटरी क्लोन करें: `git clone https://github.com/yourusername/motion-control-ai.git`
3. वर्चुअल एनवायरनमेंट: `python -m venv env` और `env\Scripts\activate` (Windows)।
4. डिपेंडेंसी इंस्टॉल: `pip install -r requirements.txt`
5. रन करें: `python animate_image.py`

## यूजेज
- Gradio UI खुलेगा – इमेज और वीडियो अपलोड करें, प्रॉम्प्ट दें, और एनीमेटेड वीडियो पाएं।
- नोट: CPU पर धीमा है, GPU के लिए Colab इस्तेमाल करें।

## डिपेंडेंसी
- PyTorch, Diffusers, OpenCV, Gradio, आदि।

## लिंक्स
- [AnimateDiff GitHub](https://github.com/guoyww/AnimateDiff)
- [Hugging Face Models](https://huggingface.co/)

## कंट्रीब्यूशन
फोर्क करें और PR भेजें! व्यक्तिगत उपयोग के लिए लाइसेंस: MIT।
