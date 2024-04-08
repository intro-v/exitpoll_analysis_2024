I work with exit poll data and official data on the presidential election of Russia in 2024. I focus only on cities, where the exit poll was conducted by https://voteabroad.info.

In _data_preparation.ipynb_ I prepare two files _"exitpolls_grouped_data.xlsx"_ and _"pivot_data.xlsx"_ for further analysis, which is available on Tableau Public:
- RU https://public.tableau.com/app/profile/daria.k/viz/2024_17116428631860/sheet0
- ENG https://public.tableau.com/app/profile/daria.k/viz/AnalysisofexitpolldataabroadfortheRussianpresidentialelection2024/sheet0



Source of data:
- Exit poll _"Экзитполы \_Голосуй за рубежом_ 15-17 марта 2024 - Raw data.xlsx"_: https://voteabroad.info/#results-block
- Official results _"results-uik-20240318T1503UTC.tsv"_: https://t.me/nevybory/131

Because of encoding it's difficult to parse a site with official results, so I took them from those who already have parsed. Just in case:

- official results can be found here http://vybory.izbirkom.ru and you need a vpn;
- an explanation of why it is tricky to parse the site is here https://habr.com/ru/articles/579492/ .
