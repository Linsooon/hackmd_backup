###### tags: `paper notes`
# How to Read a Paper 
* Source 
    * [How to read a paper](https://web.stanford.edu/class/ee384m/Handouts/HowtoReadPaper.pdf)
## Three-pass Approach
### 2.1 The first pass
* quick scan to get a bird’s-eye view of the paper
* takes about five to ten minutes, consisting of the following steps
    1. Carefully read the title, abstract, and introduction.
    2. Read the section and sub-section headings, but ignore everything else.
    3. Glance at the mathematical content (if any) to determine the underlying theoretical foundations.
        * 確認所需要的數學基礎
    4. Read the conclusions
        * 一篇 paper 的價值(作者自己定義的)
    5. Glance over the references, mentally ticking off the ones you’ve already read
#### ==++***five Cs***++==
* at the end of the first pass, should be able to answer the ++***five Cs***++.
    * *Category* :
        * What type of paper is this ?
        * A measurement paper ? 
        * An analysis of an existing system ?
        * A description of a research prototype ?
    * *Content* : 
        * Which other papers is it related to ?
        * Which theoretical bases were used to analyze the problem ?
    * *Correctness* : 
        * Do the assumptions appear to be valid ?(假設是否正確(有效)，包含場域，背景)
    * *Contributions* : 
        * What are the paper’s main contributions ? (paper 的價值在哪)
    * *Clarity* :
        * Is the paper well written ?

#### ==the first pass goal : using five C information==
* determine whether to read this paper further or not ? 
    * based on the personel interest, or simply hust don't enough to understand the paper(mathmetical basis ...etc)
    * the authors make invalid assumptions.
        * 跟生活的認知假設差太多，或者發生機率太低。
* The first pass is adequate for papers that aren’t in your research area, but may someday prove relevant.


#### ==From writer prosepctive== 
* while writing the paper we can assume the reviewers or readers make only one pass over it.
    * :warning: So take care to choose coherent section and sub-section titles and to write concise and comprehensive abstracts.
        * If a reviewer cannot understand the gist after one pass, the paper will likely be rejected.
        * if a reader cannot understand the highlights of the paper after five minutes, the paper will likely never be read.

### 2.2 the second pass 
* should take up to 1 hour.
* read the paper with greater care, but **ingore details such as proofs**.
    * jog down points
    * make comments in the margins(在附近做下筆記、評論)
        * what is consider a useful notes 
            * the term dont know
            * the question want to ask author
1. Look carefully at the figures, diagrams and other illustrations in the paper.Pay special attention to graphs.
    * Are the axes properly labeled
    * Are results shown with error bars(誤差棒), so that conclusions are statistically significant ?
    * ==**可以區分出那些是亂做的論文，那些是乾貨。**==
2. Remember to mark relevant unread references for further reading 
    * (this is a good way to learn more about the background of the paper).
* This level of detail is appropriate for a paper in which you are interested, but does not lie in your research speciality.

#### ==second pass goals==
* able to grasp(掌握) the content of the paper
* able to summarize the main thrust of the paper, with supporting evidence, to someone else

#### ==Still dont understand after pass 2 ?==
* The reasons might be 
    * the subject matter is new to you, with unfamiliar terminology and acronyms.
    * the authors may use a proof or experimental technique that you don’t understand.
    * The paper may be poorly written with unsubstantiated assertions(未被證實的斷言，可能沒有數據支撐，或者足夠事證) and numerous forward references.
    * Or it could just be that it’s late at night and you’re tired.
* 看不懂後的選項
    * 把 paper 放旁邊，祈禱自己不用懂這些也可以在職涯中存活。:smile:
    * 補完背景知識，晚點再回來看
    * 保留並且往 pass 3 走
### 2.3 the thrid pass
* take about four or five hours for beginners
* The key to the third pass is to attempt to ***virtually re-implement***(comparison of the actual with the virtual) the paper.
    * that is, making the same assumptions as the authors, re-create the work.
* By re-implement the paper can 
    * easily identify not only a paper’s innovations.(論文創新的點)
    * its hidden failings and assumptions(隱藏的失敗過程，或是假設)
* This pass requires **great attention** to detail.
    * identify and challenge every assumption in every statement.(要去質疑他的架設跟論述)
    * 以及思考如果是自己要如何去完善這個論述。
* At the end of this pass.
    * able to reconstruct the entire structure of the paper from memory
    * able to identify its strong and weak points
    * able to pinpoint implicit assumptions, missing citations to relevant work and potential issues with experimental or analytical techniques.

### 2.4 timing between passes
* 作者自己的流程
    * collect large numbers of papers and read them (10 minute rapid first review)
    * come back to them sometimes weeks later for a second pass
    * Finally, some further weeks or months later I return to them and find that I can extract the final useful insight that I had not done previously.
    * 【Note】 我自己覺得參考拉，自己也講那是沒 deadline 情況下。

## Doing a literature survey by using three-pass approach
* steps 
    1. use an academic search engine, find 3 to 5 ***recent*** papers in area.
        * google Scholar
        * CiteSeer
        * or related keywords.
    2. Do **one pass** in each one. to get a sense of the work. 
    3. then read their related work sections
        * You will find a thumbnail (縮簡) summary of the recent work, and perhaps, if you are lucky, a pointer to a recent survey paper.
        * If find a survey in a good lucky
            * 可以很快的得到簡略的概念，讀 survey 很爽。
    4. otherwise, find shared citations or repeated author names(代表他是大佬) in the bibliography.
        * key papers and researchers in that area.
    5. then download the keys papers and set them aside.
    6. then go to the websites of key researchers and see what they've pubilshed recently.
        * help you identify the top conferences in that field.(the best researchers usually publish in the top conferences.)
    7. go to the website for these top conferences and look through their recent proceedings
        * A quick scan will usually identify recent high-quality related work.
    * 之前放旁邊的 paper 跟這些 high-quality related works 組成第一版本的 survey
    8. make two passes through these papers.
    * If they all cite a key paper that you did not find earlier, obtain and read it, iterating as necessary.
## Benefits
* adjust the depth of paper evaluation depending on my needs and how much time I have
## Reference of Paper
* [S. Peyton Jones, “Research Skills"](https://simon.peytonjones.org/)
* [T. Roscoe, “Writing Reviews for Systems
Conferences](http://people.inf.ethz.ch/troscoe/pubs/reviewwriting.pdf.)
* [H. Schulzrinne, “Writing Technical Articles,”](https://www.cs.columbia.edu/~hgs/etc/writing-style.html)
* [G.M. Whitesides, “Whitesides’ Group: Writing a
Paper,”](http://www.che.iitm.ac.in/misc/dd/writepaper.pdf.)

* Reference 
    * [台大寫作中心](https://www.awec.ntu.edu.tw/old/writing_study_case.html)
