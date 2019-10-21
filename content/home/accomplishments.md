+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

title = "Project"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "Graduation project: A classifier for autism prediction based on the conbination of phenotypic information and the features of brain networks"
  company = "Northeastern University"
  company_url = ""
  location = "Shenyang City"
  date_start = "2019-04-01"
  date_end = "2019-06-10"
  description = """
  The result :
  
  * I have developed a classifier that distinguishes between autistic and normal people by combining multiple feature vectors. On the basis of 9 important edges between brain areas, the vector such as 2 spectral domain features, 14 node efficiency and 9 node degree are merged as the input of the support vector machine, and the output is the classification result, achieving a 70% correct rate. 
  
  * Based on the experiment, I summarized the differences between the brain regions of autistic patients and normal people: 
  1. The brain areas which node efficiency and node degree are slightly higher than normal people:57, 63, 77(AAL atlas) 
  2. The brain areas which node efficiency and node degree are slightly lower than normal people:25, 28, 86, 90(AAL atlas)


  Experimental process :
  
  1. Download 871 data from ABIDE website and calculate the correlation coefficient matrix
  
  2. Use a combination of L1-scca + SLR(learn from Japanese paper) and phenotype information for correlation coefficient matrix dimensionality reduction(feature dimension reduction), choose the important edges.
  
  3. Extract the spectral domain features of each correlation coefficient matrix, and select features that have a classification effect
  
  4. Select appropriate node features with classification effect
  
  5. SVM
  
  
  Award:
  
  1. Outstanding Graduation project of School of Biomedical Engineering 
  
  2. Outstanding Graduation project of Northeastern University
  """

[[experience]]
  title = "Team leader"
  company = "Neusoft"
  company_url = "http://www.neusoftmedical.com/"
  location = "Shenyang City"
  date_start = "2016-07-20"
  date_end = "2016-08-13"
  description = """
  Participated in the project License Plate Recognition System Based on Opencv
  
  Responsibilities include:
  
  * Extracted, processed and recognized the vehicle license plate content
  * Designed the user interface
  * Obtained an intern certificate
  """

+++
