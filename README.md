# Analyze-US-Security-Financial-Documents

# Introduction
Objective of this assignment is to extract textual data from SEC / EDGAR financial reports and perform text analysis to compute variables those are explained below. 

# Data Source
Link to SEC / EDGAR financial reports are given in excel spreadsheet “cik_list.xlsx”. 
Please add https://www.sec.gov/Archives/ to every cells of column F (cik_list.xlsx) to access link to the financial report. 
Example: Row 2, column F contains edgar/data/3662/0000950170-98-000413.txt
Add https://www.sec.gov/Archives/ to form financial report link i.e. 
https://www.sec.gov/Archives/edgar/data/3662/0000950170-98-000413.txt 

# Variables:
“Text Analysis.docx” you need to compute following: 

Section 1.1: Positive score, negative score, polarity score

Section 2: Average Sentence Length, percentage of complex words, fog index

Section 4: Complex word count

Section 5: Word count

# Output Data structure
Output Data Structure

Output Variables:

All input variables in “cik_list.xlsx”
1. positive_score

2. negative_score

3. polarity_score

4. average_sentence_length

5. percentage_of_complex_words

6. fog_index

7. complex_word_count

8. word_count

9. uncertainty_score

10. constraining_score

11. positive_word_proportion

12. negative_word_proportion

13. uncertainty_word_proportion

14. constraining_word_proportion

15. constraining_words_whole_report

# Libraries
1. NLTK
2. Pandas
3. Regular expression
4. String
5. Request
6. BeautifulSoup

# Text Analysis
1. Sentiment Analysis
2. Analysis of readability
3. Average Number of Words Per Sentence
4. Complex Word Count
5. Average Word Length
