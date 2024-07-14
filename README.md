# Capstone-Project_2024

Bitext Sample Customer Service Training Dataset for English
============================================================

Overview
--------
This dataset contains sample utterances and their corresponding intents from
the Customer Service domain, ideal for training intent recognition models for
Natural Language Understanding (NLU) platforms.

The dataset focuses on the "Customer Service" domain and includes 27 intents
divided into 11 categories. These intents are selected from Bitext's collection
of 20 domain-specific datasets (such as banking, retail, utilities), emphasizing the intents
that are common across various domains. Below is a complete list of categories and intents.

Utterances
----------
The dataset comprises over 8,000 utterances, with a varying number of examples
per intent. It includes variations in language register, such as politeness, colloquial expressions,
swearing, and indirect styles. Stratified sampling ensures that the dataset represents a general user language register profile.

The dataset also mirrors linguistic phenomena typically seen in real-life chatbots, such as:
  - Spelling mistakes
  - Run-on words
  - Missing punctuation

Contents
--------
Each entry in the dataset includes an example utterance from the Customer Service
domain, alongside its corresponding intent, category, and additional linguistic information.
Each line contains the following four fields:
  - Flags: the applicable linguistic flags
  - Utterance: an example user utterance
  - Category: the high-level intent category
  - Intent: the specific intent corresponding to the user utterance

Linguistic Flags
----------------
The dataset includes annotations for linguistic phenomena, which can be used
to tailor bot training to different user language profiles. These flags are:
  B - Basic syntactic structure
  C - Complex/Coordinated syntactic structure
  E - Expanded abbreviations (e.g., I'm -> I am, I'd -> I would)
  I - Interrogative structure
  K - Keyword only
  L - Lexical variation (synonyms)
  M - Morphological variation (plurals, tenses)
  P - Politeness variation
  Q - Colloquial variation
  W - Offensive language
  Z - Noise (spelling, punctuation)

These features enhance the training dataset's effectiveness, making bots more accurate and robust.

Categories and Intents
----------------------
The dataset's intent categories are:
  ACCOUNT
  CANCELLATION_FEE
  CONTACT
  DELIVERY
  FEEDBACK
  INVOICE
  NEWSLETTER
  ORDER
  PAYMENT
  REFUND
  SHIPPING_ADDRESS

The dataset covers the following intents:
  - Cancel order
  - Change order
  - Change shipping address
  - Check cancellation fee
  - Check invoice
  - Check payment methods
  - Check refund policy
  - Complaint
  - Contact customer service
  - Contact human agent
  - Create account
  - Delete account
  - Delivery options
  - Delivery period
  - Edit account
  - Get invoice
  - Get refund
  - Newsletter subscription
  - Payment issue
  - Place order
  - Recover password
  - Registration problems
  - Review
  - Set up shipping address
  - Switch account
  - Track order
  - Track refund

(c) Bitext Innovations, 2022
