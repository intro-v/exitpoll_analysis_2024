I work with exit poll data and official data on the presidential election of Russia in 2024. I focus only on cities, where the exit poll was conducted by https://voteabroad.info.

In data_preparation.ipynb I prepare data for further analysis, which is available on Tableau Public:
- RU https://public.tableau.com/app/profile/daria.k/viz/2024_17116428631860/sheet0
- ENG https://public.tableau.com/app/profile/daria.k/viz/AnalysisofexitpolldataabroadfortheRussianpresidentialelection2024/sheet0

Source of data:
- Exit poll "Экзитполы \_Голосуй за рубежом_ 15-17 марта 2024 - Raw data.xlsx": https://voteabroad.info/#results-block
- Official results "results-uik-20240318T1503UTC.tsv": https://t.me/nevybory/131

Because of encoding it's difficult to parse a site with official results, so I took them from those who already have parsed. Just in case:

- official results can be found here http://vybory.izbirkom.ru and you need a vpn;
- an explanation of why it is tricky to parse the site is here https://habr.com/ru/articles/579492/ .