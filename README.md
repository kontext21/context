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

## Computer Use
- Anthropic Computer Use

## Benchmarking
- https://github.com/likaixin2000/ScreenSpot-Pro-GUI-Grounding/

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