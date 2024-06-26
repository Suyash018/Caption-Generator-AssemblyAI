
# Caption Generator

It generates .SRT for an mp3 audio using  [ASSEMBLY AI](https://www.assemblyai.com/)

## API KEY

Sign up at [https://www.assemblyai.com/](https://www.assemblyai.com/)

You will find your API Key here

![image](https://github.com/Suyash018/Caption-Generator-AssemblyAI/assets/73903830/4ff6ca0a-a40a-4559-94b1-8ab5cf045db2)



## Installation

Download the ipynb file or Go to Colab and import the file

In the first cell 

Add your API key here 
```bash
  aai.settings.api_key = "YOUR_API_KEY" 
```
In the Second cell 

Change your Audio file
```bash
  transcript = transcriber.transcribe("audio.mp3"
                                    ,config=config)  
```


### In the No Char / word limit below code 

- You will get long srt which might block the screen

![image](https://github.com/Suyash018/Caption-Generator-AssemblyAI/assets/73903830/c68ce043-cdc7-4a61-9ceb-4b7475d0797b)


### In the 10 Word limit below code 

- It will limit the words shown on Screen 
- Preferably it should not be more than 13

change the word limit here
```bash
  wordLimit=10 
```

![image](https://github.com/Suyash018/Caption-Generator-AssemblyAI/assets/73903830/7eaa3e0e-5382-465d-8eff-5ff6e7de6ab7)


### In the Word Level For Reels/ Youtube Shorts below code 

- It will give you a single word mostly used in Reels/TikTok/YT shorts

![image](https://github.com/Suyash018/Caption-Generator-AssemblyAI/assets/73903830/f92d3722-0a8a-4e8a-9475-c2bb69c43b03)

