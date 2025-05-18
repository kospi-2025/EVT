# EVT
Supplementary material

- [code]logDD.ipynb : logDD를 만든다. &rarr; 결과물 : [csv]logDD.csv
- [code]LMO.ipynb : [csv]logDD.csvD를 기반으로 각 percentile에서 Lmoments를 계산한다. &rarr; [csv]LMO.csv
- [code]MRL.ipynb : [csv]logDD.csv를 기반으로 각 percentile에서 mean residual life를 계산한다. &rarr; [csv].MRL.csv
- [code]LMO_plot.ipynb : [csv]LMO.csv를 기반으로 Hosking diagram을 만든다. &rarr; 결과물 : [plot]hosking_diagrams_all.pdf
- [code]best_5.ipynb : [csv]LMO.csv를 기반으로 ticker별로 5개의 최적 임계값을 선택한다. &rarr; [csv]best_5.csv
- [code]MRL_plots.ipynb : [csv].MRL.csv을 기반으로 MRL plot을 만든다. [csv]best_5.csv을 활용하여 MRL_plots_best를 만든다. &rarr; [plot]MRL_plots.csv, [plot]MRL_plots_best.csv
- [code]AD_test.ipynb : AD test &rarr; [csv]ad_test_results_lmoment.csv, [csv]ad_test_results_mle.csv &rarr; [table]AD_Test_Results_by_Ticker.pdf 
