<p align="center">
    <a href="https://apps.apple.com/ca/app/ai-resume-writer/id6463698204">
        <img src="https://raw.githubusercontent.com/AI-Resume-Builder/AI-Resume-Builder.github.io/main/get-apple-store.jpg" alt="Available on the App Store" width="150">
    </a>
    <a href="https://play.google.com/store/apps/details?id=com.wloo.airesume">
        <img src="https://raw.githubusercontent.com/AI-Resume-Builder/AI-Resume-Builder.github.io/main/get-play-store.jpg" alt="Available on Google Play" width="150">
    </a>
</p>

## **[Download Now](https://apps.apple.com/ca/app/ai-resume-writer/id6463698204)**

Welcome to the official website of **AI Resume Writer**: Let AI Write your resume

---

## **[About](https://ai-resume-builder.github.io/)**

AI Resume Writer - the ultimate tool for crafting impressive resumes effortlessly. Say goodbye to hours of formatting and editing – with AI Resume Writer, you can create a polished and professional resume in a few minutes. Just answer 5 straightforward questions about your education, experience, and achievements, and watch as the magic unfolds.

## **[Features](https://ai-resume-builder.github.io/)**

- 🌟 **Quick and Beautiful**: Choose from our selection of over 15+ recruiter-screened templates to make sure your resume stands out.
- 🤖 **GPT-3.5 Powered**: Harness the power of cutting-edge AI technology to craft a memorable job application.
- 📝 **Personalized Edit Feature**: Effortlessly modify your resume and explore various templates to suit your unique needs.
- 📄 **Professional PDFs**: Receive your resume in a polished PDF format, perfect for both printing and digital sharing.
- 🔄 **Export Options**: Seamlessly export your resume for convenient sharing and collaborative editing.
- 🔐 **Privacy First**: Rest assured that your data remains yours. We prioritize privacy and maintain the utmost security for your information.

# The Story of AI Resume Writer Project -- By: Daniyal Mohammed

After I completed a project I'm truly proud of, I have a habit of chronicling the story of its creation and the journey it took to bring it to life. Today's story is about the AI Resume Writer project. In just two weeks, my team and I created and deployed a monetizable app on both the App Store and the Play Store, which I believe is the quickest and cleanest method to create a resume.

## The Beginning

The true start of this story goes back to the beginning of Summer 2023. I knew I wanted to create something impactful with a team. My prior internship at Cognixion, a neurotech startup, had taught me how to work effectively within a software team, giving me valuable insights into processes such as branches, pull requests, JIRA, estimating story points, and grooming sessions. Armed with this knowledge, I was excited to implement these practices in my own team. I was also determined to build something genuinely impactful, not just a cool technical project, but something that would have users and generate revenue.

## Idea Generation

With this mindset, I approached Ishan, and we began brainstorming ideas. We discussed numerous concepts, ranging from outrageously ambitious to mundane. Eventually, we stumbled upon the success of a simple Resume Generator app created by a mutual friend's previous manager. It was reportedly generating $10,000 in profit each month. This sparked our curiosity: How could we make it better? I suggested using the relatively new GPT API. What if we fed user input to GPT and let it create a polished, perfect resume? GPT was underutilized in such applications at the time.

## Developing the Concept

We started discussing technical requirements. What would we receive from GPT? How would we generate the resume? Should we develop on XCode or Flutter? We also contemplated how users would answer questions, whether they should be able to edit the resume afterward, and how to ensure a clean user flow.

The idea was intriguing, but initially, it was just a side project. We wondered how we could pitch it to a venture capitalist (VC). That's when I reached out to my co-op manager for advice. He emphasized that even if the idea might not launch a full-fledged company, the learning experience would be invaluable. It shifted my mindset entirely. Why not use this project to practice making a real-world impact, learn how to work effectively with others, lead a project, and take ownership of both its successes and failures? I shared this perspective with Ishan, and he agreed. We decided to dive in.

## Planning and MVPs

Our first step was to create a JIRA board and plan our approach. We decided to start by creating a prototype and then bringing others on as the codebase expanded. On August 20th, we had our initial planning session and set a tight timeline for each feature:

### Product Plan:
- **MVP V0.1 (EOD August 21st):** Ask one question (in a text box) → 1 query sent to chatGPT → get a reply from GPT.

- **MVP V0.5 (EOD August 23rd):** Ask one question (letting the user input everything GPT needs to know) → 1 query sent to chatGPT → display on a single template (even if it's basic) → export as a one-page PDF.

- **MVP V1 (EOD August 25th):** 10 questions to the user → 1 query sent to chatGPT → display on a single template → export as a PDF/send to a printer (and look decently good).

- **MVP V1.5 (EOD August 27 launch):** 10 questions to the user → 1 query sent to chatGPT → display on a single template → export as a PDF (throttle control/self-sustaining).

- **MVP V2 (EOD September 2nd):** 10 questions to the user → 1 query sent to chatGPT → display on multiple templates (in-app purchases) → export as PDF OR docx.

- **MVP V2.5 (planned for later):** 10 questions to the user OR importing an existing resume → 1 query sent to chatGPT → export on multiple templates (in-app purchases) with color-changing functionality → new page to edit the app → export as PDF OR docx.

*Note: EOD means end of day.*

We aimed to release the app before the start of school and co-op, so our deadlines were exceptionally tight. However, this approach helped us stay focused and on track. Despite some pivots along the way, we stuck to our original timeline and completed everything we needed by EOD September 3rd, with only a one-day delay.

## Iteration and Progress

After each MVP deadline, we reviewed the past "sprint" and refined tasks for the next one. These meetings and the entire process integrated seamlessly, despite the long, grueling, and stressful days.

## Learning and Growth

This project was not only technically challenging but also a tremendous learning experience. I learned to think from a product perspective rather than just a technical one, considering user flow, minimizing pain points, and even marketing strategies. We created a character named Blake, representing our target audience—a person with experience at McDonald's seeking a cashier job at Walmart, recommended by a friend.

I invited a friend interested in UX design to join us, helping create wireframes and enhance user flow. Additionally, two friends helped with marketing, with TikTok identified as the best platform, both cost-effective and in line with our target audience.

Eventually, we brought on 12 more team members, ranging from my little sister in Grade 8 to experienced developers, data scientists, and business students. I took on a leadership role, mentoring and managing most of them. Learning these soft skills to motivate and guide others was incredibly valuable, and I thoroughly enjoyed the experience.

## Technical Contributions

In terms of technical work, I implemented the GPT API, engaged in prompt engineering, and ensured rate limiting worked effectively. I also worked on creating the question flow page and UI in Flutter, gaining insights into page controllers and navigation contexts. Additionally, I used RevenueCat to implement in-app purchases, a time-consuming challenge. I reviewed every pull request and had a hand in almost every part of the app, fixing bugs and providing implementation advice.

## Conclusion

In conclusion, those two weeks were incredibly stressful but also highly rewarding. I had the opportunity to lead a mini-startup, problem-solve from a product perspective, and be a technical mentor for the first time. The next steps involve marketing the app and assessing its revenue generation. As I'm writing this, the app is on the Play Store and awaiting review on the App Store (we faced two rejections for minor errors). Phase 2 of marketing will begin soon, and we will discover if AI Resume Writer can generate revenue and attract users.



## **[Feedback](https://ai-resume-builder.github.io/)**

We're always eager to hear from our users! If you have any feedback or suggestions, or if you'd like to contribute to the project, please don't hesitate to get in touch **[here](https://forms.gle/dkonS5PPThD3oqVB7)**.

<img src="https://raw.githubusercontent.com/AI-Resume-Builder/airesumewriter.github.io/main/Group%2040.png" width="200"> 
