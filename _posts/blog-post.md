---
layout: post
title: "Hello World"
date: 2024-12-27
---

# My Hertz Fellowship Application and Interview Experience

## Application Components

The Hertz Fellowship application includes these main essay questions:

1. **Brief Essays (~300 words each)**
   - Question 1: How did you choose your field and what are your primary expectations of your future career?
   - Question 2: How does your proposed field of study and career constitute an application of the physical sciences or engineering?
   - Question 3: What are the considerations involved in your choice of graduate school?
   - Question 4: Chronological Synopsis (technical activities since high school)

2. **Personal Essay** (< 2 pages, 11pt font, single-spaced)
   - Focus on personal creativity beyond research

3. **Academic Honors and Fellowships**

4. **Previous Research and Projects**

## Writing the Application

I took the essay from my NSF GRFP application, subsetting the research experience part of my personal statement and added broader impacts throughout the research statement paragraphs. This meant I didn't have to worry about integrating the rest of my activities. I used AI to write an intro connecting my leadership and research creativity to my experience with music, leading singing groups, and solo singing in bands throughout my life. I wrapped up with my goals in graduate school.

Throughout the essay, I included key elements everyone looks for: examples of independence, collaboration, self-taught skills, interest, creativity (big for Hertz), and impact. It's important to explain why you want to go to grad school, framing it like "this is why I'm prepared for grad school." This can be a paragraph at the end, along with specifically mentioning the Hertz Fellowship and how it would help extend that creativity to your graduate school experience.

Here's an example structure of how I organized my personal essay:

**Introduction (Non-Research Story)**
- Twenty years of musical experience, focusing on vocal performance
- Leadership as president of college a cappella group
- Demonstrated creativity through arranging music and organizing performances
- Showed how performing taught me about preparation, presentation, and collaboration

**Research Experience (Modified from NSF Essay)**
- First Research Experience (Computational Lab):
  * Identified gap in neural network analysis tools
  * Self-taught deep learning frameworks
  * Developed open-source extensions to existing packages
  * Showed independence and quick learning ability

- Second Research Experience (Biology Lab):
  * Applied computational skills to biological questions
  * Initiated own projects and analyses
  * Demonstrated creativity in finding novel connections
  * Published findings and mentored others

- Current Research Position:
  * Leading collaborative projects
  * Developing new analytical tools
  * Making impact through open-source contributions
  * Building bridges between computational and experimental biology

**Conclusion**
- Connected musical creativity to scientific innovation
- Explained how Hertz Fellowship would enable creative freedom in research
- Outlined specific goals for graduate school
- Emphasized commitment to collaborative science

## The Interview Process

I was notified that I was chosen for an interview as part of the 12% of applicants selected. The interview was scheduled for mid-December. My preparation included reading other people's blogs and getting into the mindset of answering problem-solving questions. I also practiced basic probability questions since I had never taken probability and had seen they were popular questions.

The interviewers were two previous Hertz fellows - a postdoc studying complex chemistry and an assistant professor in biostats/epidemiology. Looking into their backgrounds didn't prove very useful for the interview.

The interview structure:
- 5-minute introduction about myself and research experience
- 15-minute slot to speak about creativity with an example
- Technical interview portion

The creativity section wasn't my best - my example was from years ago so I couldn't explain everything fluently. I recommend planning for this with a recent, specific example where you know all the details.

The technical section started with designing biological AND and OR gates. For the AND gate, I discussed cooperative binding between transcription factors leading to reporter gene transcription. For the OR gate, I described two proteins detecting different molecules with the same reporter.

When asked about an XOR gate, I struggled and tried using fluorescence. They asked me to describe fluorescence, and at that point I thought, "just talk through what I'm thinking and if I'm crazy then I'm crazy. If I'm spitting facts then so be it."

I rambled about fluorescence and got confused about luminescence. They helped clarify the distinction, though I was flustered with the molecular explanation. We discussed invisible pens and UV light, and I tried to work through my understanding while acknowledging when their corrections made more sense.

With ten minutes left, they asked about cooperative binding and protein interactions. The final five minutes featured a probability question about a LinkedIn conference pairing system. Having prepared for probability questions, I recognized it as a classic "probability that at least one" problem and solved it with 1 - [(N-1)/N]^N.

Currently waiting to hear back about the results.

## Interview Questions

Here are the exact technical questions I was asked during the interview:

1. "Please design a biological AND gate and a biological OR gate."

2. "Design an XOR gate." (Following discussion of AND/OR gates)

3. "Can you describe fluorescence?" (After I mentioned fluorescence in my XOR gate attempt)

4. "How do invisible pens work where you shine UV and all of a sudden you see a secret message?"

5. Questions about cooperative binding and protein interactions (towards the end)

6. Probability Question: "You go to a LinkedIn conference and you are paired up with someone random on the attendance list. That list contains yourself, so there's a chance you get paired up with yourself. What's the probability you get yourself?"
   - Follow-up: "What's the probability that at least one person at the conference gets paired with themselves?"
   - Additional follow-up: "What does this approach as N goes to infinity?"
