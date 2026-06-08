# Prompt Engineering Portfolio
Name: Shivangee Solanki
Date: 8th June 2026
LLM Used: ChatGPT-5.5

## Part 1: Prompt Design & Iteration

### 1.1 Scenario A: Technical Explanation

## Goal

Explain the concept of **Machine Learning** to a 10-year-old child.

---

## Initial Prompt (V1)

Explain Machine Learning to a 10-year-old child.

### Output (V1)

Machine Learning is a type of artificial intelligence where computers learn from data instead of being directly programmed. The computer looks at many examples and finds patterns. It then uses those patterns to make predictions or decisions.

### Issue with Output

The explanation uses terms like "artificial intelligence," "data," and "predictions," which may be difficult for a 10-year-old to fully understand. It also lacks relatable examples.

---

## Refined Prompt (V2)

You are an elementary school teacher. Explain Machine Learning to a 10-year-old child using simple language and a real-life example. Avoid technical terms and keep the explanation under 150 words.

### Output (V2)

Machine Learning is like teaching a computer how to recognize things by showing it lots of examples. Imagine you are learning to tell the difference between cats and dogs. The more pictures you see, the better you get at spotting the differences.

A computer can learn in a similar way. If it sees many pictures of cats and dogs, it starts noticing patterns and can guess whether a new picture is a cat or a dog.

### Issue with Output

The explanation is simpler and includes an example, but it could be more engaging and memorable for a child.

---

## Refined Prompt (V3 - Final Prompt)

You are a fun and friendly teacher explaining technology to a curious 10-year-old. Explain Machine Learning using simple words, a relatable example, and a short analogy. Avoid technical jargon. Make the explanation engaging and easy to remember.

---

## Final LLM Response

Imagine you have a friend who is learning to sort fruits. At first, they might not know the difference between apples and oranges. But after seeing lots of examples, they start noticing clues like color, shape, and size.

Machine Learning works in a similar way. Instead of giving a computer every rule, we show it many examples. The computer studies those examples and learns patterns on its own.

For example, if a computer sees thousands of pictures of cats and dogs, it can learn what makes a cat look different from a dog. Later, when it sees a new picture, it can make a good guess about which animal it is.

Think of Machine Learning as teaching a computer the same way a student learns from practice. The more examples it sees, the smarter it becomes at recognizing things and making decisions.

### 1.1 Scenario B: Professional Email

## Goal

Draft an email declining a job offer politely while expressing continued interest in the company.

---

## Initial Prompt (V1)

Write an email declining a job offer.

### Output (V1)

Dear Hiring Manager,

Thank you for the job offer. I have decided not to accept it at this time. I appreciate the opportunity and wish your company success.

Sincerely,
[Your Name]

### Issue with Output

The email is polite but very brief. It does not explain appreciation for the offer or express interest in future opportunities with the company.

---

## Refined Prompt (V2)

Write a professional email declining a job offer politely. Thank the company for the opportunity and express interest in working with the company in the future.

### Output (V2)

Dear Hiring Manager,

Thank you for offering me the position. After careful consideration, I have decided to decline the offer. This was a difficult decision because I have great respect for your organization.

I truly appreciate the time and effort invested in the interview process. I hope to stay connected and would welcome the opportunity to work with your company in the future.

Best regards,
[Your Name]

### Issue with Output

The email is more professional and appreciative, but it could sound warmer and provide a clearer reason for declining without being overly detailed.

---

## Refined Prompt (V3 - Final Prompt)

You are a professional career advisor. Write a polite and professional email declining a job offer because another opportunity was accepted. Express sincere gratitude for the offer, appreciation for the interview process, and continued interest in the company for future opportunities. Keep the tone respectful, positive, and concise.

---

## Final LLM Response

Subject: Thank You for the Opportunity

Dear Hiring Manager,

Thank you very much for offering me the position at your company. I sincerely appreciate the time and effort you and the team invested throughout the interview process.

After careful consideration, I have decided to accept another opportunity that aligns more closely with my current career goals. As a result, I must respectfully decline your offer.

This was not an easy decision, as I was genuinely impressed by your organization, its culture, and the professionalism of everyone I met during the hiring process.

I am grateful for the opportunity to learn more about your company and hope our paths may cross again in the future. I would welcome the chance to be considered for future opportunities.

Thank you again for your understanding, and I wish you and your team continued success.

Kind regards,

[Your Name]

### 1.1 Scenario C: Creative Content

## Goal

Generate a creative marketing tagline for a new eco-friendly water bottle brand.

---

## Initial Prompt (V1)

Create a tagline for an eco-friendly water bottle brand.

### Output (V1)

"Stay Hydrated, Stay Green."

### Issue with Output

The tagline is clear but generic. It does not stand out from existing sustainability slogans and lacks creativity.

---

## Refined Prompt (V2)

Create five creative taglines for an eco-friendly water bottle brand. Focus on sustainability, reducing plastic waste, and healthy living.

### Output (V2)

1. Drink Smart, Live Green.
2. Every Sip Saves the Planet.
3. Refresh Yourself, Respect Nature.
4. Refill Today, Protect Tomorrow.
5. Hydration with a Purpose.

### Issue with Output

The taglines are more varied, but many still sound like common environmental slogans. They need stronger branding and emotional appeal.

---

## Refined Prompt (V3 - Final Prompt)

You are an award-winning marketing copywriter. Create 10 short, memorable, and original taglines for a modern eco-friendly water bottle brand. The brand targets environmentally conscious young adults. Emphasize sustainability, reducing single-use plastic, and making a positive impact. Use creative and inspiring language that is easy to remember.

---

## Final LLM Response

1. Sip Clean. Live Green.
2. Refill the Bottle, Renew the Planet.
3. Every Refill Writes a Better Future.
4. Drink Bold. Waste Less.
5. Small Bottle, Big Impact.
6. Hydrate Responsibly.
7. Carry Water, Not Waste.
8. One Bottle. Endless Refills.
9. Your Daily Sip for a Greener Tomorrow.
10. Choose Reuse. Choose Change.

### Selected Best Tagline

**"One Bottle. Endless Refills."**

This tagline is short, memorable, and directly communicates the product's eco-friendly value by encouraging reusable habits and reducing plastic waste.


### 1.2 Iteration Documentation

| Version | Prompt                                                                                                                                                                                                                                                | What Changed                                                                                                           | Why This Improved the Output                                                                |
| ------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| V1      | Explain Machine Learning to a 10-year-old child.                                                                                                                                                                                                      | N/A                                                                                                                    | N/A                                                                                         |
| V2      | You are an elementary school teacher. Explain Machine Learning to a 10-year-old child using simple language and a real-life example. Avoid technical terms and keep the explanation under 150 words.                                                  | Added a role (elementary school teacher), specified the audience, requested simple language and a real-life example.   | The explanation became easier for children to understand and included relatable examples.   |
| V3      | You are a fun and friendly teacher explaining technology to a curious 10-year-old. Explain Machine Learning using simple words, a relatable example, and a short analogy. Avoid technical jargon. Make the explanation engaging and easy to remember. | Added a friendly teaching role, requested an analogy, emphasized engagement, and instructed the model to avoid jargon. | The output became more engaging, memorable, and age-appropriate while maintaining accuracy. |

### 1.3 Role and Context Analysis

## Part 2: Temperature & Parameter Control
### 2.1 Temperature Experimentation
### 2.2 Analysis & Recommendations

## Part 3: Strategic Prompting Techniques
### 3.1 Chain-of-Thought Prompting
### 3.2 Few-Shot Prompting

## Part 4: Responsible AI & Limitations
### 4.1 Testing for Hallucinations
### 4.2 Testing for Bias
### 4.3 Limitations & Responsible Use
