# Speech To Text

aka:
  Microsoft Speech API

  Cortana Speech API 

  Bing Speech API

---
# Capabilities
| Use cases                                                                                          | [REST APIs] | [Client Libraries] |
|----------------------------------------------------------------------------------------------------|-------------|--------------------|
| Convert a short spoken audio, for example, commands (audio length \< 15 s) without interim results | Yes         | Yes                |
| Convert a long audio (\> 15 s)                                                                     | No          | Yes                |
| Stream audio with interim results desired                                                          | No          | Yes                |
| Understand the text converted from audio using LUIS                                                | No          | Yes                |

[REST APIs]: getstarted/getstartedrest
[Client Libraries]: getstarted/getstartedclientlibraries

---
# Recognition modes

   * Interactive mode
   * Conversation mode
   * Dictation mode

---
# Output
  * Basic
  * N-Best

---
# Profanity

| *Profanity* value | Description                                                   |
|-------------------|---------------------------------------------------------------|
| `masked`          | Masks profanity with asterisks. This behavior is the default. |
| `removed`         | Removes profanity from all results.                           |
| `raw`             | Recognizes and returns profanity in all results.              |

---


# Custom Speech Service

Overcome speech recognition barriers such as speaking style, vocabulary and background noise.

---

# Style
* Elderly
* Accents
* Conversation and Command base

---
# Vocabulary
* Industry Names (dianasours, ml, ect)
* Product names 

# Background Noise
Your audio on your devices

# Custom Speech Service

Overcome speech recognition barriers such as speaking style, vocabulary and background noise.

---

# Style
* Elderly
* Accents
* Search, Dictation, Conversational

---
# Vocabulary
* Industry Names (dianasours, ml, ect)
* Product names 
---
# Background Noise
Your audio on your devices
---
# Comatibility
* Uses Bing Speech API
* Deploy to custom endpoint 
* Supports English, German, Chinese
---

# Architecture

![full](/home/administrator/Source/MicroNotes/Images/ChatBot.png)






![full](https://github.com/Microshak/MicroNotes/blob/master/Images/Screenshot%20from%202018-05-07%2011-04-47.png?raw=true)
---
