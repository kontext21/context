Welcome! This is a curated collection of resources around capturing &amp; processing user context from computer screens and beyond.

# Motivation 
Context matters. Providing it is painful.

No human user should be forced to repeat themselves. That's what computers are made for. It's the 21st century, yet we are still forced to work with old-school software that is heavily siloed. Users have to repeat inputs, rely on copy & paste, import/export or in the best case integegration via APIs.

What if all software could acess all other software that you use? 

Microsoft's Office 97 Clippy "Are you writing a letter?" Was the right idea at the **wrong time**.

**Now is the right time.** If you are an innovator and excited about empowering your user with context, you came to the right place.

 # Developer Painpoints

 When developing context aware applications, one have to deal with a lot of pain points. 

1. **Discovery & validation** - Keeping up with what’s possible & Setting up experimentation 
1. **Privacy & Compliance** - Ensure user trust & compliance with regulations
2. **Performance** - Faster is better
3. **Cost** - LLMs are expensive - Here is our [cost calculator](https://docs.google.com/spreadsheets/d/16-K-vLpqvAxRUBy4ppqjMmPJyQwZ4E0wxevJdWcmzP4/edit?usp=sharing)
7. **Quality Testing & Evaluation** - You need to test and evaluate the quality of your application
4. **Deployment** - You need to deploy your application and keep it running
5. **Capturing Recording** - cross-platform recording the user's screen, audio, etc
6. **Avoiding lock-in** - avoid lock-in and stay flexible

# Stages
1. **Capture** - Ingest raw data from the source
2. **Pre-Process** - Clean, enrich, transform the data
3. **Contextualize** - Add meaning to the data. Merge different sources, do enrichment like entity recognition & aggregation.
4. **Act** - Use the data to take action, optionally store it for later.

# Interesting Links

## (Computer Screen) Vision Models 
- [Google AI Studio Live](https://aistudio.google.com/live) to stream your screen  
- Mistral Pixtral
- OpenAI
- Meta 3.2 Vision
- https://github.com/microsoft/OmniParser & https://huggingface.co/microsoft/OmniParser-v2.0
- [Phi-4-multimodal](https://techcommunity.microsoft.com/blog/educatordeveloperblog/welcome-to-the-new-phi-4-models---microsoft-phi-4-mini--phi-4-multimodal/4386037)

## Computer Use & Browser Use
- Anthropic Computer Use
- [Google Project Mariner](https://deepmind.google/technologies/project-mariner/)
- https://github.com/browser-use/browser-use
- [Nayla Browser](https://naylabrowser.com/)
- [Proxy 1.0](https://www.producthunt.com/posts/proxy-1-0)
- OpenAI Operator

## Logging/Rewind/Recall
   - Microsoft Recall
   - Apple [on screen content](https://developer.apple.com/documentation/appintents/making-onscreen-content-available-to-siri-and-apple-intelligence)
   - [Serval Open source alternatives for Recall/Logging](https://github.com/search?q=recall&type=repositories&s=stars&o=desc)
       - [OpenRecall](https://github.com/openrecall/openrecall) Python OS+ privacy first alternative to WIndows 1,800 stars
       - [TotalRecall](https://github.com/xaitax/TotalRecall) access Windows 11 recall data 2,000 stars
       - [Rem Recall](https://github.com/jasonjmcghee/rem) on Mac 2,300 stars
       - [Windrecorder](https://github.com/yuka-friends/Windrecorder) 3,000 stars
       - [mediar-ai/screenpipe](https://github.com/mediar-ai/screenpipe) rewind.ai x cursor.com = your AI assistant that has all the context. 24/7 screen & voice recording for the age of super intelligence. get… 8,800 stars
## OCR
- [getomni-ai/zerox](https://github.com/getomni-ai/zerox)
- [LLama-OCR](https://news.ycombinator.com/item?id=42154410)
- Visual to “structured”
    - [Meta nougat](https://facebookresearch.github.io/nougat/)

## Screen Recording / Remote Desktop sharing
 - https://github.com/rdp/screen-capture-recorder-to-video-windows-free

## Benchmarking
- https://github.com/likaixin2000/ScreenSpot-Pro-GUI-Grounding/

## Datasets
- **RICO Dataset**: This dataset comprises approximately 66,000 screenshots from 9,300 Android apps across 27 categories. While it primarily focuses on mobile applications, it has been widely used for screen content understanding and could offer insights applicable to desktop applications. ([arxiv.org](https://arxiv.org/html/2209.08199v4?utm_source=chatgpt.com))
- **ScreenQA Dataset**: Introduced in the paper "ScreenQA: Large-Scale Question-Answer Pairs over Mobile App Screenshots," this dataset contains around 86,000 question-answer pairs collected from approximately 35,000 screenshots derived from the RICO dataset. Although centered on mobile app screenshots, the methodologies employed might be adaptable for desktop application contexts. ([github.com](https://github.com/google-research-datasets/screen_qa?utm_source=chatgpt.com))
- **CIRCL Images AIL Dataset**: Offered by the Computer Incident Response Center Luxembourg (CIRCL), this dataset includes images such as photos and screenshots of websites. While it may not specifically target standard software applications, it could serve as a supplementary resource. ([circl.lu](https://www.circl.lu/opendata/circl-ail-dataset-01/?utm_source=chatgpt.com))

## Testing & Evaluation
- "Taking the pain out of screenshot AI testing" - We don't want to record the same screen over and over again. Instead for developer convenience we want to record the screen once and reuse it. This allows us to test and evaluate different pipelines, models, prompts etc. but also ensure quality with production systems. One inspiration for this is https://roark.ai which does it for voice

# Sources
## Outputs OS Streams 
 - Screen
 - Audio
 - Video
 - File Access
 - Notifications
- Clipboard
## Inputs
 - Keyboard
 - Mouse
 - Touch
 - Gaze
 - Gestures
 - Thoughts
## APIs to other services 
 - Calendar, Contacts, etc.
 - Messages (Email & Chats)
 - Browser History  
