# Overview of Statistical Analysis Regarding Novel Drug Impact on Rodent Tumor Size
In this analysis, we can see the results of several different drugs and their effects on mouse tumor development. These drugs are Capomulin, Ramicane, Infubinol, and Ceftamin. Data cleaning and visualization are performed via Python and spreadsheets. 


With more data, the connection between drug type, dosage amount, tumor volume and length of treatment may become more apparent. Data in areas including treatment start time in terms of onset of tumor detetion, tumor aggresivity, mouse genetics, and dosage variables depdent on these could help provide more insight into the nature of the drugs MOA and potential efficacy in a range of situations, helping to explain both outliers and potential treatment implementations, as well as implications for a wider audience of clinical trials.


- The only drug with an outlier is Infubionol; this could be due to errors in testing, a unique overall reaction, or a unique reaction dependent on the specific genetic makeup of the mice in question that produced the result. Looking into this result could provide further details into the mechanisms of action for the drug in mice with this genetic makeup, or potentially highlight the specific issue with testing leading to the outlier. 
  
![treatment_group_boxplot](https://github.com/llang777/Rodent-Tumor-Analysis/assets/146140759/84b2ebc8-74ea-4540-a577-6247a9652952)


  -  We can see a siginifcant reduction in tumor volume occur around halfway through the treatment of the mouse on Capomulin; this drop in tumor volume seems to remain mostly consistent through the rest of the treatment, providing potential evidence that this drug does in fact meaningfully reduce the tumor volume for this mouse.
    
![Tumor_Volume_Timepoint_Mouse_l509_Capomulin](https://github.com/llang777/Rodent-Tumor-Analysis/assets/146140759/94998ea5-bd27-4b38-9ef3-05c604b2ac7f)

  -  There is a high level of correlation between tumor volume and mouse weight; as mouse weight increases, so does tumor volume. This could be due to the mice having larger mass overall leading to a larger tumor mass, but could also potentially mean the drugs may be less effective as mouse weight increases if not properly scaled to their weight.

![Weight_vs_Tumor_Volume_Capomulin](https://github.com/llang777/Rodent-Tumor-Analysis/assets/146140759/e0270083-2004-47f3-98e1-8e6980b564e4)

