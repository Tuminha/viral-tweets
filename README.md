# 🐦 Viral Tweets Analysis: My Journey into Machine Learning

> **"Social media has provided a platform for users to communicate, interact, express opinions, and share information throughout various communities. Within the vast amount of user-generated content, there are potential insights that can be found by analyzing this data."**

## 👋 About Me & This Project

Hey there! I'm **Francisco Barbosa**, and this project represents a significant milestone in my machine learning journey. As someone passionate about data science and social media analytics, this Codecademy project has been instrumental in helping me understand how machine learning can uncover patterns in human behavior and communication.

**Connect with me:**
- 🐦 **Twitter/X:** [@cisco_research](https://twitter.com/cisco_research)
- 📧 **Email:** cisco@periospot.com
- 💻 **GitHub:** [Tuminha](https://github.com/Tuminha)

## 🎯 Project Overview

This project explores real Twitter (now X) data to find patterns in social media usage using machine learning. We'll work with four datasets to discover insights that can help with:

- 📊 **Sentiment Analysis**
- 🌐 **Social Network Analysis** 
- 🎯 **Content & Product Recommendations**
- 📈 **Trend Prediction**
- 💬 **Customer Engagement Improvement**

## 📁 Project Structure

```
viral_tweets/
├── 📊 data/                   # Dataset files
│   ├── random_tweets.json      # Random sample of tweets
│   ├── new_york.json          # NYC location-specific tweets
│   ├── london.json            # London location-specific tweets
│   └── paris.json             # Paris location-specific tweets
├── 📓 notebooks/              # Main project notebooks
│   ├── tweet_location.ipynb   # Location classification project
│   └── viral_tweets.ipynb     # Virality prediction project
├── 🔒 solution/               # ⚠️ Only open if really necessary!
│   ├── tweet_location_solution.ipynb
│   └── viral_tweets_solution.ipynb
└── README.md                  # Project documentation
```

## 🚀 Learning Objectives & Tasks

Follow these steps to complete your own viral tweets analysis journey:

### Phase 1: Data Exploration 📊
- [x] **Task 1:** Load and explore the dataset structure
- [x] **Task 2:** Understand tweet features and metadata
- [x] **Task 3:** Analyze user information and location data
- [x] **Task 4:** Examine tweet text patterns and characteristics

### Phase 2: Data Preprocessing 🧹
- [x] **Task 5:** Clean and prepare tweet text data
- [x] **Task 6:** Handle missing values and outliers
- [x] **Task 7:** Extract relevant features for analysis
- [x] **Task 8:** Create target variables for classification

### Phase 3: Feature Engineering ⚙️
- [x] **Task 9:** Extract text-based features (hashtags, mentions, links)
- [x] **Task 10:** Analyze user engagement metrics
- [x] **Task 11:** Create temporal features from timestamps
- [x] **Task 12:** Engineer location-based features

### Phase 4: Machine Learning Models 🤖
- [x] **Task 13:** Implement Naive Bayes for location classification
- [x] **Task 14:** Build K-Nearest Neighbors for virality prediction
- [x] **Task 15:** Evaluate model performance and accuracy
- [x] **Task 16:** Compare different algorithms and approaches

### Phase 5: Analysis & Insights 💡
- [x] **Task 17:** Identify key factors driving tweet virality
- [x] **Task 18:** Analyze location-specific tweet patterns
- [x] **Task 19:** Create visualizations of findings
- [x] **Task 20:** Document insights and recommendations

## 🏆 Project Results & Achievements

### 📊 **Location Classification (Naive Bayes)**
- **Accuracy:** 67.79% - Excellent performance for multi-class text classification
- **Key Insight:** Paris tweets are easiest to identify (70.7% accuracy) due to French language patterns
- **Challenge:** NYC vs London classification is harder (both English-speaking cities)

### 🚀 **Viral Tweet Prediction (K-Nearest Neighbors)**
- **Regular Viral Classification:** 94.1% accuracy (k=6)
- **Extreme Viral Classification:** 73.9% accuracy (k=19)
- **Innovation:** Dual-classification approach for different virality levels

### 🔍 **Key Discoveries**
1. **Optimal Tweet Length:** ~20 words for maximum virality
2. **Social Influence Matters:** Higher follower counts correlate with virality
3. **Counterintuitive Finding:** Links might hurt tweet performance (only 35.7% of extreme viral tweets have links)
4. **Surprising Insight:** Hashtags might hurt performance (only 2.7% of extreme viral tweets have hashtags)
5. **Engagement Patterns:** Average of 627 friends and 729 followers for extreme viral tweets

### 🎯 **Advanced Features Implemented**
- **Beyond Basic Requirements:** Added 3 bonus features (hashtags, links, word count)
- **Hyperparameter Optimization:** Tested k values from 1-200 to find optimal performance
- **Statistical Analysis:** Deep dive into extreme viral tweet characteristics
- **Research-Level Insights:** Counterintuitive findings about social media engagement

## 🛠️ Technical Stack

- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **Scikit-learn** - Machine learning algorithms
- **Jupyter Notebooks** - Interactive development environment
- **Matplotlib/Seaborn** - Data visualization

## 📂 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Tuminha/viral-tweets.git
   cd viral-tweets
   ```

2. **Open the notebooks:**
   - For location classification: `notebooks/tweet_location.ipynb`
   - For virality prediction: `notebooks/viral_tweets.ipynb`

3. **Note:** The notebooks are configured to read data from the `data/` directory using relative paths (`../data/filename.json`). Make sure to run the notebooks from within the `notebooks/` directory.

## 🎓 What You'll Learn

By completing this project, you'll gain hands-on experience with:

1. **Real-world Data Science Pipeline** - From raw data to actionable insights
2. **Text Processing** - Handling unstructured social media data
3. **Classification Algorithms** - Naive Bayes and KNN implementation
4. **Feature Engineering** - Creating meaningful features from social media data
5. **Model Evaluation** - Measuring and improving model performance
6. **Data Visualization** - Communicating findings effectively

## 🚨 Important Notes

- **Solution Files:** The `solution/` folder contains complete implementations. Only reference these if you're truly stuck - the learning happens through struggle! 💪
- **Data Privacy:** All datasets contain anonymized Twitter data for educational purposes
- **Original Source:** This project is based on Codecademy's Off-Platform Project curriculum

## 🤝 Contributing

This is a personal learning project, but I'd love to hear about your experience! Feel free to:

- ⭐ Star this repository if you found it helpful
- 🐛 Report any issues or bugs you encounter
- 💬 Share your own insights and findings
- 🔄 Fork and adapt for your own learning journey

## 📚 Additional Resources

- [Codecademy Data Science Path](https://www.codecademy.com/learn/paths/data-science)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Jupyter Notebook Tutorial](https://jupyter-notebook.readthedocs.io/en/stable/)

## 🎉 My Personal Reflection

This project has been a **game-changer** in my ML journey! Working with real social media data taught me that machine learning isn't just about algorithms - it's about understanding human behavior, cleaning messy data, and finding meaningful patterns that can drive real-world decisions.

### 🌟 **What I'm Most Proud Of:**

1. **Innovation Beyond Requirements:** I didn't just follow instructions - I created a **dual-classification system** for regular vs extreme viral tweets, achieving 94.1% and 73.9% accuracy respectively.

2. **Counterintuitive Discoveries:** My analysis revealed that **links and hashtags might actually hurt tweet performance** - a finding that challenges conventional social media wisdom!

3. **Research-Level Analysis:** I went beyond basic feature engineering to discover that **~20 words is the optimal tweet length** and that social influence (follower count) is a key predictor of virality.

4. **Technical Excellence:** I implemented hyperparameter optimization, tested k values from 1-200, and created comprehensive visualizations that tell a compelling data story.

### 🚀 **Key Learnings:**
- **Feature Engineering is King:** Adding meaningful features (hashtags, links, word count) significantly improved model performance
- **Domain Knowledge Matters:** Understanding social media behavior helped me interpret results meaningfully
- **Statistical Rigor:** Proper validation and analysis revealed insights that simple accuracy scores couldn't show
- **Creative Problem-Solving:** Thinking beyond the basic requirements led to breakthrough discoveries

### 🎯 **Next Steps for Me:**
- Explore more advanced NLP techniques (BERT, GPT models)
- Implement deep learning models for text analysis
- Work with larger, more complex social media datasets
- Build end-to-end ML pipelines for production use
- Publish research papers on social media virality patterns

---

*Happy coding and may your tweets go viral! 🚀*

**Francisco Barbosa** | *Data Science Enthusiast & ML Practitioner*
