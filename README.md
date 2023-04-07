# Java
Repository containing examples of Java code I have written. 

## Code Discription 

* **AminoAcidQuiz**: This code is an amino acid quiz. The quiz ends after 30 seconds or when there is a single incorrect answer. The program displays the full name of an amino acid (like “alanine” ) and asks the user to type in the one character code (like a).The quiz ignores case in the answer. The program displays the amino acids in random order, can repeat amino acids and can show more than 20 if the user gets that many correct. The total score is the number of correct answers. 
* **SeqRan**:This code implements a method that returns a random sequence from an arbitrary alphabet. The method does the following: checks to see that alphabet and weights have the same length, checks to see that length >= 0, checks to see that the sum of weights is within round-off error of 1, returns a random string of characters sampled with replacement from alphabet[] with relative frequencies set by weights[]. 
* **FastaSequence**: This code first uses a static factory method to parse a fasta file and return a list of FastaSequence objects. This code then implements a method that inputs a List<FastaSequence> and outputs a columnar spreadsheet represented as a tab-separated .txt file.
* **AminoQuizGUI**: This code produces a GUI-based amino acid quiz. The GUI has the a place for users to type the answer, a place that shows how many right/wrong, and the time left. The GUI has “start quiz” and “cancel” buttons. The time left counts down (in real-time) from 30 seconds...the quiz ends when the time left is 0 seconds. The quiz does not terminate on a wrong answer.. it will keep track of # right and wrong
* **WorkNoGUI/WorkGUI**: The code in "WorkGUI.java" produces a GUI in conjunction with the workers in the "WorkNoGUI.java" file. The GUI does the slow calculation of finding prime numbers up to a number given by the user. The program can use multiple background threads and the user is prompted to choose the number of threads to spawn.The GUI reports on the results of how many primes have been found every few seconds.The GUI has a cancel button that can cancel the operation. At the end of the calculation, or if the user hits cancel, the results are shown (and the amount of time it took to do the calculation).



