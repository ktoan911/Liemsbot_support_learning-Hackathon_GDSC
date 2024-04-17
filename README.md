# LiemsBot - Chatbot Supporting Learning Hust
Authors:
- Github: [ktoan911](https://github.com/ktoan911) 
- Email: khanhtoan.forwork@gmail.com 


<iframe width="560" height="315" src="https://www.youtube.com/watch?v=xKN8LjJHfx0" frameborder="0" allowfullscreen></iframe>


This project, Liemsbot - Chatbot supporting learning, is built based on the prompt-based fine-tuning approach using the large language model Llama2. The chatbot is capable of answering questions related to general subjects at the university level, assisting students in obtaining quick and accurate explanations for their inquiries.




## I.  Run project
- Step 1: Download ollama from link: https://ollama.com/

- Step 2: Clone and Navigate to Repository Directory
```
git clone <repository_url>
cd {repository_directory_name}
```

- Step 3: Setup model chatbot using ollama

```
ollama create {name of chatbot} -f ./model.txt
``` 
- Step 4: Using Gradio to create a chatbot interface.

```
python main.py --model {name of chatbot}
``` 

![Image](.\assets\image.png)

