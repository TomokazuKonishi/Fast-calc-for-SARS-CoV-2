# Fast-calc-for-SARS-CoV-2

# update (2020-12-01)
A recent version of the axes and the mean data are given, by using data to September.

# RightA: the axes and average data.
# samples.fas, samples.txt: example for the alignment.
# Acknowledgments: those for the GISAID. The original sequences can be downloaded.
# excel files: scores from each continent and figures.
# sPCbaseSelect.xlsx:  The PC for bases. Those made the axes.
# figures.zip: sPC_samples for each continent.


To calculate thousands of sequences will take time.
If your new sequence would be inside the existing framework, 
and if you wish to classify yours within the framework,
you can use an axis determined before.

Here are sample sequences: duplications were removed from the accompanying data sets, 
and many incomplete sequences were also removed. 
By these removals, the routes in Europe became in patches. 
Also, the fourth route from Wuhan (sky-blue) appeared. 
The green dod is the Zhejiang strain, which afterward migrated to Europe
and became a paremtal strain of many variations. 

To use this codes,

0. download the files and unzip.

1. align your sequences to the samples.fas. 
  This should be done manually. 
  Do NOT change any parts of the sample sequence; rather, change yours.
  The extra stretches of N- and C- terminals have to be removed.
  Here I added two samples from Brazil to classify.

2. Make a txt.file that contains yours only.
   (here the example is "brazil.txt")
   
3. Run the code. It makes boolean of yours and applies the axis that has been made for the sample sequence.
   Here the Brazil samples were located at the far end of negative PC1.
   
   


