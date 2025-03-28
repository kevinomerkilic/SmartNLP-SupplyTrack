# QGIS_NLP_Summarizing_Tool

# Automating Customer Relationship Management for Faulty Device Components with Natural Language Processing: A Vendor Solution


**I. Introduction**

The proposed methodology allows a vendor to look back into the supply chain events for component failure. Component failure generates a majority of customer complaints often leading vendors to lose customers if customer support can not assess these issues. With the various Input/Output (IO) devices component list and add-ons, our solution attempts to track and log a timestamp for the date of a phase in the assembly and manufacturing process, country of origin, and manufacturing or assembly plant. Access checkpoints will be created from the vendors' global distribution sites, where their information will also be logged for company records.

When issues arise with a product, the vendor will receive complaints from customers that are frequently logged into a database using a Custom Relationship Management (CRM) system. The solution will data mine those complaints with a Natural Language Processing (NLP) tool. For example, if many complaints are received relating to the speakers on a particular design of a laptop, our model will associate those complaints with the speaker components of that laptop design. That way, the vendor will be able to pinpoint a pool of possible errors that can lead to that specific issue whether it be a driver issue, hardware issue, and etc. The benefit of this particular solution is that it enables the trouble shooting customer complaints to be cohesive resolve with the manufacturing plants.

CRM systems handling customer care and support for cookie-cutter products such as particular IO devices have the potential to damage the profitability of products if their system methodology can not handle big data. Software Mobility teams would have to invest more resources to ensure that complaints are being addressed in a timely fashion. Data is greater than opinions if data supports that there is massive issue with component failure it is paramount to ensure customer satisfaction is expectations are met. The solution will be able to peer through the blinds of the corpus of data that companies receive to ease the logistical burden of tracking backward through the supply chain, and resolving customer issues.

**II. Dataset**

The data was generated using a General Pretrained Model (GPM) to simulate Customer Information Tickets about complaints. The data set is custom made with a sample marker labels of laptops and customer complaints. Feature engineering is required to optimize the Deep Learning Neural Network that will be used in this set up. The dataset might be adjusted with more columns as more feedback appears external factors that arise.

**III. Literature Review**

1. **Summarization Task**

Automatic text summarization is a natural language processing task that entails shortening a passage or sequence of text without neglecting its main focus. Text summarization models fall into two distinct categories: extractive and abstractive [1].

Extractive summarizations are simple in that they extract sentences and phrases from the given text that best represent the overall idea from the text. Models like the Bidirectional Encoder Representation from Transformers (BERT) [2] uses a bidirectional transformer which can detect and assign specific weights and correlations to different words based on the previous and future correlated features. Word pairs generated by BERT are generally considered related and contribute to the overall message of the passage, often resulting in a small one to two sentence span of text.

Abstractive summarizations, like the Text-to-Text Transfer Transformer (T5) [3] and the Bidirectional Auto Regressive Transformer (BART) [4], similarly mark words with specific weights and correlate them with other words in the sequence to create features. However, the main difference of this type of model is that instead of constructing the summary based on the sequence the word pairs were created, the model attempts to reconstruct the sentence, disregarding the original sequence. The output is essentially an entirely new sentence which includes word pairs from the passage. A combination of both approaches can, however, be achieved in the instance of Pei et al [5], producing competitive results comparable to other popular summarization models.

1. **Faulty Product Reporting**

Using artificial intelligence in supply chain management is not an uncommon occurrence. The main goal of using AI and machine learning algorithms is to emulate the thinking and decision making processes of human beings [6]. In this particular field, models would have to be able to detect faulty components either through some kind of sensors and make decisions based on what they see. However, the implementation of such a system into multiple factories can be very expensive and impractical due to the potentially wide range of products that need to be produced. Another approach is to automate the product or component review process after it has been made. Because manufacturers may not be able to catch every faulty component and product, they can use the feedback from the customer reviews to identify issues within the product itself [7].

**IV. Methods**

Methods that are being implemented in this prototype are the following: we are using an Artificial Intelligence (AI)/ Machine Learning (ML)/ Deep Learning (DL) algorithm to summarize a custom data set that was made using a General Pretrained Model, particularly ChatGPT.

1. Experiment/Simulation plans. Evaluation methods.

**V. References**

[1] D. O. Cajueiro et al., 'A comprehensive review of automatic text summarization techniques: method, data, evaluation and coding', _arXiv [cs.CL]_, 2023. https://doi.org/10.48550/arXiv.2301.03403

[2] J. Devlin, M. Chang, K. Lee, and K. Toutanova, "BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding," 2018 arXiv. https://doi.org/10.48550/arXiv.1810.04805.

[3] C. Raffel, N. Shazeer, A. Roberts, K. Lee, S. Narang, M. Matena, Y. Zhou, W. Li, and P. J. Liu, "Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer," 2019, arXiv. https://doi.org/10.48550/arXiv.1910.10683.

[4] M. Lewis, Y. Liu, N. Goyal, M. Ghazvininejad, A. Mohamed, O. Levy, V. Stoyanov, and L. Zettlemoyer, "BART: Denoising Sequence-to-Sequence Pre-training for Natural Language Generation, Translation, and Comprehension," 2019, arXiv. https://doi.org/10.48550/arXiv.1910.13461

[5] J. Pei, R. Hantach, S. Ben Abbès and P. Calvez, "Towards Hybrid Model for Automatic Text Summarization," _2020 19th IEEE International Conference on Machine Learning and Applications (ICMLA)_, Miami, FL, USA, 2020, pp. 987-993, https://doi.org/10.1109/ICMLA51294.2020.00160.

[6] H. Min, "Artificial intelligence in supply chain management: theory and applications," _International Journal of Logistics: Research and Applications_, Vol. 13, No. 1, February 2010, pp. 13–39 https://doi.org/10.1080/13675560902736537

[7] H. Xu, S. Xie, L. Shu and P. S. Yu, "CER: Complementary entity recognition via knowledge expansion on large unlabeled product reviews," 2016 _IEEE International Conference on Big Data (Big Data)_, Washington, DC, USA, 2016, pp. 793-802, https://doi.org/10.1109/BigData.2016.7840672.

----*Issue.txt* Generated with ChatGPT-3.5
----*Issue1.txt* Generated with ChatGPT-3.5
