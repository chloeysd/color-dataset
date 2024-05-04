Datasheet: Color Themes

Author: Shuodi Yin
Organization: Creative Computing Institute, University of the Arts London
Date: 01/12/2023
Datasheet Template Source: github.com/JRMeyer/markdown-datasheet-for-datasets

Motivation
The questions in this section are primarily intended to encourage dataset creators to clearly articulate their reasons for creating the dataset and to promote transparency about funding interests.
1. For what purpose was the dataset created?  Was there a specific task in mind?  Was there a specific gap that needed to be filled?  Please provide a description.
The dataset was created for a university NLP course project, aiming to scrape a substantial amount of color-related Wikipedia data for thematic analysis.

2. Who created this dataset (e.g. which team, research group) and on behalf of which entity (e.g. company, institution, organization)?
Shuodi Yin, studying at the Creative Computing Institute (CCI).

3. What support was needed to make this dataset? (e.g. who funded the creation of the dataset? If there is an associated grant, provide the name of the grantor and the grant name and number, or if it was supported by a company or government agency, give those details.)
No.

4. Any other comments?
No.

Composition
Dataset creators should read through the questions in this section prior to any data collection and then provide answers once collection is complete. Most of these questions are intended to provide dataset consumers with the information they need to make informed decisions about using the dataset for specific tasks. The answers to some of these questions reveal information about compliance with the EU’s General Data Protection Regulation (GDPR) or comparable regulations in other jurisdictions.
1. What do the instances that comprise the dataset represent (e.g. documents, photos, people, countries)?Are there multiple types of instances (e.g. movies, users, and ratings; people and interactions between them; nodes and edges)? Please provide a description.
The dataset comprises text files scraped from Wikipedia, focusing on 10 colors across five domains: colour, Art & culture, Science and nature, Psychology and symbolism, and sport.

2. How many instances are there in total (of each type, if appropriate)?
10 folders, containing 253 texts, each averaging 4,568 words, totaling around 1,155,631 words.

3. Does the dataset contain all possible instances or is it a sample (not necessarily random) of instances from a larger set? If the dataset is a sample, then what is the larger set? Is the sample representative of the larger set (e.g. geographic coverage)? If so, please describe how this representativeness was validated/verified. If it is not representative of the larger set, please describe why not (e.g. to cover a more diverse range of instances, because instances were withheld or unavailable).
The dataset includes a set of predefined colors and topics, representing a subjective selection and potentially missing other relevant topics.

4. What data does each instance consist of? "Raw" data (e.g. unprocessed text or images) or features? In either case, please provide a description.
Each text file contains the content of a Wikipedia article on a specific color and domain.

5. Is there a label or target associated with each instance? If so, please provide a description.
No.

6. Is any information missing from individual instances? If so, please provide a description, explaining why this information is missing (e.g. because it was unavailable). This does not include intentionally removed information, but might include, e.g. redacted text.
Each field is only extracted as a representative keyword and some other keywords may be omitted, resulting in the absence of content themes in subsequent use.

7. Are relationships between individual instances made explicit (e.g. users' movie ratings, social network links)? If so, please describe how these relationships are made explicit.
Each color's keywords are linked within the respective Wikipedia color page with hyperlinks.

8. Are there recommended data splits (e.g. training, development/validation, testing)? If so, please provide a description of these splits, explaining the rationale behind them.
No.

9. Are there any errors, sources of noise, or redundancies in the dataset? If so, please provide a description.
There may be errors from flaws in web scraping, but each sample was checked by the creator before publication.

10. Is the dataset self-contained, or does it link to or otherwise rely on external resources (e.g. websites, tweets, other datasets)? If it links to or relies on external resources, a) are there guarantees that they will exist, and remain constant, over time; b) are there official archival versions of the complete dataset (i.e., including the external resources as they existed at the time the dataset was created); c) are there any restrictions (e.g. licenses, fees) associated with any of the external resources that might apply to a future user? Please provide descriptions of all external resources and any restrictions associated with them, as well as links or other access points, as appropriate.
The dataset is self-contained.

11. Does the dataset contain data that might be considered confidential (e.g. data that is protected by legal privilege or by doctor-patient confidentiality, data that includes the content of individuals' non-public communications)? If so, please provide a description.
No.

12. Does the dataset contain data that, if viewed directly, might be offensive, insulting, threatening, or might otherwise cause anxiety? If so, please describe why.
The dataset does not contain confidential information. Some cultural topics may include sensitive subjects like death, war, gender, and religion.

13. Does the dataset relate to people? If not, you may skip the remaining questions in this section.
In some fields, such as art and culture, psychology involves people issues.

14. Does the dataset identify any subpopulations (e.g. by age, gender)? If so, please describe how these subpopulations are identified and provide a description of their respective distributions within the dataset.
Some colors involve discussions on gender. Historical figures are named.

15. Is it possible to identify individuals (i.e., one or more natural persons), either directly or indirectly (i.e., in combination with other data) from the dataset? If so, please describe how.
There are some names of historical figures that can be searched directly.

16. Does the dataset contain data that might be considered sensitive in any way (e.g. data that reveals racial or ethnic origins, sexual orientations, religious beliefs, political opinions or union memberships, or locations; financial or health data; biometric or genetic data; forms of government identification, such as social security numbers; criminal history)? If so, please provide a description.
Some cultural topics might be sensitive, but they are objective descriptions from Wikipedia.

17. Any other comments?
No.

Collection
As with the previous section, dataset creators should read through these questions prior to any data collection to flag potential issues and then provide answers once collection is complete. In addition to the goals of the prior section, the answers to questions here may provide information that allow others to reconstruct the dataset without access to it.

1. How was the data associated with each instance acquired? Was the data directly observable (e.g. raw text, movie ratings), reported by subjects (e.g. survey responses), or indirectly inferred/derived from other data (e.g. part-of-speech tags, model-based guesses for age or language)? If data was reported by subjects or indirectly inferred/derived from other data, was the data validated/verified? If so, please describe how.
Data was publicly scraped from Wikipedia.

2. What mechanisms or procedures were used to collect the data (e.g. hardware apparatus or sensor, manual human curation, software program, software API)? How were these mechanisms or procedures validated?
The data was collected using web scraping code using the libraries scrapy and beatifulsoup4.

3. If the dataset is a sample from a larger set, what was the sampling strategy (e.g. deterministic, probabilistic with specific sampling probabilities)?
Adding more topic keywords could yield a larger dataset.

4. Who was involved in the data collection process (e.g. students, crowdworkers, contractors) and how were they compensated (e.g. how much were crowdworkers paid)?
Shuodi Yin, a CCI student, developed and used the web scraping code.

5. Over what timeframe was the data collected? Does this timeframe match the creation timeframe of the data associated with the instances (e.g. recent crawl of old news articles)? If not, please describe the timeframe in which the data associated with the instances was created. Finally, list when the dataset was first published.
All of the data was collected on the 20/11/2023.

6. Were any ethical review processes conducted (e.g. by an institutional review board)? If so, please provide a description of these review processes, including the outcomes, as well as a link or other access point to any supporting documentation.
No.

7. Does the dataset relate to people? If not, you may skip the remainder of the questions in this section.
Some cultural or historical topics involve well-known historical figures.

8. Did you collect the data from the individuals in question directly, or obtain it via third parties or other sources (e.g. websites)?
Data was publicly scraped from Wikipedia.

9. Were the individuals in question notified about the data collection? If so, please describe (or show with screenshots or other information) how notice was provided, and provide a link or other access point to, or otherwise reproduce, the exact language of the notification itself.
N/A

10. Did the individuals in question consent to the collection and use of their data? If so, please describe (or show with screenshots or other information) how consent was requested and provided, and provide a link or other access point to, or otherwise reproduce, the exact language to which the individuals consented.
N/A

11. If consent was obtained, were the consenting individuals provided with a mechanism to revoke their consent in the future or for certain uses? If so, please provide a description, as well as a link or other access point to the mechanism (if appropriate).
N/A

12. Has an analysis of the potential impact of the dataset and its use on data subjects (e.g. a data protection impact analysis) been conducted? If so, please provide a description of this analysis, including the outcomes, as well as a link or other access point to any supporting documentation.
Then the LDA topic modeling analysis was carried out on the collected data set.

13. Any other comments?
No.

Preprocessing / Cleaning / Labeling
Dataset creators should read through these questions prior to any pre-processing, cleaning, or labeling and then provide answers once these tasks are complete. The questions in this section are intended to provide dataset consumers with the information they need to determine whether the “raw” data has been processed in ways that are compatible with their chosen tasks. For example, text that has been converted into a “bag-of-words” is not suitable for tasks involving word order.
1. Was any preprocessing/cleaning/labeling of the data done (e.g. discretization or bucketing, tokenization, part-of-speech tagging, SIFT feature extraction, removal of instances, processing of missing values)? If so, please provide a description. If not, you may skip the remainder of the questions in this section.
Regex and BeautifulSoup were used for HTML parsing and extracting all paragraphs as raw text, followed by manual review and editing.

2. Was the "raw" data saved in addition to the preprocessed/cleaned/labeled data (e.g. to support unanticipated future uses)? If so, please provide a link or other access point to the "raw" data.
Original data can be accessed through direct Wikipedia article links.

3. Is the software used to preprocess/clean/label the instances available? If so, please provide a link or other access point.
No.

4. Any other comments?
No.

Uses
These questions are intended to encourage dataset creators to reflect on the tasks for which the dataset should and should not be used. By explicitly highlighting these tasks, dataset creators can help dataset consumers to make informed decisions, thereby avoiding potential risks or harms.
1. Has the dataset been used for any tasks already? If so, please provide a description.
The dataset was used for a final course project, with LDA topic modeling to discover potential color-related topics for designers and marketers.

2. Is there a repository that links to any or all papers or systems that use the dataset? If so, please provide a link or other access point.
No.

3. What (other) tasks could the dataset be used for?
Suitable for various color-related analyses.

4. Is there anything about the composition of the dataset or the way it was collected and preprocessed/cleaned/labeled that might impact future uses? For example, is there anything that a future user might need to know to avoid uses that could result in unfair treatment of individuals or groups (e.g. stereotyping, quality of service issues) or other undesirable harms (e.g. financial harms, legal risks) If so, please provide a description. Is there anything a future user could do to mitigate these undesirable harms?
No impact on future uses.

5. Are there tasks for which the dataset should not be used? If so, please provide a description.
No.

6. Any other comments?
No.

Distribution
Dataset creators should provide answers to these questions prior to distributing the dataset either internally within the entity on behalf of which the dataset was created or externally to third parties.
1. Will the dataset be distributed to third parties outside of the entity (e.g. company, institution, organization) on behalf of which the dataset was created? If so, please provide a description.
The dataset exists only within the project.

2. How will the dataset will be distributed (e.g. tarball on website, API, GitHub)? Does the dataset have a digital object identifier (DOI)?
To be uploaded to GitHub after the project concludes.

3. When will the dataset be distributed?
January 2024.

4. Will the dataset be distributed under a copyright or other intellectual property (IP) license, and/or under applicable terms of use (ToU)? If so, please describe this license and/or ToU, and provide a link or other access point to, or otherwise reproduce, any relevant licensing terms or ToU, as well as any fees associated with these restrictions.
No。

5. Have any third parties imposed IP-based or other restrictions on the data associated with the instances? If so, please describe these restrictions, and provide a link or other access point to, or otherwise reproduce, any relevant licensing terms, as well as any fees associated with these restrictions.
No.

6. Do any export controls or other regulatory restrictions apply to the dataset or to individual instances? If so, please describe these restrictions, and provide a link or other access point to, or otherwise reproduce, any supporting documentation.
No.

7. Any other comments?
No.

Maintenance
As with the previous section, dataset creators should provide answers to these questions prior to distributing the dataset. These questions are intended to encourage dataset creators to plan for dataset maintenance and communicate this plan with dataset consumers.
1. Who is supporting/hosting/maintaining the dataset?
Shuodi Yin

2. How can the owner/curator/manager of the dataset be contacted (e.g. email address)?
s[dot] yin0320233 [at] arts [dot] ac [dot] uk

3. Is there an erratum? If so, please provide a link or other access point.
No.

4. Will the dataset be updated (e.g. to correct labeling errors, add new instances, delete instances)? If so, please describe how often, by whom, and how updates will be communicated to users (e.g. mailing list, GitHub)?
No.

5. If the dataset relates to people, are there applicable limits on the retention of the data associated with the instances (e.g. were individuals in question told that their data would be retained for a fixed period of time and then deleted)? If so, please describe these limits and explain how they will be enforced.
Only involves objective descriptions of historical figures.

6. Will older versions of the dataset continue to be supported/hosted/maintained? If so, please describe how. If not, please describe how its obsolescence will be communicated to users.
Available in the Git history on GitHub.

7. If others want to extend/augment/build on/contribute to the dataset, is there a mechanism for them to do so? If so, please provide a description. Will these contributions be validated/verified? If so, please describe how. If not, why not? Is there a process for communicating/distributing these contributions to other users? If so, please provide a description.
Others can fork the GitHub repository to add samples and make pull requests.

8. Any other comments?
No.
