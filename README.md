\begin{table*}[t]
\centering
\caption{Representative samples from the proposed EmotiLens tourism dataset.}
\label{tab:dataset}
\small
\begin{tabular}{llllllllll}
\toprule
ID & Application & Service & Location & Language & Rating & Sentiment & Emotion & Date & Comment \\
\midrule
1 & Booking.com & Hotel & Chiang Mai & English & 5 & Positive & Joy &
2026-01-05 &
Excellent hotel staff and clean room. \\

2 & TripAdvisor & Attraction & Chiang Mai & English & 5 & Positive &
Satisfaction &
2026-01-08 &
Beautiful temple and peaceful atmosphere. \\

3 & Grab & Transport & Chiang Mai & English & 2 & Negative &
Anger &
2026-01-12 &
Airport shuttle was delayed by 30 minutes. \\

4 & Google Maps & Restaurant & Palermo & Italian & 4 & Positive &
Joy &
2026-02-03 &
Amazing local food experience. \\

5 & Bolt & Transport & Palermo & English & 2 & Negative &
Sadness &
2026-02-10 &
Taxi arrived late during rush hour. \\

6 & Airbnb & Hotel & Palermo & English & 5 & Positive &
Satisfaction &
2026-02-18 &
Easy check-in and comfortable apartment. \\

7 & Yelp & Restaurant & Chiang Mai & English & 3 & Neutral &
Neutral &
2026-03-02 &
Restaurant was crowded but food was acceptable. \\

8 & TAGTHAi & Attraction & Chiang Mai & Thai & 5 & Positive &
Joy &
2026-03-12 &
Highly recommend this cultural attraction. \\

9 & WhatsApp & Customer Support & Palermo & Italian & 4 &
Positive &
Satisfaction &
2026-03-18 &
Quick response from customer support. \\

10 & 12Go Asia & Transport & Chiang Mai & English & 4 &
Positive &
Joy &
2026-03-25 &
Convenient online train ticket booking. \\
\bottomrule
\end{tabular}
\end{table*}
The proposed EmotiLens dataset consists of 1,000 multilingual tourism reviews collected from multiple tourism applications, including Booking.com, TripAdvisor, Airbnb, Google Maps, Grab, Bolt, TAGTHAi, WhatsApp, Yelp, and 12Go Asia. Each record contains the application name, tourism service category, destination (Chiang Mai or Palermo), review language, user rating, sentiment label, emotion category, timestamp, user country, and review text. Table~\ref{tab:dataset} presents representative examples from the dataset.

\begin{table}[t]
\centering
\caption{Characteristics of the proposed EmotiLens tourism review dataset.}
\label{tab:dataset_characteristics}
\small
\begin{tabular}{ll}
\toprule
\textbf{Dataset Property} & \textbf{Description} \\
\midrule
Dataset Name & EmotiLens Tourism Review Dataset \\
Total Records & 1,000 multilingual reviews \\
Tourism Destinations & Chiang Mai (Thailand), Palermo (Italy) \\
Data Sources &
Booking.com, TripAdvisor, Airbnb, Google Maps, \\
& Grab, Bolt, TAGTHAi, WhatsApp, Yelp, 12Go Asia \\
Number of Applications & 10 \\
Languages & English, Thai, Italian \\
Service Categories &
Hotel, Restaurant, Transportation, \\
& Tourist Attraction, Shopping, Customer Service \\
Review Information &
Review text, Rating, Timestamp, User Country, \\
& Location, Application Name \\
Sentiment Labels & Positive, Neutral, Negative \\
Emotion Categories &
Joy, Satisfaction, Anger, Sadness, \\
& Surprise, Neutral \\
Average Rating & 1--5 Stars \\
Temporal Coverage & January--June 2026 \\
Prediction Tasks &
Sentence Sentiment, Review Sentiment, Emotion, \\
& Aspect Extraction, Emotion Intensity \\
Framework Usage &
Training, Validation, Testing, Human Feedback Learning \\
\bottomrule
\end{tabular}
\end{table}
Table~\ref{tab:dataset_characteristics} summarizes the characteristics of the proposed EmotiLens tourism review dataset. The dataset contains 1,000 multilingual tourism reviews collected from ten widely used tourism applications across two culturally distinct destinations, namely Chiang Mai, Thailand, and Palermo, Italy. Each review includes contextual information such as the application source, tourism service category, review text, user rating, timestamp, user location, and country. The dataset supports English, Thai, and Italian languages and covers six major tourism service categories, including hotels, restaurants, transportation, tourist attractions, shopping, and customer services. Furthermore, each review is annotated with sentiment labels, emotion categories, and associated metadata to facilitate multilingual sentiment analysis, emotion recognition, explainable AI, and human feedback learning within the proposed EmotiLens framework.
\begin{table}[t]
\centering
\caption{Distribution of reviews across tourism applications.}
\label{tab:data_distribution}
\small
\begin{tabular}{lcc}
\toprule
\textbf{Application} & \textbf{Service Type} & \textbf{Reviews} \\
\midrule
TripAdvisor & Attractions, Hotels & 150 \\
Booking.com & Hotels & 140 \\
Google Maps & Restaurants, Attractions & 130 \\
Grab & Transportation & 110 \\
Bolt & Transportation & 90 \\
TAGTHAi & Tourism Services & 100 \\
Airbnb & Accommodation & 80 \\
Yelp & Restaurants & 70 \\
12Go Asia & Transportation & 70 \\
WhatsApp & Customer Support & 60 \\
\midrule
\textbf{Total} & & \textbf{1,000} \\
\bottomrule
\end{tabular}
\end{table}
Table~\ref{tab:data_distribution} presents the distribution of tourism reviews collected from different mobile applications and online tourism platforms. The dataset includes reviews from hotel reservation platforms (Booking.com and Airbnb), tourism review websites (TripAdvisor and Yelp), navigation services (Google Maps), transportation applications (Grab, Bolt, and 12Go Asia), official tourism applications (TAGTHAi), and customer communication platforms (WhatsApp). The review distribution reflects the diversity of tourism services and user experiences across accommodation, transportation, restaurants, tourist attractions, and customer support. Integrating data from multiple heterogeneous sources enables the proposed EmotiLens framework to learn comprehensive multilingual representations, improve model generalization, and generate reliable recommendations for various tourism stakeholders.
