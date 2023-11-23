# [Page_Rank.pdf](https://github.com/bilan604/GooglePagerank/blob/main/Page_Rank.pdf)  

MAT167: 5/21/2022 - 5/28/2022  

So this project was a group project that I ended up doing by myself due to missing half the class after breaking my hand. The project requirements were to literally explain the Page Rank algorithm, since it was covered already. To figure this out, I spent days learning about it from different fields, going over explanations from computer science backgrounds, linear algebra backgrounds, and statistical backgrounds. This project received an A with extra credit.

After I developed a framework for understanding how and why it works, and what each variable was responsible for, I coded a way to calculate the page ranks on my own - iteratively. I verified that my implementation calculated the same results as those provided by the Power and method and Dense SVD methods. If you are looking for a high level explanation for the page rank algorithm, this paper is for you!

Note: The teleportation (teleporting away) parameter got cut off in the screenshot for Figure 2. It should add (1-tp)/n on the last line. Refer to the Jupyter Notebook if replicating.
