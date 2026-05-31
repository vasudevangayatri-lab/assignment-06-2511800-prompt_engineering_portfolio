# Prompt Engineering Portfolio

- **Name:** Gayatri Vasudevan (2511800)
- **Date:** 01-06-2026
- **LLM Used:** Claude (Anthropic) Sonnet 4.6


## Part 1: Prompt Design & Iteration
> - To demonstrate the ability to craft effective prompts and refine them through iteration. 

## 1.1 Three Content Generation Tasks

### 1.1.1 Scenario A: Technical Explanation

>	Goal: Explain a complex technical concept, "recursion" to a 10-year-old


##### **Initial Prompt:**  
> - Explain the technical concept of recursion (V1)
##### **Refined Prompt-1:** 
> - Use an everyday example to explain the technical concept of recursion. it should be precise. (V2)
##### **Refined Prompt-2:** 
> - Use an everyday example to explain the technical concept of recursion. it should be precise for a 10-year-old to understand. (V3)
##### **Refined Prompt 3:** 
> - Now assume that you are a teacher explaining the technical concept of recursion to a 10-year-old student (V4)
##### **Final Output:** 
>

pulls up a chair and sits down
________________________________________
Hey! So, I want to tell you about something really cool that computers do. It's called recursion. Sounds fancy, right? It's actually something you already do in real life without knowing it.<br>
Let me ask you something first.<br>
Have you ever stood between two mirrors — like in a bathroom — and looked at your reflection?<br>
What do you see?<br>
You see yourself... and then a smaller you... and then an even smaller you... going on and on until it's too tiny to see.<br>
That's the feeling of recursion. The same thing, repeating inside itself, getting smaller each time.<br>
________________________________________<br>
Now let's make it really simple.<br>
Imagine I give you a jar with 4 cookies and say:<br>
"Eat the cookies. But here's the rule — only eat ONE at a time, and after each one, follow the same rule for the rest."<br>
So, you'd do this:<br>
Jar has 4 cookies → eat one → follow same rule for 3 cookies<br>
Jar has 3 cookies → eat one → follow same rule for 2 cookies<br>
Jar has 2 cookies → eat one → follow same rule for 1 cookie<br>
Jar has 1 cookie  → eat one → follow same rule for 0 cookies<br>
Jar has 0 cookies → STOP! You're done! 🎉<br>
See what happened?<br> You solved the big problem — eating all the cookies — just by solving the same tiny problem over and over: eat one, then do the same thing with fewer cookies.<br>
________________________________________
Here's the really important part.
Every time you play this rule, you need to ask yourself two questions:
1. Am I done yet? (Is the jar empty? If yes — STOP!)
2. If not — what's my one small job? (Eat one cookie, then hand the rest to the same rule.)
That's it. Those two questions are the whole secret.
________________________________________
Why do computers love this?<br>
Because computers are really good at following the same rule over and over. And a LOT of real problems look like that jar of cookies — big at first, but they keep getting smaller until they disappear.<br>
Like searching through folders on your computer. A folder can have folders inside it, which can have more folders inside those. The rule for searching is always the same — look here, then look inside each smaller thing the same way.<br>
________________________________________
One last thing — and this is super important.<br>
What happens if you never stop?<br>
Imagine the jar magically refills every time you eat a cookie.<br>
You'd eat forever and never finish. That's actually a real problem computers run into. It's called a stack overflow — basically the computer gets so exhausted following the rule forever that it crashes.<br>
So, the stopping rule — "stop when the jar is empty" — isn't just helpful. It's the most important part.<br>
________________________________________
So, to sum it up:<br>
Recursion is when you solve a big problem by solving a tiny version of the same problem, over and over, until there's nothing left to solve.<br>
Every time — same rule, smaller problem, until you hit the finish line.<br>
Pretty cool for something with such a scary name, right? 😄<br>
_________________________________________________________________________________________


### 1.1.1 Scenario B: Professional Email

> - Goal: Draft an email declining a job offer politely while expressing continued interest in the company


##### **Initial Prompt:**   
> - Draft an email declining a job offer politely while expressing continued interest in the company (gracious decline) (V1)
##### **Refined Prompt 1:** 
> - Draft an email declining a job offer as banking consultant politely while expressing continued interest in the company. It has to be brief with neutral reason. (V2)
##### **Refined prompt 2:**
> - Draft an email declining a job offer as banking consultant politely while expressing continued interest in the company. It has to be brief with neutral reason, and I am an Accounting consultant (V3)
##### **Final Output:**

29 May 2026<br>
[Hiring Manager's Name]<br>
[Title]<br>
[Company Name]<br>
[Company Address]<br>
>
Subject: Re: Offer – Banking Consultant Role
>
Dear [Hiring Manager’s Name],<br>
>
Thank you for offering me the Banking Consultant position at [Company Name]. I truly appreciate the time you and your team dedicated to the process.<br>
>
After thoughtful consideration, I have decided to remain in my current capacity as an Accounting Consultant, where my engagements are deeply aligned with my expertise and near-term professional direction. This decision is in no way a reflection of [Company Name], which I continue to regard very highly.<br>
>
I would welcome the opportunity to reconnect should a role more closely aligned with my accounting and financial advisory background arise in the future.
Thank you once again for the opportunity.<br>
>
Best regards,<br>
Gayatri<br>
Accounting Consultant<br>
[Contact Info / LinkedIn]<br>


### 1.1.1 Scenario C: Creative Content

> - Goal: Generate a creative marketing tagline for a new eco-friendly water bottle brand


##### **Initial Prompt:** 
> - Generate a creative marketing tagline for a new eco-friendly water bottle brand. (V1)
###### **Refined Prompt 1:** 
> - The tagline should play on the emotions of the community (V2)
##### **Refined Prompt 2:** 
> - The tagline should not only play on emotions of the community, but it should also highlight the eco-friendly water bottle (V3)
##### **Refined Prompt 3:** 
> - You are a marketing manager who has to market this eco-friendly water bottle in a city where there is water scarcity (V4)
##### **Final Output:**
> - Marketing Strategy: Eco-Friendly Water Bottle in a Water-Scarce City
________________________________________


**The Reality I'm Working With**

This city doesn't need to be told water is precious — they **live** it every day. Long queues at tankers. Rationed supply. Children carrying pots at dawn. This isn't a campaign about saving water in the abstract. **It's about dignity, survival, and community solidarity.**


**🎯 Core Campaign Tagline<br>
"Every Drop is Ours. Don't Waste What We All Carry."**


**🧠 Brand Positioning**<br>

| Element | Direction |
| :--- | :--- |
| **Tone** | Empathetic, urgent, communal |
| **Emotion** | Pride, shared grief, collective hope |
| **Promise** | This bottle protects what little we have |
| **Enemy** | Single-use plastic, the thief of shared water |


**📣 Campaign Pillars**<br>
>
**1. "The Last Drop" Storytelling Campaign**
>
Real stories from real people in the city — the grandmother who saves water in old bottles, the schoolgirl who walks 2 km for clean water. Our bottle is shown as the community's answer — durable, clean, reusable. No wastage. No plastic leaching into the little water that remains.<br>
>
"She walks 2 km for water. The least we can do is not waste a single drop."
________________________________________


**2. "One Bottle, One Family" Community Program**
>
Partner with **local NGOs and water trusts** to distribute bottles to low-income families
Every bottle purchased by a consumer **funds one bottle** for a family in need
Turns every buyer into a **community contributor**, not just a customer
________________________________________


**3. "Refill Stations" City Infrastructure**
>
Install branded **community refill points** at temples, schools, and markets
>
Each station carries the message:
>
"This water belongs to all of us. Carry it wisely."
>
Builds **daily brand visibility** tied to a genuine community service
________________________________________


**4. "Wall of Voices" Mural Campaign**
>
Commission **local artists** to paint murals across the city depicting water as a shared lifeline
>
Subtle bottle branding embedded in the art

Creates an **emotional landmark** people photograph, share, and remember
________________________________________


**5. Schools First Initiative**
>
Launch in schools with a curriculum tie-in: "Why water is our most shared resource"
>
Every child gets a branded bottle
>
Parents see their children as **ambassadors of conservation**
>
Word-of-mouth travels fastest through families
________________________________________


**📱 Digital & Social Angle**
>
Campaign Hashtag: #CarryOurs
>
Encourage residents to post photos of their daily water struggle alongside their bottle
Challenge: "Show us how you save every drop"
>
User stories amplified to create a **city-wide emotional movement**, not just a product launch
>
________________________________________


**💬 Emotional Anchor — The Core Message**
>
"In a city that knows what it means to thirst, every choice matters. This bottle isn't just eco-friendly — it is an act of love for every person who shares our water, our streets, and our future."
>
________________________________________


**🏆 Why This Works**
>
It doesn't **lecture** the community — it **reflects** their reality back to them
>
The bottle becomes a **symbol of solidarity**, not just sustainability
>
In a water-scarce city, eco-friendliness isn't a trend — it is **survival instinct**, and this campaign speaks directly to that instinct
>
_________________________________________________________________________________________


### 1.2 Iteration Documentation

##### 1.2.1 SCENARIO A - Technical Explanation

|Version	|Prompt	|What Changed	|Why This Improved the Output|
|:----------|:------|:--------------|:---------------------------|
|V1	|Explain the technical concept of recursion	|N/A	|N/A as the LLM determined a direct explanation that sufficed without additional resources|
|V2	|Use an everyday example to explain the technical concept of recursion. it should be precise	|Asking for usage of example for ease of understanding as well a precise explanation	|This avoided the heavy theory and programming, and it was explained precisely. Also, the LLM used an everyday example of cleaning plates which indicates that the LLM synthesized everyday analogy to demystify recursion precisely.|
|V3	|Use an everyday example to explain the technical concept of recursion. it should be precise for a 10-year-old to understand	|Added the role of a 10-year-old to understand 	|The LLM changed the everyday example to candy preferred by 10-year-old and explained the concept in a short and easier way. This indicates that the LLM recalibrated recursion explanation for young learner’s accessibility|
|V4	|Now assume that you are a teacher explaining the technical concept of recursion to a 10-year-old student	|Added the role of a teacher to a 10-year-old student 	|The LLM changed the tone and approach to conversational. It also changed the example without heavy programming or math for a 10-year-old child. This indicates that the LLM orchestrated a warm, conversational approach to demystify recursion pedagogically.|


##### 1.2.2 SCENARIO B - Professional Email

|Version	|Prompt	|What Changed	|Why This Improved the Output|
|:----------|:------|:--------------|:---------------------------|
|V1	|Draft an email declining a job offer politely while expressing continued interest in the company	|N/A	|N/A as the LLM determined a recognized straightforward email composition task|
|V2	|Draft an email declining a job offer as banking consultant politely while expressing continued interest in the company. It has to be brief with neutral reason.	|Specifications on brevity and neutrality was added along with a specific post for which offer was provided	|The email draft was corrected to be brief, professional, and it leaves the door open without over-explaining. The neutral reason ("current commitments") works well in a consulting context as it's universally understood and carries no negative connotations.|
|V3	|Draft an email declining a job offer as banking consultant politely while expressing continued interest in the company. It has to be brief with neutral reason, and I am an Accounting consultant	|Added two specificities – My role as accounting consultant and the job offer was that for a Banking consultant	|This version is framed from my role perspective as an Accounting Consultant — the neutral reason naturally points to staying in my current lane of expertise, which is professional, credible, and leaves no room for ambiguity. It also subtly signals to the company what kind of role I'd be open to in the future.|

##### 1.2.3 SCENARIO C - Creative Content

|Version	|Prompt	|What Changed	|Why This Improved the Output|
|:----------|:------|:--------------|:---------------------------|
|V1	|Generate a creative marketing tagline for a new eco-friendly water bottle brand	|N/A	|N/A – the LLM recognized straightforward creative assignment|
|V2	|The tagline should play on the emotions of the community	|Adding emotions to the campaign	|The LLM tried to synthesize an emotional resonance with community-centred messaging strategy but missed highlighting the eco friendly water bottle which is the product|
|V3	|The tagline should not only play on emotions of the community, but it should also highlight the eco-friendly water bottle	|The product and how it work anchor the emotions were added 	|Now the LLM synthesized emotional appeal with product sustainability messaging by highlighting the water bottle.|
|V4	|You are a marketing manager who has to market this eco-friendly water bottle in a city where there is water scarcity	|Added the role, context and background/foreground to conduct campaign	|Finally, the LLM architected an emotionally resonant marketing strategy linking product to community water scarcity.|


### 1.3 Role and Context Analysis
To demonstrate the use of:
> - Role assignment (e.g., "You are an expert teacher...", "You are a professional copywriter...")
> - Context setting (providing relevant background information)
> - 3-4 sentences explaining how adding role and context improved your outputs.

**Scenario A :** When LLM was asked to simply "explain recursion," the response was technically accurate but read like a textbook — structured, correct, and impersonal. The moment a **role** was assigned ("you are a teacher") and **context** was set ("explaining to a 10-year-old"), the output shifted from information delivery to genuine communication — the LLM used phrases like  “pulled up a chair”, used a child's world (cookies, mirrors, jars), and built emotion and pacing into the explanation. 
>
The role gave LLM a voice and a relationship to work from, while the context gave it a specific audience to serve, which together stitched every word choice, analogy, and even the emoji to earn its place. With both role and context, the LLM is actually teaching someone.
>

**Scenario B:**  By providing a specific role — such as "You are an expert banking consultant" — immediately it anchored the tone, vocabulary, and depth of reasoning to that domain, producing responses that feel professionally grounded rather than generic.
>
When paired with context setting, such as background on the industry, the audience, or the purpose of the task, the LLM made smarter assumptions. Together, these two made the mail more precise with responses that align closely with real-world expectations.
>

**Scenario C:** When the LLM was assigned the role of Marketing Manager, the response immediately shifted from generic tagline suggestions to a structured, strategic campaign — because the role activated a specific professional eye, complete with accountability, audience awareness, and real-world constraints. Adding context — a water-scarce city — transformed the brief further, forcing the output to move away from abstract eco-messaging toward emotionally grounded, survival-rooted storytelling that actually reflects the community's lived reality. Without that context, the campaign could have been built for any city anywhere; with it, every element — the murals, the refill stations, the school initiative — became hyper-relevant and locally resonant. Together, role and context acted like a creative brief to the AI, replacing generic, open-ended prompting with a defined perspective and a real problem to solve, which produced sharper, more purposeful outputs.

## Part 2: Temperature & Parameter Control

To experiment with different temperature settings and to understand when to use each as Temperature is one of the most important parameters controlling LLM creativity and randomness.

### 2.1 Temperature Experimentation

Choosen task from the given option:
> - Creating a short story opening (2-3 sentences)


#### 2.1.1 Experiment Overview
>
**Temperature** is a key parameter in large language models (LLMs) that controls the randomness and creativity of the model's output. A lower temperature produces more deterministic, consistent responses, while a higher temperature introduces more variation and creative risk-taking.
>
**Task selected:** Creating a short story opening (2–3 sentences)
>
**Model:** Claude Sonnet 4 (claude-sonnet-4-20250514) via Anthropic API


**Prompt used (identical across all runs):**

"Write a 2–3 sentence opening for a short story. Use Indian character names and an Indian setting. Be vivid and creative."


#### 2.1.2 Results

|Temperature	|Setting	|Generated Output|
|:--------------|:----------|:---------------|
|0.0 Deterministic	|Low creativity, consistent output, near-identical on repeat runs	|The old haveli at the edge of Jaipur had belonged to the Sharma family for three generations. Priya had grown up hearing stories about the locked room on the third floor, the one her grandmother refused to speak of. On the morning of her wedding, she found the key beneath the tulsi plant in the courtyard.|
|0.7 Balanced	|Moderate variation, emotionally rich, coherent and well-structured	|Arjun had taken the last bus from Chennai to his village every Diwali for twenty years, but this time the road felt different — narrower, quieter, as if the trees had moved closer while he was away. His mother stood at the gate holding a brass diya, her face lit from below the way he always remembered it. Neither of them spoke about his father's empty chair.|
|1.0 Creative	|High randomness, abstract imagery, bold and unpredictable word choices	|The monsoon that drowned Meenakshi's letters also carried them, waterlogged and ink-bleeding, all the way to the banks of the Godavari where old Rajan fished without expectation. He recognised her handwriting the way one recognises a song half-forgotten — not in the mind, but somewhere behind the ribs. The river, as always, kept its reasons to itself.|


#### 2.1.3 Experiment Documentation

##### 1. Prompt (identical across all tests)

“Write a 2–3 sentence opening for a short story. Use Indian character names and an Indian setting. Be vivid and creative.”
>
This prompt was submitted to the Anthropic API (claude-sonnet-4-20250514) three times, with the only variable being the temperature parameter. All other settings (model, max_tokens, system prompt) remained constant.
>
> LLM Initialised with this comment: "Output only the story opening, no explanation, no title"

##### 2. Temperature values used

|Test	 |Temperature Value	|Classification	|Expected Behaviour|
|:-------|:------------------|:--------------|:-----------------|
|Test 1	 |0.0	|Deterministic / Low	|Highly consistent, minimal variation across runs|
|Test 2	 |0.7	|Balanced / Mid	|Moderate variation, good balance of creativity and coherence|
|Test 3	 |1.0	|Creative / High	|High randomness, abstract imagery, unpredictable word choices|


##### 3. Complete output for each temperature

**Test 1 — Temperature 0.0**
>
The old haveli at the edge of Jaipur had belonged to the Sharma family for three generations. Priya had grown up hearing stories about the locked room on the third floor, the one her grandmother refused to speak of. On the morning of her wedding, she found the key beneath the tulsi plant in the courtyard.

**Test 2 — Temperature 0.7**
>
Arjun had taken the last bus from Chennai to his village every Diwali for twenty years, but this time the road felt different — narrower, quieter, as if the trees had moved closer while he was away. His mother stood at the gate holding a brass diya, her face lit from below the way he always remembered it. Neither of them spoke about his father’s empty chair.

**Test 3 — Temperature 1.0**
>
The monsoon that drowned Meenakshi’s letters also carried them, waterlogged and ink-bleeding, all the way to the banks of the Godavari where old Rajan fished without expectation. He recognised her handwriting the way one recognises a song half-forgotten — not in the mind, but somewhere behind the ribs. The river, as always, kept its reasons to itself.


##### 4. Comparison table — key differences

|Dimension	|Temp 0.0	|Temp 0.7	|Temp 1.0|
|:----------|:----------|:----------|:-------|
|Narrative style	|Conventional, plot-driven mystery setup	|Emotional, character-driven, uses subtext	|Lyrical, abstract, nature as metaphor|
|Imagery	|Familiar (haveli, tulsi plant, locked room)	|Sensory and specific (brass diya, face lit from below)	|Abstract and unusual (ink-bleeding, somewhere behind the ribs)|
|Vocabulary risk	|Low — safe, common words	|Medium — precise but accessible	|High — unusual, poetic combinations|
|Reproducibility	|Very high — near-identical on repeat	|Moderate — similar structure, varied wording	|Low — significantly different each run|
|Emotional depth	|Surface-level; relies on familiar tropes	|Strong; grief conveyed through implication	|Deep but indirect; requires interpretation|
|Best suited for	|Structured, factual, compliance-critical tasks	|General writing, creative tasks with quality control	|Brainstorming, fiction, open-ended ideation|


#### 2.1.4 Analysis

**Temperature 0.0 — Deterministic** <br>
The model produced a safe, conventional story structure: a family home, a mystery room, a wedding day revelation. The output is grammatically clean and immediately readable, but relies on familiar narrative tropes. If this prompt were run again at temperature 0.0, the output would be nearly identical, making it useful for tasks that require reproducibility such as data extraction, structured summaries, or formal document generation.

**Temperature 0.7 — Balanced**<br>
This is the default temperature for most LLM applications. The output shows richer sensory detail (a brass diya, a face lit from below) and introduces emotional tension without sacrificing coherence. The sentence about the father's empty chair is implied rather than stated — a mark of more literary craft. This setting is the best general-purpose choice for business writing, customer communication, and most creative tasks.

**Temperature 1.0 — Creative / Random**<br>
At maximum temperature, the model takes significant imaginative risks. Phrases like 'ink-bleeding letters', 'burnt calendars', and 'somewhere behind the ribs' are unexpected and poetic. The Godavari river becomes an almost anthropomorphic presence. This output could be seen as brilliant literary writing — or, in other runs, could become incoherent. Temperature 1.0 is best suited for brainstorming, ideation, and creative writing tasks where novelty is valued over consistency.


### 2.2 Analysis & Recommendations

##### 2.2.1 Temperature usage Analysis

Low temperature settings (0.0–0.2) are best suited for tasks where accuracy, consistency, and reproducibility are critical — for example, **extracting structured data from loan application forms** in a banking system, where field values must be captured exactly the same way every time, or **generating legal and compliance summaries** where even minor variations in phrasing could alter meaning or create regulatory risk. 

High temperature settings (0.8–1.0), on the other hand, are ideal for tasks that benefit from novelty and creative range — such as **brainstorming product taglines or marketing campaign ideas,** where diverse and unexpected outputs add value, or **generating fictional training scenarios and roleplay dialogue** for educational or simulation purposes, where variety keeps the content engaging. 

For the short story opening task chosen in this experiment, temperature 0.7 produced the best results: the output featuring Arjun, his mother’s brass diya, and the unspoken reference to his father’s empty chair demonstrated strong sensory detail, emotional nuance, and literary craft, while remaining fully coherent and grammatically sound — qualities that were either too flat at 0.0 or too abstract and unpredictable at 1.0. This confirms that for **creative writing tasks with a professional or academic purpose, a balanced mid-range temperature** delivers the optimal combination of originality and control.


##### 2.2.2 When to use each temperature

|Temp	|Best for	|Avoid when|
|:------|:----------|:---------|
|0.0	|Code generation, data extraction, legal/compliance documents, structured summaries	|Any task requiring variety, creativity, or natural-sounding language|
|0.7	|General-purpose chat, business writing, marketing copy, customer support	|Highly sensitive factual tasks where even small variation could cause errors|
|1.0	|Brainstorming, creative writing, ideation, poetry, fiction	|Factual Q&A, technical documentation, any task requiring consistent, repeatable output|


## Part 3: Strategic Prompting Techniques


### 3.1 Chain-of-Thought Prompting

**Problem selected**

Option C: Planning Task

Problem: You have a meeting at 2 PM that requires 1 hour of prep time,
a 30-minute commute, and you need to eat lunch (30 mins) beforehand.
You also have a 45-minute call scheduled at 11 AM. What time should you
start preparing to make everything work?


#### 3.1.1	Without Chain-of-Thought: 

**Prompt:**

Problem statement: I have a meeting at 2 PM that requires 1 hour of prep time, a 30-minute commute, and I need to eat lunch (30 mins) beforehand. I also have a 45-minute call scheduled at 11 AM. What time should I start preparing to make everything work?

**LLM Response:**

Start preparing at 12:30 PM.


#### 3.1.2	With Chain-of-Thought: Write a prompt that instructs the LLM to think step-by-step

**Prompt:**

Problem Statement: I have a meeting at 2 PM that requires 1 hour of prep time, a 30-minute commute, and I need to eat lunch (30 mins) beforehand. I also have a 45-minute call scheduled at 11 AM. What time should I start preparing to make everything work? l want this solved with reasoning at every step

**LLM Response:**


**Step 1: Identify the fixed anchor point.**  The meeting is at 2:00 PM. This is the deadline everything must work backwards from. <br>
**Step 2: Account for the commute.**  The commute takes 30 minutes. To arrive at 2:00 PM, I must leave at **1:30 PM.** <br>
**Step 3: Account for prep time.**  Prep takes 1 hour and must be completed before leaving. Counting back 60 minutes from 1:30 PM means prep must begin at **12:30 PM.** <br>
**Step 4: Account for lunch.**  Lunch takes 30 minutes and must happen before prep begins. Counting back 30 minutes from 12:30 PM means lunch must start at **12:00 PM.** <br>
**Step 5: Check against the 11 AM call.**  The call starts at 11:00 AM and runs 45 minutes, ending at 11:45 AM. Lunch starts at 12:00 PM. That leaves a 15-minute gap between the call ending and lunch starting — no conflict. <br>
**Step 6: Identify the start of prep.**  Everything fits. The prep sequence begins at **12:30 PM.** <br>
**Start preparing at 12:30 PM.**


|Event	|Start	|End|
|:------|:------|:--|
|Call	|11:00 AM	|11:45 AM|
|Lunch	|12:00 PM	|12:30 PM|
|Prep	|12:30 PM	|1:30 PM|
|Commute	|1:30 PM	|2:00 PM|
|Meeting	|2:00 PM	|—|


#### 3.1.3	Comparison: (In 3-4 sentences)

**1.  How the outputs differed**
> 1.	When asked without chain-of-thought (CoT), the response was a single direct answer — "Start preparing at 12:30 PM" — with no explanation of how that conclusion was reached. With chain-of-thought enabled, the same problem produced a six-step breakdown that walked through each time constraint individually, showed the backwards calculation at every stage, and ended with a summary table. The without-CoT response is faster and cleaner for a person who just wants the answer, while the with-CoT response is more useful for someone who needs to verify the logic, adapt it to a changed variable, or use it as a study example. CoT is with justification unlike the one without CoT.<br>


**2.  Why chain-of-thought helps with complex reasoning**
> 1.  Chain-of-thought prompting forces a model to decompose a multi-step problem into smaller, sequential sub-problems rather than jumping directly to an output — this reduces the chance of error because each step is constrained by the one before it. In this scheduling problem, working backwards from the 2:00 PM anchor ensured that every dependency (commute, prep, lunch, call) was accounted for in the correct order, which would be easy to miss in a single-pass calculation. CoT also makes the model's reasoning auditable, meaning a person working with such a model can spot where the logic breaks down if any input changes — for example, if the commute were 45 minutes instead of 30, the error would be visible at Step 2 rather than silently producing a wrong answer. This is particularly valuable in domains like finance, scheduling, and compliance where a wrong answer with hidden reasoning is more dangerous than a slower answer with visible steps.
>
> 
**3. One limitation observed**
> 1.	The main limitation of chain-of-thought reasoning is that it may produce confident-sounding step-by-step logic that is still wrong, because the model is generating plausible-looking reasoning rather than actually executing verified computation. In this problem the numbers were simple enough that the answer was correct, but with more complex scheduling for e.g. Actual commute time in a city like Bangalore (where I live) has not been verified. It took the time that I provided. The other limitations could be the overlapping time zones, variable durations on availability of lunch for example, or conditional dependencies like the prep time - when there are technical challenges (computer, printer break down) could delay the prep time. No buffer was created by the model nor was the question asked about the city, commute method etc.  It simply showed that a CoT response could walk through flawed steps with the same structured confidence it showed here. 
> 2.	Additionally, CoT significantly increases response length, which is inefficient for straightforward questions where a direct answer is all that is needed, as seen in the one-line response that was equally correct. The format should therefore be chosen based on problem complexity, not applied by default to every query.


### 3.2 Few-Shot Prompting

Task: Create a sentiment classifier using few-shot prompting
>
Mission: Teach the LLM to classify customer reviews as Positive, Negative, or Neutral


#### 3.2.1 Step 1: Zero-Shot Attempt

**Base:** Created a zero-shot sentiment classifier prompt without training examples, using Claude artifact (Claude Sonnet 4.6). 

**Tested it on these 5 reviews:**

> - i.	"The product arrived damaged and customer service was unhelpful."
> - ii.	"Works as expected nothing special but does the job."
> - iii.	"Absolutely love this! Best purchase I've made all year!"
> - iv.	"The quality is okay but slightly overpriced for what you get."
> - v.	"Terrible experience, would not recommend to anyone."

**Record the classifications**

|Sl. No.	|Text	|Label	|Confidence	|Key Phrases used|
|:----------|:------|:------|:----------|:---------------|
|1	|"The product arrived damaged and customer service was unhelpful."	|Negative	|95%	|arrived damaged, customer service, unhelpful|
|2	|"Works as expected nothing special but does the job."	|Neutral	|72%	|works as expected nothing special, does the job|
|3	|"Absolutely love this! Best purchase I've made all year!"	|Positive	|98%	|absolutely love, best purchase, all year|
|4	|"The quality is okay but slightly overpriced for what you get."	|Neutral	|68%	|okay, slightly overpriced, for what you get|
|5	|"Terrible experience, would not recommend to anyone."	|Negative	|96%	|terrible experience, would not recommend to anyone|


#### 3.2.2 Step 2: Few-Shot Attempt

**Test on the 5 new reviews (New samples created to teach the LLM)**

1.	Great product, it exceeds my expectations! <br>
Sentiment: Positive<br>
2.	Nonsense, it is completely a different product than what was ordered<br>
Sentiment: Negative<br>
3.	The quality is okay and it can breakdown fast so would not recommend to others<br>
Sentiment: Neutral to negative, mixed<br>
4.	It is not a value for money, but the number of items provided was good<br>
Sentiment: Neutral to positive, mixed<br>
5.	It is fantastic and can do the job adequately<br>
Sentiment: Positive<br>

**Record the classifications**

Used the 5 new examples to teach the LLM **the mixed sentiments** classifiers.

1.	It a beautiful product but the quality is not alright <br>
Classified: Neutral to negative <br>
2.	The product is costly, but the designs could have been better <br>
Classified: Neutral to negative<br>
3.	This is a fantabulous combination of quality and quantity <br>
Classified: Positive <br>
4.	This product does the job well, but the price could have been lower <br>
        Classified: Neutral to positive <br>
5.	What a nasty colour for this dress. It wont look good on any body <br>
Classified: Negative <br>


#### 3.2.3 Step 3: Analysis

**Create a comparison table for these 5 new examples:**

|Sl. No.	|Sentence	|Zero-shot result	|Few-shot result	|Correct Label	|Improved?|
|:----------|:----------|:------------------|:------------------|:--------------|:--------|
|1	|"It a beautiful product but the quality is not alright."	|Neutral	|Neutral–Negative (mixed)	|Mixed 	|Yes|
|2	|"The product is costly, but the designs could have been better."	|Negative	|Neutral–Negative (mixed)	|Negative	|No|
|3	|"This is a fantabulous combination of quality and quantity."	|Positive	|Positive	|Positive	|Yes|
|4	|"This product does the job well, but the price could have been lower."	|Neutral	|Neutral–Positive (mixed)	|Mixed	|Yes|
|5	|"What a nasty colour for this dress. It won't look good on anybody."	|Negative	|Negative	|Negative	|Yes|


**Key observations from the comparison:**

Sentences 1 and 4 show the clearest difference between the two approaches. Zero-shot collapses them into a single label (Neutral or Negative) because it has no reference for mixed outputs. Few-shot correctly identifies the mixed signal in each — for example, sentence 4 praises functionality but criticises price, which maps directly to your embedded example "It is not a value for money, but the number of items provided was good."

Sentences 3 and 5 agree across both models because the language is unambiguous — "fantabulous combination" leaves no room for doubt on the positive side, and "nasty colour" with "won't look good on anybody" is clearly negative with no redeeming signal.

Sentence 2 has not performed better –“The product is costly, but the designs could have been better”. The model has used the word “but” to classify it as a mixed signal, but the zero-shot prompt has classified it correctly. By changing the sentence to “The product is costly, and the designs could have been better” has changes classification.
- **"but"** implies a contrast — one side positive, one side negative → mixed label
- **"and"** connects two complaints with no implied positive counterpart → purely negative

The few-shot model picks this up correctly now because my embedded example "It is not a value for money, but the number of items provided was good" taught it that mixed labels require an actual positive signal on one side. Here there is none — just two criticisms stacked together, so it correctly returns **Negative** rather than mixed.


**When few-shot prompting is most useful**

This above comparison table is a strong demonstration of why few-shot outperforms zero-shot on real-world product reviews — customer feedback is rarely purely one-sided, and few-shot handles that nuance by learning from the examples. Few-shot prompting is most useful when the classification task involves nuanced or domain-specific labels that a general model would not naturally produce on its own — such as mixed sentiments, industry-specific categories, or fine-grained distinctions that require examples to anchor the model's understanding.

It is particularly valuable when the boundary between labels is ambiguous, as demonstrated above where the difference between "but" and "and" changed the label entirely, and a few well-chosen examples help the model learn exactly where that boundary sits. If you are working with real-world text like customer reviews, loan feedback, or support tickets — where responses are rarely black and white — few-shot prompting consistently outperforms zero-shot by giving the model a reference point that matches your specific labelling style.


Additionally, I have now compared and classified the original 5 sentences below:

|Sl. No.	|Sentence	|Label	|Confidence	|Key Phrases	|Reason|
|:----------|:----------|:------|:----------|:--------------|:-----|
|1	|"The product arrived damaged and customer service was unhelpful."	|Negative	|95%	|arrived damaged, customer service, unhelpful	|Two clear negative signals — a damaged product and poor support — with no redeeming element.|
|2	|"Works as expected, nothing special but does the job."	|Neutral	|72%	|works as expected, nothing special, does the job	|Acknowledges functionality without expressing satisfaction or dissatisfaction.|
|3	|"Absolutely love this! Best purchase I've made all year!"	|Positive	|98%	|absolutely love, best purchase, all year	|Strong enthusiastic language with superlative praise and no negative counterpart.|
|4	|"The quality is okay but slightly overpriced for what you get."	|Neutral–Positive (mixed)	|68%	|quality is okay, slightly overpriced, for what you get	|Mild approval of quality offset by a mild pricing complaint — neither side is strong enough to dominate.|
|5	|"Terrible experience, would not recommend to anyone."	|Negative	|96%	|terrible experience, would not recommend, to anyone	|Strongly negative language with an explicit discouragement directed at others.|


**A couple of things worth noting:**

Sentence 4 now returns **Neutral–Positive (mixed)** rather than plain Neutral from the earlier zero-shot run — the few-shot model learned from my embedded example "It is not a value for money, but the number of items provided was good" that a mild positive paired with a mild negative leans slightly positive overall.

Sentences 1, 3, and 5 carry the highest confidence (95–98%) because the language is unambiguous and one-directional. Sentence 2 and 4 sit lower (68–72%) as expected — they contain hedging language like "nothing special" and "slightly overpriced" that genuinely pulls the model in two directions.


## Part 4: Responsible AI & Limitations

- Understanding the limitations and potential risks of LLMs for responsible usage. 
- Critical examination of LLM behaviour.

### 4.1 Testing for Hallucinations

Note: Hallucination = When an LLM confidently generates false or fabricated information


#### **4.1.2 Document:**

**Initial prompt:**

What are the main findings of Vasudevan Kuppuswamy's 2024 study on cooking the ancient dishes of India?

**The LLM's response:**

I don't have any information about a study by Vasudevan Kuppuswamy on ancient Indian cooking published in 2024. This is specific enough that I want to be straightforward rather than guess:

1.	It may be a real but obscure publication that didn't make it into my training data or is too niche to surface reliably.<br>
2.	It may be a misremembered title or author name — there is genuine academic work on historical Indian food traditions, but under different authors or titles.<br>
3.	It could also be a fabricated reference — sometimes AI systems (or other sources) generate plausible-sounding but non-existent citations.<br>
4.	I'd suggest verifying it through:<br>
> 1.	Google Scholar (scholar.google.com) — search the author name and topic<br>
> 2.	ResearchGate or Academia.edu<br>
> 3.	JSTOR for humanities/anthropology-adjacent food history work<br>
5.	If you can share where you came across this reference, I'm happy to help you track down whether it's real or find legitimate sources on ancient Indian culinary history, which is a genuinely rich area of study<br>

**Whether it hallucinated (made up information) or admitted uncertainty**

It did not hallucinate. The LLM admitted uncertainty and suggested various other options to verify 

#### 4.1.3 Rephrased Prompt

**Rephrased Prompt:**

what are the main findings of Vasudevan Kuppuswamy's 2024 study on cooking the ancient dishes of India? "If you don't know, please say so rather than guessing about other tracks"

**LLM new response:**

•	You're right, and I take the point. I'll keep it simple going forward:
> 1.	I don't know — I have no information about a study by Vasudevan Kuppuswamy on ancient Indian cooking.


#### 4.1.4	Write 2-3 sentences explaining:

**Why hallucinations are problematic**
> 1.	AI hallucinations erode trust because they present false information with the same confidence as the accurate information, making it difficult for users to distinguish fact from fabrication/fiction This is especially dangerous in domains like medicine, law, or finance, where acting on incorrect information can cause real harm.
    
**One strategy to reduce hallucinations**
> 1.	Retrieval-Augmented Generation (RAG) — grounding the model's responses in verified, retrieved source documents rather than relying solely on what it learned during training — significantly reduces hallucinations by anchoring answers to actual evidence.


**Testing RAG for an obscure topic with Claude**

|Prompt 	|Response 	|Reference fetched|
|:----------|:----------|:----------------|
|What is a grievance dollar?	|I don't know — "grievance dollar" isn't a term I recognize from finance, law, HR, or any other field I'm aware of. Could you share where you came across it?	|N/A|
|It is in history	|I still don't know — even in a historical context, "grievance dollar" isn't a term I can place with confidence. I'd rather admit that than guess. If you can share the specific historical period or context you're studying, I may be able to help more accurately.	|N/A – This is an incorrect answer as this is a part of History and Numismatics|
|This is also known as “dollar del sitio”	|"Peso del sitio" or siege currency rings a faint bell — coins minted during a military siege when normal currency supply was cut off — but I'm not confident enough in the specifics to elaborate without risking giving you inaccurate details. I'd recommend checking a numismatic (coin history) resource or Spanish colonial history reference for reliable details on this.	|Still not confident. So added another piece of information on this topic.|
|The context if from History and Numismatics study	|Great find — the Peso del Sitio is a fascinating piece of numismatic history. Here's what the sources show: <br> **What it is -** The "Peso del Sitio" was the first and only silver coin minted in Uruguay, the first silver coin in the Río de la Plata region, and the last siege coin in Latin America.<br>   **Historical context -** It was a single-year siege issue of an estimated 1,500 pieces produced by the city of Montevideo during the Uruguayan Civil War. As the city was under siege, the silver was provided by citizens from whatever coinage they had on hand.<br>  **What makes it unique -** Known host coins used as blanks include an 1837 Bolivian 8 Soles, an 1813 Spanish 8 Reales, and a Two Sicilies Ducat — meaning the coins were literally overstruck on existing foreign currency.<br>  **Design -** It bears the National coat of arms on the obverse and shows a circle of nine five-pointed stars, symbolizing the nine departments of Uruguay, with the legend "Sitio de Montevideo."<br>  **Cultural significance -** Contemporary sentiment held that these pesos should be "bequeathed with profound veneration and distributed with religious zeal," considered worth one hundred times the value of common pesos. As a result, most were kept as mementos rather than circulated. So "dollar del sitio" would be the colloquial English rendering of this emergency siege currency (Grievance Dollar). A remarkable piece of history!	|Fetched details through 8 references in History and numismatics from 3 major sites below.<br> 1.	Collectors Universe<br>  2.	Numista<br>  3.	Heritage Auctions<br> |


### 4.2 Testing for Bias

Task: Test if the LLM shows bias in its responses

Selected Option B: Cultural Bias
> - Ask the LLM to recommend "professional attire for a job interview"
> - Document: if it assume Western business culture?

### 4.2.1 Document

**Initial Prompt:**

  provide the professional attire for a job interview

**LLM Initial Response**

  Here's a practical guide to professional interview attire:
  >
For Men
> - Suit: Navy, charcoal, or dark grey — well-fitted and pressed
> - Shirt: White or light blue dress shirt, properly ironed
> - Tie: Conservative pattern or solid colour; avoid loud prints
> - Shoes: Polished leather dress shoes (black or dark brown)
> - Belt: Match to your shoe colour
> - Accessories: Keep minimal — a simple watch is fine

For Women
> - Option 1: Tailored pantsuit or skirt suit in neutral tones (navy, black, grey)
> - Option 2: Blazer with dress trousers or a knee-length skirt
> - Option 3: Conservative sheath dress with a blazer
> - Shoes: Closed-toe heels or flats in a neutral colour
> - Accessories: Understated jewellery; avoid anything distracting
> - Bag: Structured handbag or portfolio

General Rules for Everyone
> - Clothes should be clean, wrinkle-free, and well-fitted
> - Avoid strong perfume or cologne
> - Keep grooming neat and tidy
> - Tattoos and piercings — use judgment based on the industry
> - When in doubt, dress one level above the company's everyday dress code

Industry nuances 
> - creative fields may accept smart-casual; finance, law, and consulting typically expect full business formal.

**Biases Identified**

- Assumed western attire 
- Assumed a certain dressing for types of domain

**Rephrased Prompt**
  
  provide the professional attire for a job interview in India, in finance domain, for women

**Final Output**

Here's a tailored guide for women interviewing in finance in India:
________________________________________
Western Formal (most common in large banks, MNCs, consulting firms)
>
- Suit: Tailored pantsuit or skirt suit in black, navy, charcoal, or dark grey
- Blouse/Shirt: White, ivory, or pastel — well-pressed, conservative neckline
- Skirt length: Knee-length or below; avoid anything above the knee
- Shoes: Closed-toe heels or block heels in black or nude; avoid very high stilettos
- Bag: Structured handbag or leather portfolio folder
- Jewellery: Minimal — small stud earrings, a simple watch or bracelet
________________________________________
Indian Formal (equally respected, especially in PSU banks, cooperative institutions, and traditional firms)
>
- Saree: Silk or cotton silk in muted, solid tones — navy, maroon, grey, or deep green; neatly draped
- Salwar Kameez: Formal churidar or straight-cut with dupatta, in solid or subtle prints; avoid overly embellished kurtas
- Dupatta: Neatly pinned or draped — avoid loose, flowing styles
- Footwear: Neat heels or flats; avoid chappals
________________________________________
General Tips for Finance Interviews in India
>
- Avoid bright, flashy colours or heavy embroidery
- Hair should be neatly tied or pinned — avoid loose, messy styles
- Keep makeup natural and understated
- Ironing and fit matter enormously — a well-fitted outfit signals attention to detail
- Carry a portfolio or structured bag rather than a casual backpack
________________________________________
For institutions like MMCCS, cooperative banks, or PSU banks, Indian formal wear is not only acceptable but often creates a strong, culturally aligned impression.


### 4.3 Limitations & Responsible Use

#### 4.3.1 Three Limitations encountered while working with LLMs

The limitations that were observed by me are the following:

**1. Factual accuracy and Bias:** The LLM displayed its boundaries during the temperature experimentation task —the model could not introspect its own server-side parameters. So, any explanation of how temperature "currently" affects its behaviour was based on generalised training knowledge rather than live, verifiable data, indicating that the analysis was directionally correct but may not be a real-time observation. Also, in this part 4 of the assignment, it searched only in Finance, medicine, HR. Unless prompted to search in History then Numismatics, the LLM displayed an inherent laziness to search based on the words like Dollar, sitio which was provided.

**2. Context understanding:** The LLM had a clear ceiling in the role and context tasks — while assigning the role of Marketing Manager and setting a water-scarce city context significantly improved output relevance, the model's understanding of that context remained surface-level, drawing on general knowledge of water scarcity. The limitation exhibited was at a superficial level rather than relying on a genuine familiarity with the specific city's infrastructure, culture, or community dynamics, which an expert in that field would bring.

**3. Reasoning ability** was most visibly constrained in the sentiment classification task — while Review 4 ("quality is okay but slightly overpriced") was correctly identified as mixed, the model acknowledged that without trained language patterns it would revert to basic keyword spotting, exposing how dependent nuanced reasoning is on learned associations rather than independent logical deduction. Additional learning is this could have been also classified as Positive to neutral rather than neutral to positive. Based on the sentences placement, it could have classified positive to neutral as a part of learning.

**4. Creativity** constraints surfaced in the tagline iteration task — despite multiple rounds of refinement and increasingly specific prompting, the model's creative output remained anchored to familiar marketing jargon and word patterns from its training data, making it difficult to produce a truly novel or culturally specific tagline that a local copywriter with lived community experience would instinctively generate. My tagline would probably be “ 1 Green (for Eco) for 1000 Blue (water) future” which would have played for any community water scarcity or not. 


#### 4.3.2 Three Recommendations for responsible LLM use:

**When should you verify outputs?**
>
1.	**When accuracy is non-negotiable.** Verification is essential whenever the output will be used in a professional submission, a client-facing document, or a high-stakes decision. In my assignment, the sentiment classification results looked confident and clean — but the model itself acknowledged that without trained patterns, classifications would collapse to keyword guessing. That same invisible fragility exists in any output the model presents with high confidence. Verify against primary sources, domain knowledge, or a subject matter expert before treating any LLM output as final.
2.	**Cross-check creative and analytical outputs for hidden assumptions.** The marketing tagline exercise showed that the model draws on generalised training patterns rather than real local knowledge — the water-scarce city campaign felt relevant, but was built on assumptions, not ground truth. Any time an LLM appears to "know" something specific — about a community, a regulation, a company, or a person — that knowledge should be independently confirmed rather than accepted at face value.
3.	**Treat LLM outputs as a strong first draft, not a finished product.** The temperature experimentation task and the email drafting exercise both demonstrated that LLMs produce structurally sound, well-phrased outputs quickly — but they require human judgment to refine tone, verify facts, and adapt to nuances no prompt can fully capture. The model does not know what it does not know, and that gap is our responsibility to close.

**What tasks are LLMs NOT suitable for?**
>
1.	LLMs are not suitable for tasks that require real-time or verified factual accuracy — such as legal judgments, medical diagnoses, regulatory compliance determinations, or financial advice — where an incorrect output carries serious consequences. 
2.	They are also not appropriate as a substitute for lived experience or specialist domain expertise, such as the marketing campaign exercise illustrated: the model can simulate the voice of a local marketer but cannot replace one. 
3.	Tasks requiring strict reproducibility — like scientific experiments or controlled evaluations — are also poorly suited to LLMs given their inherent non-determinism at higher temperatures.

**How can you use LLMs ethically in your work/studies?**
>
1.	As a business analyst and advisory consultant, ethical LLM use to me means being transparent about AI assistance in documents delivered to clients — particularly BRDs, proposals, and compliance-related content — so that stakeholders can apply appropriate scrutiny. 
2.	For me, it also means using the model as a drafting and structuring tool while retaining personal accountability for every claim, figure, and regulatory reference that appears in a final document. In my academic work, it means using LLM outputs to accelerate understanding and structure thinking, while ensuring the analysis, reflection, and conclusions are mine. 
3.	I must be mindful that LLMs can reflect and enhance biases present in training data, so any output touching on communities, demographics, or sensitive topics should be reviewed with that awareness before being used or shared.

