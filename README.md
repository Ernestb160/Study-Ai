# Study-Ai
Study-Ai is a locally hosted AI to help you prepare for whatever you need


Hi. This is my first time working with AI, especially within coding. What I found out really quickly is that this is something that is very simple and fun to learn, but also build.

Because a ton of people have finals coming up soon (me included), I decided to create Study-AI. Because it's locally hosted, there are an infinite amount of credits. The only bottleneck to the program is your computer.

This program is made using llama3.2:1b.

---

## Setup

To set this whole thing up, you need to do a couple things first.

1. Download Ollama for your system [here](https://ollama.com/download)

2. Open this project inside Visual Studio Code or whatever you choose, then run:
   ```
   ollama pull llama3.2:1b
   ```

3. Install the requirements for the project by running:
   ```
   pip install -r requirements.txt
   ```

4. Make sure Ollama is running

5. To use the program run:
   ```
   python main.py
   ```

6. To exit, type `exit`

---

## Advanced Mode

If you have a good computer, instead of running `main.py`, run:

```
python studyaiadvanced.py
```

Make sure you run the following in the terminal to install the better model:

```
ollama pull llama3.2:3b
```
