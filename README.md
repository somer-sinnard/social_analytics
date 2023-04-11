For our final project in our Social Analytics course, my group analyzed a collection of tweets posted the day of Queen Elizabeth's death. Our dataset came from Kaggle at: https://www.kaggle.com/datasets/welcomehere/death-of-the-queen

Our group addressed the following questions through our analysis and in the presentation file Project Presentation.ppt:
    1. What words were most frequently used? 
    2. What words are used together in a tweet most often? 
    3. What words are positively correlated? 
    4. In general, what were people’s attitudes towards her passing? 
    5. What part of speech made up the tweets?
    6. What similar words occur?
    7. What are the public's feelings toward the Queen’s death compared to King Charles' coronation?
    8. What trends exist in the user interactions on the day of her death?
    9. Who were the most influential users on the day of her death?

My personal responsibilities for this project included:

1. Cleaning and restructuring the original dataset of tweets to extract the relevant user, mentions, and engagement information required for social network visualizations
    - Data_Clean_Nodes_&_Edges.ipynb
    - Mentions_Nodes.csv
    - Mentions_Edges_1.csv
2. Segmenting the group of users based on the varying levels of engagement conveyed in the data
    - Data_Clean_Nodes_&_Edges.ipynb
3. Obtaining three equally sized and entirely separated samples of corresponding nodes and edges data
    - Sampling_Cleaned_Nodes_&_Edges.ipynb
4. Obtaining network metrics for the three samples and producing various communication visualizations using the NetworkX, Community, and Matplotlib packages
    - Sample_1_Network_Analysis.ipynb
    - Sample_2_Network_Analysis.ipynb
    - Sample_3_Network_Analysis.ipynb
