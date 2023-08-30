# WhatsApp_Chat_Analyzer

**Basic Functionality:**

Data Extraction: The code begins by reading a WhatsApp chat log from a text file. It uses regular expressions to extract information from each chat message, including the date, time, username, and message content.

**Data Structuring:** The extracted data is organized into a structured format using a Pandas DataFrame. This makes it easier to work with and analyze.

**Data Analysis:**

Basic Statistics: It provides basic statistics about the chat data, such as counts, means, and standard deviations for numeric columns (Day, Month, Year).
User Message Counts: It counts the number of messages sent by each user and visualizes this information in a bar chart.
Active Day, Month, and Time: It identifies and prints the most active day, month, and time in the chat.
Word Cloud: It generates and displays a word cloud to visualize the most frequently used words in the chat.
Text Translation: The code can translate a mixed-language paragraph in the chat into English using Google Translate. This feature is useful for understanding conversations in different languages.

**Sentiment Analysis:** It performs sentiment analysis on the chat messages using the VADER sentiment analysis tool. This provides sentiment scores for the entire chat.

**Text Summarization:** It can summarize a mixed-language paragraph using Latent Semantic Analysis (LSA) to condense the content into a shorter form.

**Emoji Analysis:** The code counts and analyzes the frequency of emojis used in the chat and can display the top emojis.

**Visualization:**

It visualizes the distribution of messages by user, month, and day of the week using bar charts and pie charts.
It can show the distribution of messages per user, messages per month, and messages by day of the week.

**Use Cases:**

Chat Data Insights: This code is useful for gaining insights from your WhatsApp chat history. You can analyze who sends the most messages, the most active time periods, and the overall sentiment of the conversations.

**Multilingual Analysis:** If your chat includes multiple languages, the code can help translate and summarize text in different languages.

**Emoji Analysis:** If you're curious about emoji usage in your chat, the code can provide statistics on the most commonly used emojis.

**Text Summarization:** The text summarization feature can help condense lengthy text into more manageable summaries.

**Data Visualization:** The code generates visualizations to help you better understand your chat data.

Overall, this script is a versatile tool for exploring and analyzing WhatsApp chat data, and it can be customized and extended to meet specific analysis needs.
