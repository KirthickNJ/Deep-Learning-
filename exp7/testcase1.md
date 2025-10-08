#exp7 test case1
import pandas as pd
input_sentences = [
    "How are you?",
    "I love coding."
]
predicted_outputs = [
    "तुम कैसे हो?",
    "मुझे कोडिंग पसंद है।"
]
correct = ["Y", "Y"]
df = pd.DataFrame({
    "Input Sentence": input_sentences,
    "Predicted Output (Hindi)": predicted_outputs,
    "Correct (Y/N)": correct
})
print(df.to_string(index=False))
<img width="384" height="63" alt="Screenshot 2025-10-08 115521" src="https://github.com/user-attachments/assets/645dc30b-3445-48e0-aed3-7884d7a54d0b" />
