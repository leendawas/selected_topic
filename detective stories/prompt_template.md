# Prompt Template — CONAN Benchmark (Paper 2)

## Instructions
This is the base prompt used for all 10 questions.
Replace `[QUESTION]` at the bottom with the specific question being tested.

---

## Full Prompt

```
Read the following detective story carefully. It contains background stories from multiple characters' perspectives. Each character only knows part of the truth. Answer the question at the end based ONLY on what is stated or can be reasonably inferred from all the perspectives combined.

=== Jue Ming's Perspective ===
Jue Ming is actually the Saint of Thiefs in disguise. He stole the clothes and identity of Mysterious Ice Sect's Messenger to sneak into Yijian Villa. His real goal is to steal the sword score of Yi Jian Jue. He successfully broke into Qingyezhai, cracked the organ box, and stole the real sword score, replacing it with a fake one. He hid the real sword score behind a loose brick near the inner garden entrance. He also stole two secret letters from the real messenger — one from Xuanbing to Du Zhong demanding the agreed sword score, and one receipt showing 50,000 silver deposited in Banxia Qianzhuang.

=== Ling Xiao's Perspective ===
Ling Xiao is the second disciple of Yijian Villa. He is responsible for the villa's contact with Wulin League. He has been secretly embezzling 50,000 silver from the Wulin League into Banxia Qianzhuang. He uses the secret intelligence network FENG to communicate secretly. During sword practice with Master Du Zhong, Ling Xiao saw an opportunity and stabbed Master in the right abdomen using the fifth style of Yi Jianjue, but the wound was not fatal. Master let him go thinking it was an accident.

=== Lu Ying's Perspective ===
Lu Ying is the first and most senior disciple of Yijian Villa. Master has hinted that the head position will be passed to Lu Ying. Lu Ying is secretly in a romantic relationship with a subordinate disciple, which is forbidden by villa rules. On the night of the incident, Lu Ying was watching the inner garden entrance from Zhiyu Xuan with their secret lover. Lu Ying recorded everyone who entered and exited the inner garden that night. Lu Ying caught a suspicious person at the entrance and was then informed by Xuan Can that Master was dead.

=== Shi Yan's Perspective ===
Shi Yan is disguised as a Wulin League investigator but is actually an avenger sent by Wanhua Valley. Lady Safflower raised Shi Yan and trained them to take revenge on Du Zhong. Lady Safflower originally created Yi Jian Jue and taught it to Du Zhong, who then deceived her and took the sword score. Shi Yan entered the villa, found Du Zhong already wounded in the right abdomen in the Purple Cabinet, and stabbed him in the left chest using the seventh style of Yi Jianjue, killing him. Shi Yan then went to Qingyezhai and took the organ box.

=== Song Jie's Perspective ===
Song Jie has a dual identity — officially a Mysterious Ice Sect messenger, secretly a member of FENG intelligence network. Song Jie was robbed of their clothes and letters by Jue Ming while sleeping. Song Jie then disguised as a Wulin League messenger to enter the villa and expose the imposter. Song Jie found a paper bag hidden under the loose brick near the inner garden — it contained a martial arts map with a Tai Chi pattern in the center. Song Jie was caught by Lu Ying and handed over to Xuan Can.

=== Wang You's Perspective ===
Wang You is one of Du Zhong's sworn brothers from 10 years ago. He preferred a free life and never lived in the villa. Du Zhong sent Wang You a letter and a box. The letter reveals that Du Zhong had a secret son with Lady Safflower over 20 years ago, and that Yi Jian Jue was actually created by Lady Safflower. Du Zhong left a lotus amulet as the key to open the box, which contains a note and a picture for his secret child.

=== Xuan Can's Perspective ===
Xuan Can is the Second Senior Uncle and second-in-command of Yijian Villa. He and Du Zhong became sworn brothers 10 years ago after a battle. Despite appearing close, Xuan Can has long felt distanced from Du Zhong who never fully trusted him. On the night of the incident, Xuan Can returned to the villa and found Du Zhong badly wounded in Qingyezhai, still alive. Du Zhong asked Xuan Can to announce his death so he could hide and recover. However Xuan Can used this moment to stab Du Zhong through the existing wound, killing him for real. He then discovered the organ box was missing from the bookshelf.

=== Zi Su's Perspective ===
Zi Su is the third disciple of Yijian Villa, a swordsmanship genius. Zi Su secretly wants to defect to Xuanbing sect. Zi Su learned that Du Zhong had promised Xuanbing the eighth style of Yi Jianjue but never delivered it. On the night of the incident, Zi Su sneaked into Qingyezhai while Master was busy, cracked the organ box, and stole a drawing of the sword score. Zi Su hid it before being summoned to Mizuki Hall.

---

Question: [QUESTION]
```

---

## The 10 Questions

| # | Question | Type |
|---|---|---|
| Q1 | What is the relationship between Du Zhong and Wang You? | Simple direct relationship |
| Q2 | What is the secret relationship between Ling Xiao and the Wulin League? | Secret/hidden relationship |
| Q3 | How is Du Zhong connected to Lady Safflower through other characters? | Multi-hop reasoning |
| Q4 | Who is "Master" really in the story? | False identity |
| Q5 | Based on all perspectives, what is the true relationship between Du Zhong and Xuan Can? | Contradicting perspectives |
| Q6 | How does Du Zhong see his relationship with Ling Xiao vs how Ling Xiao sees it? | Perspective comparison |
| Q7 | Who was with Ling Xiao on the night of the incident? | Alibi/unknown |
| Q8 | Who attempted to harm someone in the story and who was the target? | Adversarial relationship |
| Q9 | Is there any hidden family relationship revealed in the story? | Hidden family |
| Q10 | List all relationships of Du Zhong with every character mentioned | Full relationship map |
