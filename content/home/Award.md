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
  title = "Graduation project: A classifier for autism prediction based on the combination of phenotypic information and the features of brain networks"
  company = "Northeastern University"
  company_url = ""
  location = "Shenyang City"
  date_start = "2019-04-01"
  date_end = "2019-06-10"
  description = """
  The result :
  
  * I have developed a classifier that distinguishes between autistic and normal people by combining multiple feature vectors. On the basis of 9 important edges between brain areas, the vector such as 2 spectral domain features, 14 node efficiency and 9 node degree are merged as the input of the support vector machine, and the output is the classification result, achieving a 70% correct rate. 
  
  * Based on the experiment, I summarized the differences between the brain regions of autistic patients and normal people:   1. The brain areas which node efficiency and node degree are slightly higher than normal people:57, 63, 77(AAL atlas)    2. The brain areas which node efficiency and node degree are slightly lower than normal people:25, 28, 86, 90(AAL atlas)


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
  title = "GCN network"
  company = "Northeastern University"
  company_url = ""
  location = "Shenyang City"
  date_start = "2018-04-01"
  date_end = "2019-03-01"
  description = """
One reason for the low classification accuracy is the great heterogeneity between different collection sites, in order to solve this problem, We set up a study group, read some papers, and found that one solution is to use GCN and phenotype information. So we studied a gcn model and used phenotype information to improve the classification accuracy.
  
  
  The result :
  
The paper ' Disease prediction using graph convolutional networks: Application to Autism Spectrum Disorder and Alzheimer’s disease ' gave us a lot of inspiration. In this paper, it builds a gcn model, and the chebyshev polynomial is used to process each preprocessed matrix. Then it uses phenotypic information to reduce the distance between each individuals. However, the number of features in this paper is 2000, all of them are selected by ridge regression，I think it might be better to use more specific features. So in my graduation project, I used different method to select only 31 important samples' features.
  
  
  """
  
  
  
  
  
  [[experience]]
  title = "Application of Supervised Deep Learning in Medical Data Analysis"
  company = "Northeastern University"
  company_url = ""
  location = "Shenyang City"
  date_start = "2017-06-01"
  date_end = "2017-08-10"
  description = """
It was my first time to know about deep learning. And in order to complete the project better, I set up a study group to participate in this project. But unfortunately, everyone except me(in my group) went to enjoy the summer holiday gradually, so I had to do the whole project by myself. Because I had a internship at the same time, the project I finished didn't contain much.
  
  
  The result:
  
  I built a cnn and autoencoder model and use them to learn the features of images of pulmonary nodules. They didn't work well, this may be caused by my poor knowledge about pulmonary nodule. And the structure and parameters of the model I chose may be another reason.
  
  """

+++

