---
title: "Your Students Don't Use LLMs Like You Wish They Did"
date: 2026-04-19
summary: "We studied 500 real student-AI conversations and found that students mostly use AI tutors to extract answers, not to learn."
---

I've been tutoring for a while now, and over the last couple of years something changed. Every student started using AI tools. Not occasionally, not just the ones who were struggling, but everyone. And the more I watched, the less convinced I became that this was the good thing people assumed it was.

So when universities started deploying LLM-based tutors, I wasn't surprised that students liked them. Of course they did. These tools are articulate, patient, and available at 2am the night before an exam. What worried me was that everyone seemed to be treating high satisfaction as evidence that the tools were working. I looked at 10 recent papers that evaluated AI tutors with real students, and 9 of them relied on satisfaction surveys or self-reported learning gains. Nobody was checking whether students were actually learning.

That's what this paper tries to address. We built six computational metrics to measure what students actually do in conversations with AI tutors, and applied them to 12,650 messages across 500 conversations from four university courses.

The short version: students use these tools to get answers, not to learn. On the unrestricted platform we studied, 92% of conversations were answer-seeking. Only 2% were genuinely exploratory. When the AI tried to guide students with questions instead of giving direct answers, about half the students just ignored the guidance entirely. Another 20% rephrased their question to work around it. They weren't engaging with the teaching. They were trying to get past it.

The temporal patterns were just as telling. In one course, 59% of all usage for the entire semester happened during a single exam week. These tools weren't being used as learning companions. They were emergency services.

What surprised me most was the relationship between engagement and learning. The platform with the highest engagement scores had the worst learning orientation. Students were having longer, more conversational interactions, but those conversations were in service of extracting answers more efficiently, not understanding the material. There's a concept in psychology called the "illusion of fluency" where when an interaction feels smooth, people mistake that smoothness for comprehension. That's exactly what we saw. And it means that if we keep using satisfaction as our metric, we'll keep building tools that feel great and teach nothing.

The finding I keep coming back to, though, is about deployment. The same kinds of students, using similar AI tools, behaved completely differently depending on how the tool was integrated into the course. When it was optional, it became a cramming tool. When it was built into weekly assignments, usage spread across the semester, though students still mostly sought answers. The technology mattered less than the context around it.

Our metrics aren't perfect. Automated detection of some behaviours, like distinguishing genuine problem solving from disguised homework copying, is genuinely hard and we're honest about where our approach falls short. But they're a start at measuring what actually matters instead of what's easy to measure.

The paper is [available here](/files/your_students_dont_use_llms.pdf) and will appear at ACL 2026.
