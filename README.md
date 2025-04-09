

My Junior I.S. is using SVMs and logistic regression to create prediction models for the MBTI using text input and cognitive function classes, first introduced by John Beebe.

The data for this project is too large to upload onto the repository, however, the data originates from https://www.kaggle.com/datasets/zeyadkhalid/mbti-personality-types-500-dataset?resource=download&select=MBTI+500.csv
I modified the data slightly to include the classes. Here's how they're broken down for each type:

type   dominant  auxilary  rat_dominant  irrat_dominant  rationals  irrationals
INTJ   Ni        Te        Te            Ni              TeFi       SeNi
ENTJ   Te        Ni        Te            Ni              TeFi       SeNi
INTP   Ti        Ne        Ti            Ne              FeTi       NeSi
ENTP   Ne        Ti        Ti            Ne              FeTi       NeSi
INFP   Fi        Ne        Fi            Ne              TeFi       NeSi
ENFP   Ne        Fi        Fi            Ne              TeFi       NeSi
INFJ   Ni        Fe        Fe            Ni              FeTi       SeNi
ENFJ   Fe        Ni        Fe            Ni              FeTi       SeNi
ISTJ   Si        Te        Te            Si              TeFi       NeSi
ESTJ   Te        Si        Te            Si              TeFi       NeSi
ISTP   Ti        Se        Ti            Se              FeTi       SeNi
ESTP   Se        Ti        Ti            Se              FeTi       SeNi
ISFP   Fi        Se        Fi            Se              TeFi       SeNi
ESFP   Se        Fi        Fi            Se              TeFi       SeNi
ISFJ   Si        Fe        Fe            Si              FeTi       NeSi
ESFJ   Fe        Si        Fe            Si              FeTi       NeSi


