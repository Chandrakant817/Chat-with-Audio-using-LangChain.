# Chat-with-Audio-using-LangChain.
Chat with Audio data using LangChain Framework.


## System Setup:
Step 1. Create a virtual environment
  > conda create -p myenv python=3.9 -y

step 2. Activate the environment:
  > conda activate myenv/

step 3. Install all the requirements:
  > pip install -r requirements.txt
 
step 4. start writing the code, with standard file name as main.py

## <b> Flow </b>
![image](https://github.com/Chandrakant817/Chat-with-PDF-using-LangChain/assets/69152112/40d04d29-5a66-4d49-9e85-e84dec172c3b)

### <b> High Level Architecture </b>
![image](https://github.com/Chandrakant817/Chat-with-Audio-using-LangChain./assets/69152112/19d4aca7-70d6-46e4-8171-6a365d1c50ee)

### <b> Steps: </b>
1. Upload the Audio File
2. Generate the text from the Audio
3. Store the text into another variable
3. Split content into Chunk
4. Do Embeddings of the data
Download embeddings from the OpenAI)
5. Store Data into Vector Store (eg: FAISS)
6. User can pass a Prompt
7. Based on User query, Similarity search will apply
8. Get the Output.

## <b> Input </b>
![image](https://github.com/Chandrakant817/Chat-with-Audio-using-LangChain./assets/69152112/bd7e200f-fb41-4310-a7ec-24959767ef52)

## <b> Output </b>
![image](https://github.com/Chandrakant817/Chat-with-Audio-using-LangChain./assets/69152112/394bc65f-7d15-4a11-90ca-3139e8981d42)



