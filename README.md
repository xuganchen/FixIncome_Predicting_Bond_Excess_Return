# FixIncome_Predicting_Bond_Excess_Return

This is the code of project--**Predicting Bond Excess Return**.

We use multi-dimensional Factor including technical factors, macroeconomic and financial factors, composite leading factors, market factors, sentiment factors, stock model factors adn classical model factors(like CP factors, etc.) to *build a multi-dimensional selection factor model* to predict bond excess return for 2-5 year. And our model *score a higher* $R^2$ than the classical models.

We process data using four method, including class-within PCA(one factor from each class contributing to reveal economic meanings), backward selection(filter factors by p-value), in-sample and out-sample method and OLS.

Besides, we all do some robust test in different aspects. Firstly, we test for restricted model and unrestricted model, and the later model run better. Secondly, we change the frequency to three months and we get a good empirical results. Thirdly, we change the horizon of prediction. Finally, when ruling out crisis, our model have a better result.

There are five files of jupyter notebook in this project. The data used in this project
are described in the *PrepareData* and *AboutData*, which all can be found in the Internet.