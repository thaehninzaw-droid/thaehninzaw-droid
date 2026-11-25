# Thae Hnin Zaw

My projects explore how software can help people decide what to do next. In Loopline, that means helping a banking team decide which complaint needs attention first. In NeopaperRec, it means showing a reader why a particular paper is worth exploring.

## Selected work

- **[Loopline](https://github.com/thaehninzaw-droid/Customer-Complain-Analysis)** is my undergraduate thesis project on banking complaints. Customers submit a complaint and track its status. The system predicts its category and urgency separately, so staff can see both what the issue concerns and how quickly it may need attention. [Explore the classification models](https://github.com/thaehninzaw-droid/Customer-Complain-Analysis/tree/main/backend/app/ml).
- **[NeopaperRec](https://github.com/thaehninzaw-droid/NeopaperRec)** recommends research papers based on what a reader has liked. Its scoring function weighs citations, shared authors, publication venues, and popularity. It also returns reasons a reader can understand, such as a citation from a paper they already liked. [Read the scoring function](https://github.com/thaehninzaw-droid/NeopaperRec/blob/main/recommendation/scoring.py).
- **[GlowIQ](https://github.com/thaehninzaw-droid/Skincare_Recom)** helps users explore skincare products through a ten-question quiz and a filterable catalogue. Users can review their recommendations, while administrators manage products and publish articles. [See how recommendations work](https://github.com/thaehninzaw-droid/Skincare_Recom/blob/main/src/lib/recommendation-engine.ts).
- **[Employee Task Management](https://github.com/thaehninzaw-droid/Task-Management)** brings task records, attendance, and daily reports into one PHP application. [Browse the daily task report](https://github.com/thaehninzaw-droid/Task-Management/blob/main/etms%20%283%29/etms/daily-task-report.php).

## Technical focus

I use Python for classification and ranking, FastAPI and MongoDB for complaint handling, and TypeScript for product recommendations. A recurring design question in my work is how to make a result useful to the person reading it. A paper recommendation explains its connection to a reader’s interests, while a complaint prediction gives staff a category and an urgency level they can act on.
