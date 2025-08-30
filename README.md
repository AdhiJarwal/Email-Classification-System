# Email Classification System

A text classification system that categorizes emails into different types (Reset Password, OTP, Transaction, and Internshala promotional emails) using natural language processing techniques. The system processes email content by removing stop words, applies stemming using NLTK's Lancaster Stemmer, and classifies emails by comparing word overlap between the input email and pre-trained datasets for each category. The classification is determined by finding which category has the highest number of common words with the input email.

The project uses four main email categories:
1. Reset Password emails
2. OTP (One-Time Password) emails
3. Transaction/Payment emails
4. Internshala promotional emails
