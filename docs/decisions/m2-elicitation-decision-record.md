# M2 Elicitation Decision Record

## Investigation Path
1. What exactly do stakeholders mean by “students shouldn’t lose their work”?
   Evidence revealed: Teachers report that students may pause practice and return later. They want a learner’s saved practice state to remain available after leaving and returning to the application.
2. What does “modern” need to mean from a user perspective?
   Evidence revealed: Stakeholders say modern means the experience should work reliably in a browser, be understandable without a printed manual, and avoid making the learner navigate unnecessary screens. They do not specify a visual style or framework.
3. Who will use the system and in what setting?
   Evidence revealed: The primary learner is a student practicing independently, often with a teacher or parent nearby. Exact device and access conditions have not yet been confirmed.

## Initial Position
**Supported evidence:**
teachers said students may pause practice and come back later, and they want the saved practice state to still be there after leaving and coming back to the app. stakeholders said modern means it works reliably in a browser, can be understood without a printed manual and does not make the learner go through unnecessary screens. they did not pick a visual style or framework. the main user is a student practicing on their own, often with a teacher or parent nearby

**Remaining uncertainty:**
what devices and access conditions students will use, since that has not been confirmed yet. what exactly counts as work to save (progress in an activity, scores, settings) and how long it should be kept. whether students will have their own accounts. what parents or teachers need to see about learner activity and which original dataman behaviors have to stay, since i did not ask about those

**Likely functional requirement:**
the system shall save a learner's practice progress so they can leave the app and come back later and continue from where they stopped

**Likely non-functional requirement / quality constraint:**
a new learner should be able to start a practice activity in a web browser without a printed manual and without going through unnecessary screens

**Assumption or proposed solution I am not treating as confirmed:**
user accounts with a login and a specific database to store progress. those are ways to build the save feature, but stakeholders never asked for them. they only said students should not lose their work

**Why my initial position is defensible:**
both requirements come straight from evidence i gathered (evidence 1 and 2) and the user description in evidence 3. anything nobody confirmed, like devices, accounts, a database or a visual style, is listed as uncertain or as an assumption instead of being written as a requirement

## Complication
Students may use DataMan on school Chromebooks, phones, tablets, and home computers. Some sessions may be interrupted before intentional sign-out.

**What this affects:**
it affects both requirements. if sessions can get interrupted before students sign out, then saving progress only when they sign out would not be enough. it also changes what works reliably in a browser means, since it now has to work on chromebooks, phones, tablets and home computers with different screen sizes. it also brings up a new question about whether progress has to follow a student from one device to another

**What I revised, if anything:**
functional requirement: the system shall automatically save a learner's practice progress while they practice, so if the session gets interrupted they can come back and continue from where they stopped. non-functional requirement: a new learner should be able to start a practice activity without a printed manual or unnecessary screens in a web browser on a chromebook, phone, tablet or home computer

**Final decision and reasoning:**
revise. the new information answers part of what i listed as uncertain (devices and access) and shows that my first save requirement could fail if a session ends without signing out, so both requirements get updated. i am deferring whether progress has to carry over between different devices, like starting on a school chromebook and finishing at home, and reopening that as a question for stakeholders. that would need some way to identify the learner, like accounts, and nobody has confirmed that, so i am still not treating accounts or a database as a requirement

## Next Project Action
Use this evidence to update the DataMan Requirements Register and preserve any unresolved questions as open assumptions or follow-up items.
