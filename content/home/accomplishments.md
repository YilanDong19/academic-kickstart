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
  The result:
  * I have developed a classifier that distinguishes between autistic and normal people by combining multiple feature vectors. On the basis of 9 important edges between brain areas, the vector such as 2 spectral domain features, 14 node efficiency and 9 node degree are merged as the input of the support vector machine, and the output is the classification result, achieving a 70% correct rate. 
  * Based on the experiment, I summarized the differences between the brain regions of autistic patients and normal people: 
    The brain areas which Node efficiency and node degree are slightly higher than normal people:57, 63, 77(AAL atlas)
    The brain areas which Node efficiency and node degree are slightly lower than normal people:25, 28, 86, 90(AAL atlas)

  Responsibilities include:
  
  * Extract the patient's personal information from the server
  * Information transfer, modification and upload between different interfaces
  * Search, long press delete and load the local image and other function
  * Obtained an intern certificate
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
