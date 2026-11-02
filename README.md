# RShiny-text-analytics

## Overview
wuzupTA is an interactive **R Shiny dashboard** developed to analyze WhatsApp group conversations using text analytics, natural language processing (NLP), and machine learning techniques. The application transforms raw chat exports into actionable insights, enabling users to understand communication patterns, contributor engagement, discussion trends, sentiment, and frequently used words.

Designed as a self-service analytics tool, the dashboard helps organizations, communities, and teams extract meaningful intelligence from large volumes of WhatsApp conversations through interactive visualizations and reports.

🔗 **Live Application:** (https://knyarkoh.shinyapps.io/whatsapp/)

---

## Business Problem
Organizations and communities generate large amounts of conversation data through messaging platforms such as WhatsApp. Manually reviewing thousands of messages to identify key topics, active contributors, and communication trends is often time-consuming and impractical.

This dashboard addresses that challenge by providing an automated platform for:
- Analyzing group communication patterns
- Identifying popular discussion topics
- Understanding contributor participation levels
- Monitoring engagement and activity trends
- Exploring sentiment and language usage within conversations

---

## Objectives

The project was developed to:
- Extract meaningful insights from WhatsApp group chat exports.
- Identify the most active contributors and discussion participants.
- Analyze frequently used words and conversation themes.
- Evaluate communication patterns and engagement levels.
- Provide an interactive interface for text exploration and reporting.

---

## Dashboard Features

### About
Provides an overview of the project, objectives, methodology, and dashboard capabilities.

### Methodology
Documents the workflow used to process and analyze WhatsApp chat data, including:
- Data extraction
- Text preprocessing
- Data cleaning
- Feature engineering
- Analytical modeling

### Summary Analytics
Presents high-level statistics including:
- Total messages
- Number of contributors
- Conversation activity metrics
- Participation summaries

### Word Cloud Analysis
Visualizes frequently occurring words and phrases to help identify:
- Popular topics
- Trending discussions
- Common language patterns

### Contributor Analysis
Explores participant activity through:
- Message volume by contributor
- Participation rankings
- Contribution distribution

### Message Analytics
Provides detailed analysis of:
- Message frequency
- Activity trends
- Conversation volume over time

### Emoji Analysis
Examines emoji usage patterns to understand:
- Communication styles
- Popular reactions
- Frequency of emoji usage

---

## Dashboard Components

| Component | Description |
|------------|-------------|
| About | Project overview and usage guidance |
| Methodology | Data preparation and analytical approach |
| Summary | Key chat metrics and performance indicators |
| Word Cloud | Visual representation of frequently used words |
| Contributors | Participant activity and engagement analysis |
| Messages | Message volume and communication trends |
| Emojis | Emoji usage and interaction patterns |

---

## Analytics Workflow
The dashboard follows a structured text analytics workflow:
1. Import WhatsApp chat exports
2. Clean and preprocess text data
3. Remove stop words and unwanted symbols
4. Perform exploratory text analysis
5. Generate word frequencies and word clouds
6. Analyze contributor participation
7. Visualize communication patterns
8. Present results through interactive dashboards

---

## Technologies Used

- R
- Shiny
- Tidyverse
- tidytext
- tm
- wordcloud
- ggplot2
- plotly
- DT
- Text Mining
- Natural Language Processing (NLP)
- Machine Learning

---

## Dataset
The application uses exported WhatsApp group chat data containing:
- Message timestamps
- Participants
- Message content
- Emojis
- Activity metadata

### Key Variables
- Date
- Time
- Contributor
- Message
- Word Count
- Emoji Usage
- Message Frequency

---

## Skills Demonstrated
This project showcases expertise in:
- Text Analytics
- Natural Language Processing (NLP)
- Exploratory Data Analysis
- Data Visualization
- Interactive Dashboard Development
- R Programming
- Data Cleaning and Transformation
- Sentiment Analysis
- User Experience Design
- Business Intelligence Reporting

---

## Key Insights Generated
The dashboard helps answer questions such as:
- Who are the most active contributors?
- What topics are discussed most frequently?
- How does participation vary over time?
- Which words dominate conversations?
- What communication trends exist within the group?
- How are emojis used across contributors?

---

## Future Enhancements
Planned improvements include:
- Sentiment analysis by contributor
- Topic modeling using machine learning
- Network analysis of participant interactions
- Automated reporting
- Multi-group comparison
- AI-powered conversation summarization
- Real-time chat analytics

---

## Repository Structure

```text
├── data/
├── scripts/
├── www/
├── app.R
├── ui.R
├── server.R
├── README.md
```

---

## Author

### Ebenezer (Eb) Obeng-Nyarkoh

**Data Analytics | Business Intelligence | Machine Learning | R Shiny Development | Data Visualization**


