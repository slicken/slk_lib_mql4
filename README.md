# slk_lib
Big MQL4 library that contains all kind of stuff


### order ###
- GetError
- SendOrder
- CloseOrder
- ModifyOrder
- CloseType
- CloseTypePerc
- CloseTypeLots
- ModifyTypeStoploss
- CountOrdersExt
- CountOrders
- CountProfit
- CountPoints
- LastTicket
- FirstTicket
- LastCloseTime
- LastOpenTime
- IsOrderDistance
- BreakevenTicket
- TrailTicket
- TrailCandles
- WheelBarrel
- ProfitReport
- CheckSlippage
- CheckExection

### risk ###
- CalcLotsType 0=fixed,1=risk,2=margin
- LotsTypeMM 0=fixed,1=risk,2=margin 
- MarginMM
- RiskMM
- MoneyMM

### time / sessions ###
- IsTradeHour
- IsTradeTime
- IsTradeDayOfWeek
- IsNFP
- IsCurrencySession
- IsCurrencySessionOpen
- IsLondonDst
- IsLondonOpen
- IsNYOpen
- IsDailyClose
- DateTimeOffset
- OffsetHours
- IsMarketOpenDT

### misc ###
- IsTicket
- AddTicket
- DeleteTicket
- BalancedPair
- SpreadAvg
- TicketOpenStr
- TicketCloseStr
- TicketProfitStr
- CreateMagic
- ScreenShot
- StringUpper
- StringLower
- StrToNumber
- OrderTypeToStr
- TimeframeToString
- DayToStr
- MonthToStr
- Random

### visuals ###
- ChartPriceChange (for OnChartEvent) 
- DrawOrderHistory
- DrawTicket
- PlotLabel
- PlotText
- PlotRectangleLabel
- PlotTL
- PlotVL
- PlotHL
- PlotArrow
- PlotButton
- PlotEdit
- PlotCopyright
- ScrollText
- PlotLabelPrice
- SymbolInfo
- RGBToColor
- ColorToRGB

### news ###
- InitNewsArray
- MakeDateTime
- IsNewsURL
- IsNewsTime
- NextNewsTime
- NextNewsCurrTime
- PlotNews
- CheckNews (width alert)  

### indicators ###
- ZoneToString
- ZoneTypeToString
- FindZones
- DrawZones
- ZoneAlerts
- FindBlocks
- InitRenko
- CalcRenko
- FillZigZag
- FillZZ
- ClearState
- IsNewBar
- CalcAvg
- VolumeAvg
- SMAOnArray
- LWMAOnArray
- Session
- SessionAverageVolume
- LevelDistance
- NearestLevel
- DailyPivotDistance
- WeeklyPivotDistance
- VolOsc
- SaveFractal
- SaveFractals
- CheckBreaks
- GetTrend
- NanningTrend

### candles ###
- GetFractalHi
- GetFractalLo
- IsFractalHi
- IsFractalLo
- iBody
- iRange
- iBodyLow
- iBodyHigh
- IsPinBuy
- IsPinSell
- IsEngulfBuy
- IsEngulfSell
- IsBull
- IsBear
