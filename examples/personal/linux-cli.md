#q- how to optimize linux cmd? 
for the cmd "ag -g $2 $promptpath", if I have multi-path in "promptpath" and splitted by ';', how shall I update the code? please update the original code but not change other functions.

#q- how to create offline llm CLI? 
1. Download [ollama-api-man](https://github.com/ollama/ollama/blob/main/docs/api.md)
2. Upload to gpt4, and ask following question: 
```
review the official ollama api documentation and write a python script that utilizes this api to analyze an image.
make above code like CLI, support -h, -f (filepath), -q (question)
update above code that contains a default question prompt
update aboce code that starts interact mode if no -q
```

#q- how to optimize offline llm CLI? 
read this code. Now if the file is TXT, I want to directly use ollama (rather than using RAG / vector db) to read it (if too long, cut into multiple slices with some prompt to continue reading)
change the prompt --- I need to combine the content before asking question (if TXT too long)
can I switch to interactive model while keep using previous chat history (after continue reading TXT)?



