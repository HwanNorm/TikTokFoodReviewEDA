# What Makes TikTok Food Videos Go Viral? 🔥

Ever wondered why some food review videos on TikTok get millions of views while others don't? We analyzed 130 viral Vietnamese food videos to find out!

## 🍜 What We Discovered

### The Magic Formula for Viral Food Videos:
- **99% show the actual food** (obviously!)
- **98% have the reviewer talking** 
- **96% show the reviewer's face**
- **95% use descriptive food words** like "crispy," "juicy," "delicious"

### Audio Quality Matters:
- **93% of viral videos have good audio quality**
- Clear voice = more views!

## 📱 How We Did This Study

### Step 1: Finding Viral Videos
We spent hours on TikTok looking for food review videos that were truly viral:
- **Minimum requirements:** 50K+ likes, 500K+ views
- **What we actually found:** Most videos had 100K+ likes and 1M+ views
- **Top performer:** 500K+ likes and 15M views! 🤯

### Step 2: Manual Analysis
We watched each video and recorded 25+ different things:
- Does it show food? ✅
- Can you see the reviewer? ✅  
- Do they mention the price? 💰
- What's the audio quality like? 🎵
- And many more...

### Step 3: Survey Time
We asked 45 people (friends, family, classmates) to fill out a survey about what they like in food videos.

**Survey highlights:**
- **Video quality** scored highest (8.5/10)
- **Food filming style** came second (8.4/10)
- People mostly watch food videos in the **evening**

## 🎯 What This Means for Content Creators

### ✅ Do This:
1. **Show your face** - viewers want to see who's talking
2. **Get good audio** - bad sound = instant scroll
3. **Film the food clearly** - make it look delicious
4. **Use descriptive words** - "crunchy," "spicy," "melted cheese"
5. **Post in the evening** - that's when people are hungry and scrolling

### ❌ Avoid This:
- Shaky camera work
- Mumbling or unclear speech
- Not showing the actual food
- Boring descriptions

## 📊 The Numbers That Matter

| What We Looked At | How Often It Appeared |
|------------------|---------------------|
| Food shown in video | 99.2% |
| Reviewer's voice | 98.4% |
| Reviewer's face | 96.1% |
| Descriptive food words | 95.3% |
| Restaurant location shown | 65.9% |
| Food preparation process | 58.9% |

## 📈 Visual Results

Here's what our analysis revealed:

### Most Common Elements in Viral Videos
![Component Frequency Analysis](images/component_frequency_chart.png) 
*This chart shows what appears most often in viral food videos - food presence leads at 99.2%!*

### What Makes Videos Engaging?
![Category Comparison](images/category_comparison_stacked.png)
*Comparison of different video elements across Text, Audio, Visual, and Audio categories*

### Audio Quality Distribution
![Audio Clarity](images/audio_clarity_pie_chart.png)
*93% of viral videos have good audio quality - proof that sound matters!*

### Survey Results - What Viewers Want
![Survey Scores](images/survey_mean_scores.png)
*Video quality and food filming styles scored highest with viewers*

![Survey Distribution](images/survey_boxplots.png)
*Distribution of viewer preferences across different factors*

### Viewing Patterns
![Viewing Frequency](images/viewing_frequency.png)
*Most people encounter food videos "often" while scrolling*

![Viewing Times](images/viewing_timeframes.png)
*Evening is the prime time for food video consumption*

## 🚀 Want to Run This Analysis Yourself?

### Prerequisites
Make sure you have these installed:
```bash
pip install pandas matplotlib seaborn numpy openpyxl
```

### Step 1: Get the Data
1. Download the project files:
   ```bash
   git clone https://github.com/yourusername/tiktok-food-analysis.git
   cd tiktok-food-analysis
   ```

2. You'll need these files:
   - `Annotation.xlsx` - Our video analysis data
   - `survey_data.csv` - Survey responses from 45 participants

### Step 2: Run the Analysis
Open the analysis notebook:
```bash
# If using Google Colab
# Upload the files to your Google Drive and run:
python tiktok_videos_analysis.py

# Or open the Jupyter notebook locally:
jupyter notebook tiktok_analysis.ipynb
```

### Step 3: Generate Your Own Charts
The script will automatically create all the visualizations and save them to the `images/` folder.

### What the Code Does:
1. **Loads the data** from Excel and CSV files
2. **Cleans and processes** the video annotations
3. **Calculates frequencies** for each video component
4. **Creates visualizations** showing the results
5. **Analyzes survey responses** to understand viewer preferences

### File Structure:
```
tiktok-food-analysis/
├── tiktok_videos_analysis.py    # Main analysis script
├── Annotation.xlsx              # Video analysis data (130 videos)
├── survey_data.csv             # Survey responses (45 people)
├── images/                     # Generated charts
│   ├── component_frequency_chart.png
│   ├── category_comparison_stacked.png
│   └── survey_mean_scores.png
└── README.md                   # This file
```

### Need Help?
- Check the comments in the code - they explain each step
- Make sure your data files are in the right format
- All charts will be saved automatically to the `images/` folder

## 🛠️ Tools We Used
- **TikTok** (for finding videos)
- **Google Sheets** (for recording data)
- **Google Colab** (for analysis)
- **Python** (for creating charts)
- **Pandas** (data manipulation)
- **Matplotlib & Seaborn** (visualizations)

## 🎬 Fun Facts
- Most viral food videos are filmed in the **evening**
- **93%** have crystal clear audio
- The most successful videos show **food being made**
- Viewers love seeing the **restaurant atmosphere**

## 💡 Why This Matters
Understanding what makes food content viral can help:
- **Restaurant owners** create better marketing videos
- **Content creators** grow their following
- **Food businesses** reach more customers
- **Anyone** who wants to share their food experiences

---

**Want to create viral food content?** Remember: Good food + Clear audio + Show your face + Describe everything = Viral potential! 🚀

*This study analyzed 130 viral TikTok food review videos from Vietnam (2022-2023) and surveyed 45 viewers about their preferences.*
