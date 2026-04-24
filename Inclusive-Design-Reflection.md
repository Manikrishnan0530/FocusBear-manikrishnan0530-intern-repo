# Working with Vulnerable Populations
## Research & Learning

### Who Are Vulnerable Populations in a Digital Context?

When I think about vulnerable populations in the context of an app like Focus Bear, I think first and foremost about people with ADHD and Autism — because that's exactly who we are building for. These are people who may experience:

- **Sensory overload** from cluttered interfaces, animations, or notification noise
- **Executive dysfunction** — genuine difficulty initiating tasks, switching between them, or knowing where to start
- **Anxiety triggered by unpredictability** — unexpected UI changes or inconsistent behaviour can feel genuinely distressing, not just annoying
- **Cognitive fatigue** from having to decode unclear instructions or navigate complex flows

Beyond ADHD and Autism, vulnerable populations also include elderly users, people with mental health conditions, and anyone with low digital literacy. Each group brings different challenges, but the common thread is that poorly designed digital experiences don't just frustrate them — they can actively exclude or harm them.

### Ethical Considerations When Designing for Neurodivergent Users

Ethical design for neurodivergent users isn't about ticking accessibility checkboxes — it's about genuinely reducing cognitive and emotional load at every level. That means:

- **Never overwhelming** — keep interfaces simple, calm, and predictable. Every unnecessary element competes for attention that the user is already fighting to hold.
- **Respecting sensory needs** — avoid flashing animations, jarring sounds, high-contrast clutter, or anything that creates a sensory spike during a moment when the user is trying to focus.
- **Communicating clearly** — no jargon, no ambiguous instructions, no UI copy that requires interpretation. If a user has to stop and think about what a button does, that's a design failure.

These three principles aren't independent — they compound each other. An app can have calm visuals but still overwhelm through unclear language. Getting all three right together is what makes a product genuinely supportive.

### Making Focus Bear More Accessible for ADHD and Autism Users

Accessibility for neurodivergent users isn't one fix — it's a layered approach where each element reinforces the others:

- **Simple, plain language** removes friction before the user even begins a task.
- **Predictable navigation** means users never have to waste mental energy re-orienting themselves.
- **Reduced cognitive load** — fewer choices at once, clear next steps, no decision paralysis.

Together, these create an environment where the app feels like it's working *with* the user's brain, not against it.

### Supporting Neurodivergent Teammates in a Remote Setting

Some of our own teammates at Focus Bear may be neurodivergent, and the same care we give our users should extend to our colleagues. A low-friction, respectful working environment means:

- **Being explicit in communication** — don't assume people will read between the lines. Say what you mean, clearly.
- **Respecting different working rhythms** — flexibility isn't a perk, it's an accessibility need for many people.
- **Avoiding last-minute changes** — unpredictability creates anxiety. If something is changing, communicate it early and clearly.

The goal is to make collaboration feel safe, not effortful.

## Reflections

### How I Can Adjust My Communication Style

I want to be more intentionally inclusive in how I communicate — not just with users, but with teammates too. That means:

- Using shorter sentences and avoiding ML/technical jargon when context doesn't require it
- Being more patient and explicit — spelling things out rather than assuming people will fill in gaps
- Checking in more often, rather than assuming that silence means everything is fine

I have realised that being inclusive isn't a one-time adjustment — it's a continuous practice of asking myself: *"Is this clear to someone who processes information differently than I do?"*

### UX and Communication Pitfalls That Could Hurt Focus Bear Users

The biggest risk I see is **too many notifications or prompts at once**. For someone who already struggles with focus and task initiation, being bombarded with reminders doesn't help — it adds to the overwhelm and can make the app feel like another source of stress rather than a relief from it.

If a user is already fighting their brain to get started, the last thing they need is an app that keeps interrupting them. Every unnecessary notification is a small betrayal of the trust a vulnerable user placed in the product.

### One Practical Change I Will Make

Going forward, I will **write clearer, jargon-free documentation and code comments**. As an ML engineer, a lot of what I produce is read by others — teammates reviewing my work, future contributors, or even non-technical stakeholders. Writing with clarity and accessibility in mind isn't just good practice — it's a form of respect for whoever reads it next, including colleagues who may process information differently.

## Tasks

### Task 1 — First-Person Account: What I Read and What I Took Away

**Source:** ["When Productivity Techniques Meet AuDHD"](https://autisticfish.medium.com/when-productivity-techniques-meet-audhd-4d4bdfc81791) by *Autistic Fish*, Medium — November 2024

This blog post is written by someone diagnosed late in life with both Autism and ADHD (AuDHD). Their psychologist recommended the well-known Pomodoro Technique — 25-minute focus blocks followed by 5-minute breaks. The author explains, through lived experience, why it completely failed them.

What struck me reading this was how the whole article exposes a fundamental blind spot in mainstream productivity tools: **they are designed for neurotypical brains and then applied to everyone**. The author makes this painfully clear — standard tools assume that starting a task is easy, that time feels consistent, and that a timer interrupt won't derail your entire flow. For an AuDHD brain, none of those assumptions hold.

Three things in particular stood out:

- **Starting is the hardest part.** Not the task itself — getting started. A rigid Pomodoro timer does nothing to help with task initiation, which is where AuDHD users struggle most.
- **Time blindness is real.** For neurotypical people, 25 minutes feels roughly like 25 minutes. For AuDHD brains, the same stretch can feel like an eternity or vanish in a flash depending on the task. Rigid intervals ignore this completely.
- **Hyperfocus is both a gift and a vulnerability.** When someone with AuDHD finally reaches deep focus — a rare and precious state — an arbitrary timer interrupt shatters it. The tool designed to help becomes the obstacle.

The core lesson: building for neurodivergent users means questioning the assumptions baked into every design decision, not just adapting existing neurotypical patterns.

### Task 2 — Design Improvement for Focus Bear

**Proposed improvement: Flexible, penalty-free timers**

Based on the blog, the most impactful improvement Focus Bear could make is allowing users to **extend or pause focus sessions without friction or penalty**. Rigid time blocks risk the same failure mode the author described with Pomodoro — they assume a consistent relationship with time that AuDHD brains simply don't have.

A flexible timer would mean:
- Users can tap "extend" to stay in a focus block if they are in flow, without the session ending abruptly
- Pausing doesn't count as failure or reset progress
- The app adapts to the user's rhythm rather than imposing a fixed one

This small change would make Focus Bear feel *supportive* rather than *demanding* — which is exactly the difference between a tool that sticks and one that gets abandoned.

### Task 3 — Practice: Responding to a Struggling User

**Hypothetical user message:**
> *"I keep opening Focus Bear but I just can't start. I feel stuck and frustrated. Nothing is working."*

**My response:**

> Hey — that feeling is really tough, and I want you to know it makes complete sense. Getting started is genuinely one of the hardest parts, especially when your brain isn't cooperating. You're not doing anything wrong.
>
> Let's make it as small as possible. Don't think about the task — just open a **2-minute session** on anything at all. Not to be productive. Just to begin.
>
> That's it. Two minutes. You've got this. 

*The approach: validate first without minimising, keep the message short so it doesn't add to overwhelm, and give exactly one small and achievable next step. No lists, no advice overload — just a warm, human voice and a single gentle nudge forward.*
