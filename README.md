# backtester_project
backtest with python

you can restore the env with environment.yml in anaconda 


TODOs: 
- [x] 把SMACrossover策略補完(參考backtest1.py的寫法)
- [x] 封裝好 ccxt取data的部分 
- [X] 研究一下sizer的設定方式, 下注方式要改成可以按照比例投注 => 用bt.sizers.PercentSizer
- [ ] run_backtest 要調整餵入參數的方式 適用更多不同的策略方式(不然就是要針對不同策略寫run_backtest)
 