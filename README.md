# F1L_internship_emulator
https://www.linkedin.com/pulse/week-1-f1l-internship-emulator-ksq-dean-lee-354ke/?trackingId=8ytfgFGXTkupIrVN9FlQ7g%3D%3D

Given Key Scientific Question (KSQ): 

The KSQ: Using available scRNA-seq data from cancer cell lines, how would you explore the use of the following FDA-approved antibody therapies in additional cancers?
Trastuzumab: Targets HER2 and is used in the treatment of HER2-positive breast and gastric cancers.
Bevacizumab: Targets VEGF and is used for a variety of cancers, including colorectal, lung, glioblastoma, breast, liver, and kidney cancer.

Approach:

1. We should first understand what is scRNA-seq data, how was it produced, and how to access it. 

      scRNA-seq = single cell RNA sequencing
      Provides gene expression on a single-cell level. 
      Potential pitfalls: First, single-cell experiments are generally more expensive and more difficult to properly conduct. Second, the downstream analysis becomes more complex due to the increased resolution, and it is easier to draw false conclusions. [https://www.sc-best-practices.org/introduction/scrna_seq.html]

  The methods for collecting scRNA-seq data might differ, we should keep this in mind when looking at scRNA-seq across cell lines as this might bias the comparisons that we can make. 

  Other questions we should address: 
  
2. What is an antibody therapy and how does it work at treating cancer? 
3. How do Trastuzumab and Bevacizumab work?
   Trastuzumab works by binding to HER2, a protein involved in cell growth found in large amounts on some cancer cells. This binding blocks the ability of HER2-positive cancer cells to send chemical signals that tell them to grow. It also stimulates the immune system to kill cells that have a lot of HER2. Trastuzumab is a type of targeted therapy drug called a monoclonal antibody.

   Bevacizumab works by blocking a protein called VEGF, which some cancer cells produce in large amounts. Blocking VEGF may prevent the growth of new blood vessels that tumors need to grow. Bevacizumab is a type of targeted therapy called an angiogenesis inhibitor.
   
5. What are HER2 and VEGF?
6. Are there any off-target genes that are interfered with by either Trastuzumab or Bevacizumab?
   We should be able to determine this by looking at relative gene expression in the HER2-positive breast and gastric cancers for Trastuzumab treated cancer cell lines
   
7. 






References (provided by Dean Lee):
1. https://www.sc-best-practices.org/introduction/scrna_seq.html
2. https://www.cancer.gov/about-cancer/treatment/drugs/trastuzumab
3. https://www.cancer.gov/about-cancer/treatment/drugs/bevacizumab
4. https://www.cancer.gov/publications/dictionaries/cancer-terms/def/her2
5. https://www.ncbi.nlm.nih.gov/books/NBK6482/
