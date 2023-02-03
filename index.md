---
title: Home
layout: home
---

# What is PlusGPT?
At PlusGPT, our mission is to promote AI adoption by offering tailored APIs and custom fine-tuning services. We aim to make it easier for businesses to join the AI race by providing end-to-end AI applications. 

# Fitness Advisor DEMO
```python
import requests

headers = {
    "Authorization": """bearer YOUR_API_KEY""",
    "Content-Type": "application/json"
}

data = {
    "api_token": "YOUR_API_TOKEN",
    "prompt": "How to loose weight while gain muscle mass"
}

response = requests.post("{ YOUR_CUSTOM_API_END_POINT }", headers=headers, json=data, timeout=70)
print(response.json().get("choices")[0].get("text"))

# >> ## Example Output ##
# If you want to lose weight while gaining muscle mass, it's important to focus on your diet and exercise routine. To reach your goals, you'll need to create a calorie deficit, meaning that you consume fewer calories than you expend. To do this, you should combine healthy eating with a regular exercise routine that includes both resistance (weight) training and aerobic (cardio) exercises. 
# Resistance training is important for gaining muscle mass. It helps create a stimulus for your muscles to grow and helps you burn calories and fat. To lose weight while building muscle, you should focus on compound exercises, such as squats, deadlifts, and bench press. Aim to do three to four sets of eight to twelve repetitions of each exercise with a weight that is challenging enough to fatigue your muscles.
# Along with resistance training, you should also incorporate aerobic exercise into your routine. Cardio exercises such as running, cycling, swimming, and walking can help you burn calories and build muscle. Aim to do at least 30 minutes of cardio exercises three to four times a week.
# Your nutrition is also important when trying to lose weight and gain muscle mass. Eating enough protein is essential for muscle growth and repair. Aim for 1.2 to 2.0 grams of protein per kilogram of body weight each day. Additionally, make sure to get enough healthy fats and carbohydrates to fuel your workouts and help your body recover.
# Finally, it's important to get enough rest and recovery. Your body needs time to repair and rebuild muscle after resistance training. Aim for at least seven to nine hours of sleep per night and make sure to take breaks between workouts.
# By creating a calorie deficit through healthy eating and combining resistance and aerobic exercises, you can lose weight while gaining muscle mass.
```
Contact sales@plusgpt.app to get your custom use-case API endpoint!

----

[OpenAI]:https://openai.com/
[Hugging Face]:https://huggingface.co/
[Liner.ai]:https://liner.ai/
