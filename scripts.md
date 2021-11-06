# Interviews!

## Introduction
ชื่อนพนะครับ
จบตรีจากมหิดลสาขาฟิสิก ระหว่างเรียนได้ทำพวก Data Analysis ของ lab เลยเริ่มชอบเขียนโปรแกม เลยตัดสินใจเรียนต่อโทด้าน Data Science ที่ NYU
หลังจากนั่นผมก็เคยเป็น Data Scientist ให้บริษัทเว็บขายดีที่ขายของมือ 2 ส่วนใหญ่ที่ผมทำที่ Kaidee จะอยู่ตรงเวลา User จะโพสลงขายของ ส่วนใหญใช้ตัว Pytorch เขียนโมเดล




_Why Leave?:_ \
No freedom to express ideas. Rejections. Covid
_What were you doing?:_ \
help tee baan work on website
## Resume Questions:
### Kaidee
_pytoch_, maintained using _cron_ retrain every week. scripts to pull data from _redshift_
Mostly on posting page recommendations.

#### ATPRegressor (cars and motorcycle)
- _brand, model, year_ and optionals _transmission, fuel, color_  -> 3 prices also probability of outlier (fancy car)
- Autoencoder for outlier detection and quantile loss for price predictions

#### TTPRegressor (all other categories)
- CNN _title_ -> _price_ also quantile loss
- character, positional and category embedding
#### TTCClassifier

- CNN _title_ -> _category_  negative log loss
- log softmax to predict top 5 categories.

### Understood Datathon
_past page visits + demographics_ -> _next page_


## Related Knowledge:
- Banks make money primary from interest rates. Some from capital, fees, credits.
### Data Applications:
- Fraud detection
  - autoencoder
- Management of customer Data
  - k-means clustering, em, meanshift
    - elbow method
- Time Series modeling
- Personalized marketing
  - hidden markov model




# MISC
- user based CF
  - ratings based on similar users
- item based CF
  - ratings based on how similar items are rated by that user



# Asks
How many people in team? per project?
python? what modules? database?
types of project, what working on?
