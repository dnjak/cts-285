# Analyst's Case File

**System analyzed:** DataMan (Texas Instruments, 1977)
**Feature assigned:** Number Guesser
**Source document:** *The Story of DataMan* — manual transcript

**Your name:** Daniel Njaka
**Date:** October 27, 2026

---

## 1. Purpose

Why does this feature exist? What problem does it solve for the user?

| Finding | Evidence (exact quote) | Section |
|---|---|---|
| part I says the game exists so people can have fun with numbers | "One thing that annoys AntiMath and makes him green with envy is people having fun with numbers and mathematics!" | Number Guesser (Story) |
| part I claims playing builds math skills this is a claim not something the system does | "you'll be sharpening your math skills" | Number Guesser (Story) |
| part II calls it a strategy game for the whole family | "an educational game of number strategy the whole family will enjoy" | Electro Flash · Number Guesser · Wipe Out (Operating Notes) |
| part II claims it teaches betweenness and number logic this is a claim about learning so it goes here and not under processing | "Number Guesser helps to teach the important basic concept of number betweeness … and number logic." | Electro Flash · Number Guesser · Wipe Out (Operating Notes) |
| part II claims the strategy builds estimation and averaging skills this is also a claim not system behavior | "The strategy involved in getting to the answer in the fewest tries will help build skills in estimation and averaging." | Electro Flash · Number Guesser · Wipe Out (Operating Notes) |
| the whole product is meant to make math fun for kids | "DataMan™ is designed to bring extra fun, excitement, and enrichment to a child's experiences with mathematics." | Hints for Parents and Teachers |

---

## 2. Users and Roles

Who interacts with this feature? Where a feature involves more than one person, name what each one *does*.

| Role | What this role does | Evidence (exact quote) | Section |
|---|---|---|---|
| dataman not a person | picks the secret number no person ever does this unlike memory bank where people type in the problems | "I'll pick a secret number for you to guess." and "a secret number between 9 and 100 that DataMan has selected" | Number Guesser (Story) and Electro Flash · Number Guesser · Wipe Out (Operating Notes) |
| starter | turns dataman on and picks the game the manual never says if this has to be the same person who guesses | "Just press ON and the Number Guesser key: [???]" | Number Guesser (Story) |
| guesser | types in guesses until they find the secret number | "You enter your guess." and "As you enter each guess" | Number Guesser (Story) and Electro Flash · Number Guesser · Wipe Out (Operating Notes) |
| solo player | plays alone and does both jobs only part I says this | "(or just by yourself)" | Number Guesser (Story) |
| competing players | take turns guessing and try to use the fewest guesses the manual never says dataman compares their scores | "Take turns with your friends trying to guess the secret number in the fewest tries." and "Children can take turns seeing who can find a secret number in the least guesses!" | Number Guesser (Story) and Electro Flash · Number Guesser · Wipe Out (Operating Notes) |
| parent or teacher | reads the story out loud to a young kid and tries the games too this advice is for every key not just number guesser | "If your child is very young, you might want to read aloud through the story that describes each DataMan key and try out the activities yourself." | Hints for Parents and Teachers |

---

## 3. Inputs

What information or action enters the system? Include keystrokes, choices, and anything the system refuses to accept.

| Input | Supplied by | Evidence (exact quote) | Section |
|---|---|---|---|
| the ON key pressed first | starter | "first turn DataMan on with the ON key" | Electro Flash · Number Guesser · Wipe Out (Operating Notes) |
| the number guesser key part I shows it as [???] and part II calls it [NUMBER GUESSER] | starter | "Just press ON and the Number Guesser key: [???]" and "then press the [NUMBER GUESSER] key" | Number Guesser (Story) and Electro Flash · Number Guesser · Wipe Out (Operating Notes) |
| a number typed in as a guess | guesser | "You enter your guess." and "As you enter each guess" | Number Guesser (Story) and Electro Flash · Number Guesser · Wipe Out (Operating Notes) |
| pressing [???] again to start a new round with a new secret number only part I says this | starter or next player | "I'll pick a new secret number each time you press [???]" | Number Guesser (Story) |
| refused input neither number guesser section says any input gets refused the digit limits and the no negatives rule are only stated for answer checker so i did not use them here see section 8 | n/a | n/a | checked Number Guesser (Story) and Electro Flash · Number Guesser · Wipe Out (Operating Notes) and Answer Checker (Operating Notes) |

---

## 4. Processing

What does the system do with the input? Include any rule, limit, or constraint you can support.

| Rule or behavior | Evidence (exact quote) | Section |
|---|---|---|
| dataman picks a secret number between 9 and 100 both parts give the same range | "It will be somewhere between 9 and 100." and "a secret number between 9 and 100 that DataMan has selected" | Number Guesser (Story) and Electro Flash · Number Guesser · Wipe Out (Operating Notes) |
| the secret number is always between the two numbers dataman shows both parts say this | "The secret number is always somewhere between the two numbers I show you." and "the unknown secret number is always between the two numbers shown in DataMan's display" | Number Guesser (Story) and Electro Flash · Number Guesser · Wipe Out (Operating Notes) |
| dataman gives a new hint after every guess | "As you enter each guess, DataMan provides a hint by displaying two numbers that the secret number is between." | Electro Flash · Number Guesser · Wipe Out (Operating Notes) |
| dataman knows when you guess the right number and that ends the round | "When the secret number is found, DataMan rewards you" | Electro Flash · Number Guesser · Wipe Out (Operating Notes) |
| dataman counts how many guesses you made | "displays the total number of guesses that were taken" | Electro Flash · Number Guesser · Wipe Out (Operating Notes) |
| pressing the game key picks a new secret number only part I says this | "I'll pick a new secret number each time you press [???]" | Number Guesser (Story) |
| pressing ON sends dataman back to answer checker which is why you press ON first and then the game key | "[ON] Turns power on and returns machine to the Answer Checker mode." | Hints for Parents and Teachers |
| dataman turns itself off after about 5 minutes of nobody using it no matter what mode it is in | "After about 5 minutes of non-use, he will automatically turn himself off." | Hints for Parents and Teachers |

---

## 5. Outputs

What information does the system return to the user?

| Output | When it appears | Evidence (exact quote) | Section |
|---|---|---|---|
| the two hint numbers they are both an output and feedback so i only listed them once under section 6 | after each guess | see section 6 | see section 6 |
| a flash only part I says this and it never says what the flash means by itself | after each guess | "When you do, I'll flash and show you two numbers in my face mask." | Number Guesser (Story) |
| how many guesses it took | when you find the secret number | "I'll show you the number of tries it took" and "displays the total number of guesses that were taken" | Number Guesser (Story) and Electro Flash · Number Guesser · Wipe Out (Operating Notes) |

---

## 6. Feedback

How does the system respond to the user's actions? Feedback tells the user how they are doing.

| Feedback behavior | What it tells the user | Evidence (exact quote) | Section |
|---|---|---|---|
| the hint numbers both output and feedback it is an output because it gives you information and it is feedback because it tells you how you are doing part II even calls it "a hint" | a range the secret number is in | "I'll flash and show you two numbers in my face mask. The secret number is always somewhere between the two numbers I show you." and "DataMan provides a hint by displaying two numbers that the secret number is between." | Number Guesser (Story) and Electro Flash · Number Guesser · Wipe Out (Operating Notes) |
| the light show | that you found the secret number part II calls it a reward | "and then a great light show!" and "DataMan rewards you with a spectacular "light show"" | Number Guesser (Story) and Electro Flash · Number Guesser · Wipe Out (Operating Notes) |
| light shows used as a reward all across the product which explains why one shows up here | that you got something right or did well | "DataMan motivates your child positively by rewarding right answers and good scores with a dazzling "light show."" | Hints for Parents and Teachers |

---

## 7. Observations and Assumptions

List three statements you were tempted to write as fact but could not fully support. For each, say what evidence you would need.

| Statement | Observation or assumption? | What evidence would settle it? |
|---|---|---|
| the two hint numbers are your closest too low and too high guesses so the range gets smaller each time | assumption both parts only say the secret number is "between the two numbers" shown in Number Guesser (Story) and Electro Flash · Number Guesser · Wipe Out (Operating Notes) neither one says where those two numbers come from | an operating note that explains how the hint numbers are picked or a test on a real dataman or an emulator where i write down each guess and the hint it gave |
| number guesser is timed like electro flash and memory bank | assumption DataMan's Timer only says "certain DataMan activities" are timed and never lists which ones both number guesser sections only talk about a guess count "the number of tries it took" and "the total number of guesses that were taken" and never mention ticks | a list of which games are timed a number guesser score example with a time in it or watching if the timer lights spin during a round |
| a wrong guess makes dataman show EEE like a wrong answer in answer checker | assumption EEE is described for wrong answers in Please Try Me Out · Score · Division · Turning Off "I'll let you know by flashing EEE" and Answer Checker (Operating Notes) for number guesser both parts only describe a flash and two numbers after each guess and EEE never comes up | a number guesser section that mentions EEE or watching what dataman shows after a wrong guess |
| the secret number is picked at random | assumption the manual says dataman will "pick" the number in Number Guesser (Story) and that it "has selected" it in Electro Flash · Number Guesser · Wipe Out (Operating Notes) but it never says random it does say random for wipe out "selected at random by DataMan" in Wipe Out (continued) · Force Out · Missing Number (Operating Notes) so it stands out that it is missing here | either number guesser section saying how the number is picked or playing a lot of rounds and looking for patterns or repeats |

---

## 8. Unknowns and Open Questions

What could not be determined from the manual? For each, state what you looked for and where you looked, so a reader knows the gap is real and not just unsearched.

| Open question | Where I looked | Why the manual does not answer it |
|---|---|---|
| can the secret number be exactly 9 or 100 or only numbers in between | Number Guesser (Story) and Electro Flash · Number Guesser · Wipe Out (Operating Notes) and Answer Checker (Operating Notes) | both parts just say "between 9 and 100" and never say if the ends count the only digit limit in the manual "DataMan will only accept problems with one or two digit numbers" is for answer checker it would rule out typing 100 but nothing says it applies to number guesser |
| what key do you press to submit a guess GO or = or nothing | Number Guesser (Story) and Electro Flash · Number Guesser · Wipe Out (Operating Notes) | part I only says "You enter your guess." and part II only says "As you enter each guess" electro flash and wipe out both tell you to "press GO" to start but neither number guesser section names a key for entering a guess |
| what happens if you guess outside 9 to 100 or outside the current hint numbers is it refused flagged or counted | Number Guesser (Story) and Electro Flash · Number Guesser · Wipe Out (Operating Notes) and Answer Checker (Operating Notes) and Force Out (Story) | other games say what they refuse answer checker refuses subtraction with a negative answer and force out says "I won't let you put in a zero!" but both number guesser sections say nothing it is also unknown if a bad guess adds to your guess count |
| is there a limit on guesses or can a round end without finding the number | Number Guesser (Story) and Electro Flash · Number Guesser · Wipe Out (Operating Notes) | both parts only describe a round ending one way "When you finally guess the secret number" and "When the secret number is found" other games state a limit like "If after two tries the answer entered is still wrong" in Answer Checker (Operating Notes) and "You are given two tries to get the right answer to each problem" in Memory Bank (Operating Notes) · DataMan's Timer but neither number guesser section does |
| does the light show change depending on how many guesses you took | Number Guesser (Story) and Electro Flash · Number Guesser · Wipe Out (Operating Notes) and Answer Checker (Operating Notes) and Wipe Out (continued) · Force Out · Missing Number (Operating Notes) | other games say the light show depends on your score like "The higher your score, the more the razzle dazzle" in answer checker and "a light show that varies with the score" in missing number and for number guesser the light show is only called "great" in the story and "spectacular" in the operating notes |
| when players take turns does dataman keep track of whose turn it is or compare scores | Number Guesser (Story) and Electro Flash · Number Guesser · Wipe Out (Operating Notes) | both parts tell players to "take turns" and go for the fewest guesses but the only output described is one guess count per round the manual never says if the players have to keep track of scores themselves |

---

## 9. Cross-Register Note

**What differs:** the name of the key that starts the game part I shows it as a symbol [???] and part II calls it [NUMBER GUESSER] the keypad picture in part I says none of the game keys have words on them so the name in part II does not match anything on the actual device

**Part I says (quote):** "Just press ON and the Number Guesser key: [???]" and "I'll pick a new secret number each time you press [???]" in Number Guesser (Story) and the keypad picture lists "??? (Number Guesser)" and says "The activity keys carry symbols; none is labelled with words." in the Force Out (Story) illustration

**Part II says (quote), or is silent:** "first turn DataMan on with the ON key, and then press the [NUMBER GUESSER] key" in Electro Flash · Number Guesser · Wipe Out (Operating Notes)

**Why this matters to an analyst:** part II is the version written for adults and it names a key the user cannot actually see on the device. an analyst who only read part II would write down "[NUMBER GUESSER] key" as the input which is a name for what the key does and not what is printed on it. a parent following part II would have to figure out on their own that it means the ??? key and the only way to confirm that is part I, the version written for kids. when writing down inputs an analyst needs to know if the manual is describing what the user really sees or a made up name. here the two parts disagree. part I is also the only place that says pressing the key again starts a new round, so someone reading only part II would miss that use of the key completely


