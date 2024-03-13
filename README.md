Algorithms for NP-hard Problems (KAIST CS492), Spring 2024
====================


<span style="color:red">NEWS</span>
---------------------
- 7 March: Handwritten slides for lectures Week 1 and 2 are on KLMS. Lecture Note of Kernelization Part I is available now.
- 12 March: Homework 1 is available at KLMS. The deadline is 26th March midnight.
- 13 March: Lecture Note of Kernelization Part II is available.

LOGISTICS
---------------------
- Lecturer: Eunjung KIM, eunjung.kim@kaist.ac.kr
- Lecture Room: 2443 in Building E3
- Lecturer office hour: Wednesday 10:00-11:30 at 3406, E3-1
  
- Teaching Assistant: Sangyoon KIM, ksy980418@kaist.ac.kr, Office at N5 2320

  
- Schedule: 
  - On-site lectures, Tuesday and Thursday 9:00-10:30.
  - 18-22 March: Guest lecturer, [Sebastian Wiederrecht](https://www.wiederrecht.com/)
  - 15-19 April: Midterm exam period. No lecture. Exam is at 9h00-11h45, 16 April.
  - 10-14 June: Final exam period. No lecture. Exam is at 9h00-11h45, 11 June.
     
- Grading: 
  - Homeworks, Participation, Quiz 20%, Project 10%, Midterm exam 35%, Final exam 35%.
  - Project: Students choose a subject related with the course (e.g. a section from the textbooks used in the class, classic or recent papers), and produce a short video explaining the material. You can form a team consisting of up to three members.
  - Participants of the [PACE Challenge 2024](https://pacechallenge.org/2024/) with qualified solutions will get 10% bonus credits on top of their final credits. (Valid: Exact Track and Parameter Tracks)
  
 
- Others:
  - The official language in the class is English. 
  - Homework assignments will be announced on the webpage. The solutions to homeworks should be written either in latex (highly recommended) or in a text editor, e.g. MS Word. The assignment needs to be submitted before the indicated deadline on [KLMS](https://klms.kaist.ac.kr/course/view.php?id=156156). 
Hand-written solutions or submissions after the deadline are not accepted.
  - A strict policy against dishonest behaviors will be applied; expect an "F" grade. 


Course Description
-------------------
Most computational problems are NP-hard, and we cannot expect to solve them (i) optimally (ii) in polynomial-time (iii) on all instances. In this course, we study algorithm design paradigms which relax some of the criteria (i)-(iii) for a desirable algorithm. Specifically, we present techniques for designing and analyzing algorithms in the frameworks of parameterized complexity, approximation and exact exponential algorithms. We examine how such techniques are implemented as algorithms for concrete problems using the structure of a problem instance or a solution. The notions of hardness, which says that there is a limit on how efficiently some problems can be solved under some computational complexity assumption, are introduced as well.

- Recommended Prerequisite: 
Discrete Mathematics (CS204), Data Structure (CS206), Introduction to Algorithms (CS300).

- Course Materials.
  Main Textbooks
  - Parameterized Algorithms, Marek Cygan, Fedor V. Fomin, Lukasz Kowalik, Daniel Lokshtanov, Dániel Marx, Marcin Pilipczuk, Michał Pilipczuk and Saket Saurabh, Springer 2015, https://www.mimuw.edu.pl/~malcin/book/parameterized-algorithms.pdf
  - Approximation Algorithms, Vijay Vazirani, Springer 2001 https://link.springer.com/book/10.1007/978-3-662-04565-7

  References.
  - Graph Theory, Reinhard Diestel, Graph Theory (Graduate Texts in Mathematics, 173) 5th edition, Springer 2016/2017. [Free online](https://diestel-graph-theory.com/)

 
Course Plan (liable to be adjusted)
------------
- 27 Feb: Introduction. Branching-based algorithm, part I. 
  [Lecture Note](https://github.com/ssimplexity/CS492_spring2024/blob/main/%5BWeek01%5Dbranching_algorithm.pdf). Chapter 3.1, 3.3, 3.4 from Cygan et al.
- 29 Feb: Branching-based algorithm, part II
- 5 March: Basics of Kernelization.
  Chapter 2.2-2.5, 9.1 from Cygan et al.
  [Lecture Note, Part I](https://github.com/ssimplexity/CS492_spring2024/blob/main/%5BWeek02%5Dkernelization_part_I.pdf).
- 7 March: More on Kernelization: Vertex Cover, A bit of Feedback Vertex Set.
- 12 March: Quadratic kernel for Feedback Vertex Set. [Lecture Note, Part II](https://github.com/ssimplexity/CS492_spring2024/blob/main/%5BWeek02%5Dkernelization_part_II.pdf) Homework 1 out.
- 14 March: Interative compression. Chapter 4.1, 4.3 from Cygan et al. 
- 19, 21 March: Guest lecture by [Sebastian Wiederrecht](https://www.wiederrecht.com/).
- 26 March: Randomized technique for FPT algorithm. 4.4, 5.1-5.3 from Cygan et al. Homework 2 out.
- 28 March: Tree-decomposition I
- 2 April: Tree-decomposition II
- 4 April: Dynamic programming over subsets. 
- 9 April: Algorithms for CNF-SAT. Homework 3 out.
- 11 April: Hardness in parameterized complexity. 
- Week 8: Mid-term exam.
- Week 9: Hardness in parameterized complexity. Exponential Time Hypothesis. Homework 4 out. Topic Proposal for the project.
- Week 10: Algebraic technique.
- Week 11: Balanced separator and its applications. Homework 5 out.
- Week 12: Introduction to approximation algorithms. 
- Week 13: Primal-dual approach. Homework 6 out.
- Week 14: LP-based rounding. 
- Week 15: SDP-based rounding. Homework 7 out.
- Week 16: Final exam. Submission of the video presentation.


