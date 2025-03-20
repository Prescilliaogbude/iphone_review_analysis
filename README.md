# iphone_review_analysis

This project analyzes a dataset of iPhone reviews from Amazon to extract insights about customer sentiment, feature satisfaction, and common discussion topics.

   ##[About the Dataset](#about-the-dataset)**

- [Project Goals](#project-goals)
- [Methodology](#methodology)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## About the Dataset

The dataset consists of iPhone reviews scraped from Amazon. It contains various information such as review text, ratings, and potentially other metadata.


## Project Goals
The primary goals of this project are:

- **Sentiment Analysis:** Determine the overall sentiment (positive, negative, neutral) of the reviews and identify trends over time or across different iPhone models.
- **Feature Analysis:** Analyze user satisfaction with specific features of the iPhone (e.g., camera, battery life, performance).
- **Topic Modeling:** Discover underlying themes and discussion points in the reviews using techniques like Latent Dirichlet Allocation (LDA).

## Methodology

The project employs the following methodology:

1. **Data Collection:** (If applicable) Briefly describe how the data was collected or obtained.
2. **Data Preprocessing:** Clean and prepare the text data for analysis. This includes:
    - Removing irrelevant characters and punctuation.
    - Tokenization (splitting text into words).
    - Stop word removal.
    - Stemming or lemmatization.
3. **Sentiment Analysis:** Utilize libraries like TextBlob or VADER to determine the sentiment of each review. Aggregate the results to understand overall sentiment and trends.
4. **Feature Analysis:** Identify mentions of specific features in the reviews and analyze the sentiment associated with those mentions.
5. **Topic Modeling:** Apply LDA or other topic modeling techniques to discover underlying themes and group reviews based on these themes.
6. **Visualization:** Create visualizations to present the findings, such as sentiment distribution charts, feature satisfaction graphs, and word clouds for topics.

## Installation
git clone [https://github.com/prescilliaogbude/iphone-reviews-analysis.git](https://www.google.com/search?q=https://github.com/prescilliaogbude/iphone-reviews-analysis.git)
   cd iphone-reviews-analysis

## Results
1. Sentiment Analysis:

Overall Sentiment: The analysis revealed that the majority of iPhone reviews are positive. However, there's a noticeable trend of increasing negative sentiment over time, particularly following the release of newer iPhone models.

Most Common Negative Keywords: Words like "battery," "price," and "slow" frequently appear in negative reviews.
Example: A word cloud of negative reviews highlights these keywords, indicating potential areas of concern for users. [Link to word cloud: results/negative_wordcloud.png]

2. Feature Analysis:

Top Discussed Features: The most frequently mentioned features in the reviews are:
Camera
Battery Life
Performance
Display
Feature Satisfaction:

3. Topic Modeling:

Identified Topics: Using LDA, the following key topics were identified:
Topic 1: Camera and Photography: Focuses on image quality, camera features, and photography experiences.
Topic 2: Battery and Performance: Discusses battery life, charging, and overall device performance.
Topic 3: Pricing and Value: Relates to the cost of the iPhone and its perceived value for money.
Topic 4: Design and Build Quality: Covers the physical aspects of the iPhone, including its design, durability, and materials.
Topic 5: Software and Updates: Focuses on the iOS operating system, software features, and updates.
