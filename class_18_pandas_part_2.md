```python
import pandas as pd
```


```python
df = pd.read_csv("C:\\Users\\ankush.ramrao.yadav\\Downloads\\ted_data.csv")
```


```python
df 
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>name_speaker</th>
      <th>speaker_occupation</th>
      <th>title</th>
      <th>views</th>
      <th>comments</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Ken Robinson</td>
      <td>Author/educator</td>
      <td>Do schools kill creativity?</td>
      <td>47227110</td>
      <td>4553</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Al Gore</td>
      <td>Climate advocate</td>
      <td>Averting the climate crisis</td>
      <td>3200520</td>
      <td>265</td>
    </tr>
    <tr>
      <th>2</th>
      <td>David Pogue</td>
      <td>Technology columnist</td>
      <td>Simplicity sells</td>
      <td>1636292</td>
      <td>124</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Majora Carter</td>
      <td>Activist for environmental justice</td>
      <td>Greening the ghetto</td>
      <td>1697550</td>
      <td>200</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Hans Rosling</td>
      <td>Global health expert; data visionary</td>
      <td>The best stats you've ever seen</td>
      <td>12005869</td>
      <td>593</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Tony Robbins</td>
      <td>Life coach; expert in leadership psychology</td>
      <td>Why we do what we do</td>
      <td>20685401</td>
      <td>672</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Julia Sweeney</td>
      <td>Actor, comedian, playwright</td>
      <td>Letting go of God</td>
      <td>3769987</td>
      <td>919</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Joshua Prince-Ramus</td>
      <td>Architect</td>
      <td>Behind the design of Seattle's library</td>
      <td>967741</td>
      <td>46</td>
    </tr>
    <tr>
      <th>8</th>
      <td>Dan Dennett</td>
      <td>Philosopher, cognitive scientist</td>
      <td>Let's teach religion -- all religion -- in sch...</td>
      <td>2567958</td>
      <td>582</td>
    </tr>
    <tr>
      <th>9</th>
      <td>Rick Warren</td>
      <td>Pastor, author</td>
      <td>A life of purpose</td>
      <td>3095993</td>
      <td>900</td>
    </tr>
  </tbody>
</table>
</div>




```python
df = pd.read_excel('C:\\Users\\ankush.ramrao.yadav\\Downloads\\football_worldcup.xlsx')
```


```python
df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Year</th>
      <th>Country</th>
      <th>Winner</th>
      <th>Runners-Up</th>
      <th>GoalsScored</th>
      <th>MatchesPlayed</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1990</td>
      <td>Italy</td>
      <td>Germany</td>
      <td>Argentina</td>
      <td>115</td>
      <td>52</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1994</td>
      <td>USA</td>
      <td>Brazil</td>
      <td>Italy</td>
      <td>141</td>
      <td>52</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1998</td>
      <td>France</td>
      <td>France</td>
      <td>Brazil</td>
      <td>171</td>
      <td>64</td>
    </tr>
    <tr>
      <th>3</th>
      <td>2002</td>
      <td>Japan</td>
      <td>Brazil</td>
      <td>Germany</td>
      <td>161</td>
      <td>64</td>
    </tr>
    <tr>
      <th>4</th>
      <td>2006</td>
      <td>Germany</td>
      <td>Italy</td>
      <td>France</td>
      <td>147</td>
      <td>64</td>
    </tr>
    <tr>
      <th>5</th>
      <td>2010</td>
      <td>South Africa</td>
      <td>Spain</td>
      <td>Netherlands</td>
      <td>145</td>
      <td>64</td>
    </tr>
    <tr>
      <th>6</th>
      <td>2014</td>
      <td>Brazil</td>
      <td>Germany</td>
      <td>Argentina</td>
      <td>171</td>
      <td>64</td>
    </tr>
  </tbody>
</table>
</div>




```python
# basic operation on dataframe
```


```python
data = pd.read_csv('C:\\Users\\ankush.ramrao.yadav\\Downloads\\weather_data.csv')
```


```python
data
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>day</th>
      <th>temperature</th>
      <th>windspeed</th>
      <th>event</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1/1/2017</td>
      <td>32</td>
      <td>6</td>
      <td>Rain</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1/2/2017</td>
      <td>35</td>
      <td>7</td>
      <td>Sunny</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1/3/2017</td>
      <td>28</td>
      <td>2</td>
      <td>Snow</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1/4/2017</td>
      <td>24</td>
      <td>7</td>
      <td>Snow</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1/5/2017</td>
      <td>32</td>
      <td>4</td>
      <td>Rain</td>
    </tr>
    <tr>
      <th>5</th>
      <td>1/6/2017</td>
      <td>31</td>
      <td>2</td>
      <td>Sunny</td>
    </tr>
  </tbody>
</table>
</div>




```python
# shape
data.shape
```




    (6, 4)




```python
# head - showing the top n datas
data.head() # show top 5 data

#data.head(20)
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>day</th>
      <th>temperature</th>
      <th>windspeed</th>
      <th>event</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1/1/2017</td>
      <td>32</td>
      <td>6</td>
      <td>Rain</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1/2/2017</td>
      <td>35</td>
      <td>7</td>
      <td>Sunny</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1/3/2017</td>
      <td>28</td>
      <td>2</td>
      <td>Snow</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1/4/2017</td>
      <td>24</td>
      <td>7</td>
      <td>Snow</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1/5/2017</td>
      <td>32</td>
      <td>4</td>
      <td>Rain</td>
    </tr>
  </tbody>
</table>
</div>




```python
# tail - showing the bottom n datas
data.tail() # show bottom 5 data

#data.tail(20)
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>day</th>
      <th>temperature</th>
      <th>windspeed</th>
      <th>event</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>1</th>
      <td>1/2/2017</td>
      <td>35</td>
      <td>7</td>
      <td>Sunny</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1/3/2017</td>
      <td>28</td>
      <td>2</td>
      <td>Snow</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1/4/2017</td>
      <td>24</td>
      <td>7</td>
      <td>Snow</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1/5/2017</td>
      <td>32</td>
      <td>4</td>
      <td>Rain</td>
    </tr>
    <tr>
      <th>5</th>
      <td>1/6/2017</td>
      <td>31</td>
      <td>2</td>
      <td>Sunny</td>
    </tr>
  </tbody>
</table>
</div>




```python
data.columns
```




    Index(['day', 'temperature', 'windspeed', 'event'], dtype='object')




```python
# describe
data.describe()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>temperature</th>
      <th>windspeed</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>count</th>
      <td>6.000000</td>
      <td>6.000000</td>
    </tr>
    <tr>
      <th>mean</th>
      <td>30.333333</td>
      <td>4.666667</td>
    </tr>
    <tr>
      <th>std</th>
      <td>3.829708</td>
      <td>2.338090</td>
    </tr>
    <tr>
      <th>min</th>
      <td>24.000000</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>25%</th>
      <td>28.750000</td>
      <td>2.500000</td>
    </tr>
    <tr>
      <th>50%</th>
      <td>31.500000</td>
      <td>5.000000</td>
    </tr>
    <tr>
      <th>75%</th>
      <td>32.000000</td>
      <td>6.750000</td>
    </tr>
    <tr>
      <th>max</th>
      <td>35.000000</td>
      <td>7.000000</td>
    </tr>
  </tbody>
</table>
</div>




```python
# describe
data.describe(include = 'all')
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>day</th>
      <th>temperature</th>
      <th>windspeed</th>
      <th>event</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>count</th>
      <td>6</td>
      <td>6.000000</td>
      <td>6.000000</td>
      <td>6</td>
    </tr>
    <tr>
      <th>unique</th>
      <td>6</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>3</td>
    </tr>
    <tr>
      <th>top</th>
      <td>1/4/2017</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>Rain</td>
    </tr>
    <tr>
      <th>freq</th>
      <td>1</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>2</td>
    </tr>
    <tr>
      <th>mean</th>
      <td>NaN</td>
      <td>30.333333</td>
      <td>4.666667</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>std</th>
      <td>NaN</td>
      <td>3.829708</td>
      <td>2.338090</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>min</th>
      <td>NaN</td>
      <td>24.000000</td>
      <td>2.000000</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>25%</th>
      <td>NaN</td>
      <td>28.750000</td>
      <td>2.500000</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>50%</th>
      <td>NaN</td>
      <td>31.500000</td>
      <td>5.000000</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>75%</th>
      <td>NaN</td>
      <td>32.000000</td>
      <td>6.750000</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>max</th>
      <td>NaN</td>
      <td>35.000000</td>
      <td>7.000000</td>
      <td>NaN</td>
    </tr>
  </tbody>
</table>
</div>




```python
# info
data.info()
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 6 entries, 0 to 5
    Data columns (total 4 columns):
     #   Column       Non-Null Count  Dtype 
    ---  ------       --------------  ----- 
     0   day          6 non-null      object
     1   temperature  6 non-null      int64 
     2   windspeed    6 non-null      int64 
     3   event        6 non-null      object
    dtypes: int64(2), object(2)
    memory usage: 320.0+ bytes
    


```python
# head
# tail
# describe
# info
# shape
```

# selection and indexing


```python
df = pd.read_csv('C:\\Users\\ankush.ramrao.yadav\\Downloads\\citibike_tripdata.csv')
```


```python
df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>tripduration</th>
      <th>starttime</th>
      <th>stoptime</th>
      <th>start station id</th>
      <th>start station name</th>
      <th>end station id</th>
      <th>end station name</th>
      <th>bikeid</th>
      <th>name_localizedValue</th>
      <th>usertype</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>338</td>
      <td>2018-05-01 00:04:47</td>
      <td>2018-05-01 00:10:25</td>
      <td>3639</td>
      <td>Harborside</td>
      <td>3199</td>
      <td>Newport Pkwy</td>
      <td>33558</td>
      <td>Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1482</td>
      <td>2018-05-01 01:31:10</td>
      <td>2018-05-01 01:55:53</td>
      <td>3681</td>
      <td>Grand St</td>
      <td>3185</td>
      <td>City Hall</td>
      <td>33593</td>
      <td>24 Hour</td>
      <td>Customer</td>
    </tr>
    <tr>
      <th>2</th>
      <td>232</td>
      <td>2018-05-01 01:31:29</td>
      <td>2018-05-01 01:35:22</td>
      <td>3194</td>
      <td>McGinley Square</td>
      <td>3193</td>
      <td>Lincoln Park</td>
      <td>29217</td>
      <td>FREE Bonus Month with Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>3</th>
      <td>190</td>
      <td>2018-05-01 02:03:29</td>
      <td>2018-05-01 02:06:40</td>
      <td>3185</td>
      <td>City Hall</td>
      <td>3186</td>
      <td>Grove St PATH</td>
      <td>29662</td>
      <td>24 Hour</td>
      <td>Customer</td>
    </tr>
    <tr>
      <th>4</th>
      <td>303</td>
      <td>2018-05-01 04:27:12</td>
      <td>2018-05-01 04:32:16</td>
      <td>3207</td>
      <td>Oakland Ave</td>
      <td>3195</td>
      <td>Sip Ave</td>
      <td>15271</td>
      <td>Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>32423</th>
      <td>396</td>
      <td>2018-05-30 13:49:18</td>
      <td>2018-05-30 13:55:55</td>
      <td>3184</td>
      <td>Paulus Hook</td>
      <td>3279</td>
      <td>Dixon Mills</td>
      <td>29639</td>
      <td>Join Citi Bike for $14.95/month</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>32424</th>
      <td>313</td>
      <td>2018-05-30 13:49:21</td>
      <td>2018-05-30 13:54:35</td>
      <td>3202</td>
      <td>Newport PATH</td>
      <td>3639</td>
      <td>Harborside</td>
      <td>26301</td>
      <td>$25 Off Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>32425</th>
      <td>316</td>
      <td>2018-05-30 13:49:51</td>
      <td>2018-05-30 13:55:08</td>
      <td>3220</td>
      <td>5 Corners Library</td>
      <td>3195</td>
      <td>Sip Ave</td>
      <td>29260</td>
      <td>Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>32426</th>
      <td>1130</td>
      <td>2018-05-30 13:50:52</td>
      <td>2018-05-30 14:09:42</td>
      <td>3281</td>
      <td>Leonard Gordon Park</td>
      <td>3213</td>
      <td>Van Vorst Park</td>
      <td>26239</td>
      <td>Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>32427</th>
      <td>369</td>
      <td>2018-05-30 13:50:58</td>
      <td>2018-05-30 13:57:08</td>
      <td>3220</td>
      <td>5 Corners Library</td>
      <td>3207</td>
      <td>Oakland Ave</td>
      <td>33660</td>
      <td>Annual Membership</td>
      <td>Subscriber</td>
    </tr>
  </tbody>
</table>
<p>32428 rows × 10 columns</p>
</div>




```python
df.info()
df.describe()
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 32428 entries, 0 to 32427
    Data columns (total 10 columns):
     #   Column               Non-Null Count  Dtype 
    ---  ------               --------------  ----- 
     0   tripduration         32428 non-null  int64 
     1   starttime            32428 non-null  object
     2   stoptime             32428 non-null  object
     3   start station id     32428 non-null  int64 
     4   start station name   32428 non-null  object
     5   end station id       32428 non-null  int64 
     6   end station name     32428 non-null  object
     7   bikeid               32428 non-null  int64 
     8   name_localizedValue  32428 non-null  object
     9   usertype             32428 non-null  object
    dtypes: int64(4), object(6)
    memory usage: 2.5+ MB
    




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>tripduration</th>
      <th>start station id</th>
      <th>end station id</th>
      <th>bikeid</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>count</th>
      <td>32428.000000</td>
      <td>32428.000000</td>
      <td>32428.000000</td>
      <td>32428.000000</td>
    </tr>
    <tr>
      <th>mean</th>
      <td>798.978352</td>
      <td>3264.568829</td>
      <td>3255.485568</td>
      <td>29817.647959</td>
    </tr>
    <tr>
      <th>std</th>
      <td>9961.203954</td>
      <td>137.810344</td>
      <td>149.390306</td>
      <td>2807.705863</td>
    </tr>
    <tr>
      <th>min</th>
      <td>61.000000</td>
      <td>3183.000000</td>
      <td>212.000000</td>
      <td>15271.000000</td>
    </tr>
    <tr>
      <th>25%</th>
      <td>236.000000</td>
      <td>3192.000000</td>
      <td>3186.000000</td>
      <td>26310.000000</td>
    </tr>
    <tr>
      <th>50%</th>
      <td>352.000000</td>
      <td>3206.000000</td>
      <td>3203.000000</td>
      <td>29516.000000</td>
    </tr>
    <tr>
      <th>75%</th>
      <td>590.000000</td>
      <td>3272.000000</td>
      <td>3270.000000</td>
      <td>33568.000000</td>
    </tr>
    <tr>
      <th>max</th>
      <td>936970.000000</td>
      <td>3681.000000</td>
      <td>3681.000000</td>
      <td>33682.000000</td>
    </tr>
  </tbody>
</table>
</div>




```python
# select 1 column form a dataframe
df['tripduration']
```




    0         338
    1        1482
    2         232
    3         190
    4         303
             ... 
    32423     396
    32424     313
    32425     316
    32426    1130
    32427     369
    Name: tripduration, Length: 32428, dtype: int64




```python
# select 1+ column form a dataframe
df[['tripduration' , 'starttime']]
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>tripduration</th>
      <th>starttime</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>338</td>
      <td>2018-05-01 00:04:47</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1482</td>
      <td>2018-05-01 01:31:10</td>
    </tr>
    <tr>
      <th>2</th>
      <td>232</td>
      <td>2018-05-01 01:31:29</td>
    </tr>
    <tr>
      <th>3</th>
      <td>190</td>
      <td>2018-05-01 02:03:29</td>
    </tr>
    <tr>
      <th>4</th>
      <td>303</td>
      <td>2018-05-01 04:27:12</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>32423</th>
      <td>396</td>
      <td>2018-05-30 13:49:18</td>
    </tr>
    <tr>
      <th>32424</th>
      <td>313</td>
      <td>2018-05-30 13:49:21</td>
    </tr>
    <tr>
      <th>32425</th>
      <td>316</td>
      <td>2018-05-30 13:49:51</td>
    </tr>
    <tr>
      <th>32426</th>
      <td>1130</td>
      <td>2018-05-30 13:50:52</td>
    </tr>
    <tr>
      <th>32427</th>
      <td>369</td>
      <td>2018-05-30 13:50:58</td>
    </tr>
  </tbody>
</table>
<p>32428 rows × 2 columns</p>
</div>




```python
df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>tripduration</th>
      <th>starttime</th>
      <th>stoptime</th>
      <th>start station id</th>
      <th>start station name</th>
      <th>end station id</th>
      <th>end station name</th>
      <th>bikeid</th>
      <th>name_localizedValue</th>
      <th>usertype</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>338</td>
      <td>2018-05-01 00:04:47</td>
      <td>2018-05-01 00:10:25</td>
      <td>3639</td>
      <td>Harborside</td>
      <td>3199</td>
      <td>Newport Pkwy</td>
      <td>33558</td>
      <td>Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1482</td>
      <td>2018-05-01 01:31:10</td>
      <td>2018-05-01 01:55:53</td>
      <td>3681</td>
      <td>Grand St</td>
      <td>3185</td>
      <td>City Hall</td>
      <td>33593</td>
      <td>24 Hour</td>
      <td>Customer</td>
    </tr>
    <tr>
      <th>2</th>
      <td>232</td>
      <td>2018-05-01 01:31:29</td>
      <td>2018-05-01 01:35:22</td>
      <td>3194</td>
      <td>McGinley Square</td>
      <td>3193</td>
      <td>Lincoln Park</td>
      <td>29217</td>
      <td>FREE Bonus Month with Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>3</th>
      <td>190</td>
      <td>2018-05-01 02:03:29</td>
      <td>2018-05-01 02:06:40</td>
      <td>3185</td>
      <td>City Hall</td>
      <td>3186</td>
      <td>Grove St PATH</td>
      <td>29662</td>
      <td>24 Hour</td>
      <td>Customer</td>
    </tr>
    <tr>
      <th>4</th>
      <td>303</td>
      <td>2018-05-01 04:27:12</td>
      <td>2018-05-01 04:32:16</td>
      <td>3207</td>
      <td>Oakland Ave</td>
      <td>3195</td>
      <td>Sip Ave</td>
      <td>15271</td>
      <td>Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>32423</th>
      <td>396</td>
      <td>2018-05-30 13:49:18</td>
      <td>2018-05-30 13:55:55</td>
      <td>3184</td>
      <td>Paulus Hook</td>
      <td>3279</td>
      <td>Dixon Mills</td>
      <td>29639</td>
      <td>Join Citi Bike for $14.95/month</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>32424</th>
      <td>313</td>
      <td>2018-05-30 13:49:21</td>
      <td>2018-05-30 13:54:35</td>
      <td>3202</td>
      <td>Newport PATH</td>
      <td>3639</td>
      <td>Harborside</td>
      <td>26301</td>
      <td>$25 Off Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>32425</th>
      <td>316</td>
      <td>2018-05-30 13:49:51</td>
      <td>2018-05-30 13:55:08</td>
      <td>3220</td>
      <td>5 Corners Library</td>
      <td>3195</td>
      <td>Sip Ave</td>
      <td>29260</td>
      <td>Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>32426</th>
      <td>1130</td>
      <td>2018-05-30 13:50:52</td>
      <td>2018-05-30 14:09:42</td>
      <td>3281</td>
      <td>Leonard Gordon Park</td>
      <td>3213</td>
      <td>Van Vorst Park</td>
      <td>26239</td>
      <td>Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>32427</th>
      <td>369</td>
      <td>2018-05-30 13:50:58</td>
      <td>2018-05-30 13:57:08</td>
      <td>3220</td>
      <td>5 Corners Library</td>
      <td>3207</td>
      <td>Oakland Ave</td>
      <td>33660</td>
      <td>Annual Membership</td>
      <td>Subscriber</td>
    </tr>
  </tbody>
</table>
<p>32428 rows × 10 columns</p>
</div>



# slicing operation

- slicing op always give you the new df

1. Normal slicing
2. loc
3. iloc


```python
# 1. noraml slicing - it does slicing only on the rows

syntax = df[zero_index_start:zero_index_stop:step]
or
syntax = df[custom_index_start:custom_index_stop:step]
```


```python
df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>tripduration</th>
      <th>starttime</th>
      <th>stoptime</th>
      <th>start station id</th>
      <th>start station name</th>
      <th>end station id</th>
      <th>end station name</th>
      <th>bikeid</th>
      <th>name_localizedValue</th>
      <th>usertype</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>338</td>
      <td>2018-05-01 00:04:47</td>
      <td>2018-05-01 00:10:25</td>
      <td>3639</td>
      <td>Harborside</td>
      <td>3199</td>
      <td>Newport Pkwy</td>
      <td>33558</td>
      <td>Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1482</td>
      <td>2018-05-01 01:31:10</td>
      <td>2018-05-01 01:55:53</td>
      <td>3681</td>
      <td>Grand St</td>
      <td>3185</td>
      <td>City Hall</td>
      <td>33593</td>
      <td>24 Hour</td>
      <td>Customer</td>
    </tr>
    <tr>
      <th>2</th>
      <td>232</td>
      <td>2018-05-01 01:31:29</td>
      <td>2018-05-01 01:35:22</td>
      <td>3194</td>
      <td>McGinley Square</td>
      <td>3193</td>
      <td>Lincoln Park</td>
      <td>29217</td>
      <td>FREE Bonus Month with Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>3</th>
      <td>190</td>
      <td>2018-05-01 02:03:29</td>
      <td>2018-05-01 02:06:40</td>
      <td>3185</td>
      <td>City Hall</td>
      <td>3186</td>
      <td>Grove St PATH</td>
      <td>29662</td>
      <td>24 Hour</td>
      <td>Customer</td>
    </tr>
    <tr>
      <th>4</th>
      <td>303</td>
      <td>2018-05-01 04:27:12</td>
      <td>2018-05-01 04:32:16</td>
      <td>3207</td>
      <td>Oakland Ave</td>
      <td>3195</td>
      <td>Sip Ave</td>
      <td>15271</td>
      <td>Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>32423</th>
      <td>396</td>
      <td>2018-05-30 13:49:18</td>
      <td>2018-05-30 13:55:55</td>
      <td>3184</td>
      <td>Paulus Hook</td>
      <td>3279</td>
      <td>Dixon Mills</td>
      <td>29639</td>
      <td>Join Citi Bike for $14.95/month</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>32424</th>
      <td>313</td>
      <td>2018-05-30 13:49:21</td>
      <td>2018-05-30 13:54:35</td>
      <td>3202</td>
      <td>Newport PATH</td>
      <td>3639</td>
      <td>Harborside</td>
      <td>26301</td>
      <td>$25 Off Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>32425</th>
      <td>316</td>
      <td>2018-05-30 13:49:51</td>
      <td>2018-05-30 13:55:08</td>
      <td>3220</td>
      <td>5 Corners Library</td>
      <td>3195</td>
      <td>Sip Ave</td>
      <td>29260</td>
      <td>Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>32426</th>
      <td>1130</td>
      <td>2018-05-30 13:50:52</td>
      <td>2018-05-30 14:09:42</td>
      <td>3281</td>
      <td>Leonard Gordon Park</td>
      <td>3213</td>
      <td>Van Vorst Park</td>
      <td>26239</td>
      <td>Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>32427</th>
      <td>369</td>
      <td>2018-05-30 13:50:58</td>
      <td>2018-05-30 13:57:08</td>
      <td>3220</td>
      <td>5 Corners Library</td>
      <td>3207</td>
      <td>Oakland Ave</td>
      <td>33660</td>
      <td>Annual Membership</td>
      <td>Subscriber</td>
    </tr>
  </tbody>
</table>
<p>32428 rows × 10 columns</p>
</div>




```python
df[1:4]
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>tripduration</th>
      <th>starttime</th>
      <th>stoptime</th>
      <th>start station id</th>
      <th>start station name</th>
      <th>end station id</th>
      <th>end station name</th>
      <th>bikeid</th>
      <th>name_localizedValue</th>
      <th>usertype</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>1</th>
      <td>1482</td>
      <td>2018-05-01 01:31:10</td>
      <td>2018-05-01 01:55:53</td>
      <td>3681</td>
      <td>Grand St</td>
      <td>3185</td>
      <td>City Hall</td>
      <td>33593</td>
      <td>24 Hour</td>
      <td>Customer</td>
    </tr>
    <tr>
      <th>2</th>
      <td>232</td>
      <td>2018-05-01 01:31:29</td>
      <td>2018-05-01 01:35:22</td>
      <td>3194</td>
      <td>McGinley Square</td>
      <td>3193</td>
      <td>Lincoln Park</td>
      <td>29217</td>
      <td>FREE Bonus Month with Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>3</th>
      <td>190</td>
      <td>2018-05-01 02:03:29</td>
      <td>2018-05-01 02:06:40</td>
      <td>3185</td>
      <td>City Hall</td>
      <td>3186</td>
      <td>Grove St PATH</td>
      <td>29662</td>
      <td>24 Hour</td>
      <td>Customer</td>
    </tr>
  </tbody>
</table>
</div>




```python
df[1:10:-1]
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>tripduration</th>
      <th>starttime</th>
      <th>stoptime</th>
      <th>start station id</th>
      <th>start station name</th>
      <th>end station id</th>
      <th>end station name</th>
      <th>bikeid</th>
      <th>name_localizedValue</th>
      <th>usertype</th>
    </tr>
  </thead>
  <tbody>
  </tbody>
</table>
</div>




```python
new_df = df[0:6]

idx = ['row_1' , 'row_2' , 'row_3' , 'row_4' , 'row_5' , 'row_6']
```


```python
new_df.index = idx
```


```python
new_df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>tripduration</th>
      <th>starttime</th>
      <th>stoptime</th>
      <th>start station id</th>
      <th>start station name</th>
      <th>end station id</th>
      <th>end station name</th>
      <th>bikeid</th>
      <th>name_localizedValue</th>
      <th>usertype</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>row_1</th>
      <td>338</td>
      <td>2018-05-01 00:04:47</td>
      <td>2018-05-01 00:10:25</td>
      <td>3639</td>
      <td>Harborside</td>
      <td>3199</td>
      <td>Newport Pkwy</td>
      <td>33558</td>
      <td>Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>row_2</th>
      <td>1482</td>
      <td>2018-05-01 01:31:10</td>
      <td>2018-05-01 01:55:53</td>
      <td>3681</td>
      <td>Grand St</td>
      <td>3185</td>
      <td>City Hall</td>
      <td>33593</td>
      <td>24 Hour</td>
      <td>Customer</td>
    </tr>
    <tr>
      <th>row_3</th>
      <td>232</td>
      <td>2018-05-01 01:31:29</td>
      <td>2018-05-01 01:35:22</td>
      <td>3194</td>
      <td>McGinley Square</td>
      <td>3193</td>
      <td>Lincoln Park</td>
      <td>29217</td>
      <td>FREE Bonus Month with Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>row_4</th>
      <td>190</td>
      <td>2018-05-01 02:03:29</td>
      <td>2018-05-01 02:06:40</td>
      <td>3185</td>
      <td>City Hall</td>
      <td>3186</td>
      <td>Grove St PATH</td>
      <td>29662</td>
      <td>24 Hour</td>
      <td>Customer</td>
    </tr>
    <tr>
      <th>row_5</th>
      <td>303</td>
      <td>2018-05-01 04:27:12</td>
      <td>2018-05-01 04:32:16</td>
      <td>3207</td>
      <td>Oakland Ave</td>
      <td>3195</td>
      <td>Sip Ave</td>
      <td>15271</td>
      <td>Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>row_6</th>
      <td>176</td>
      <td>2018-05-01 04:37:05</td>
      <td>2018-05-01 04:40:01</td>
      <td>3194</td>
      <td>McGinley Square</td>
      <td>3195</td>
      <td>Sip Ave</td>
      <td>29298</td>
      <td>Annual Membership</td>
      <td>Subscriber</td>
    </tr>
  </tbody>
</table>
</div>




```python
# syntax = df[zero_index_start:zero_index_stop:step]
new_df[1:4]  # start(inclusive) stop(exclusive)
# or
# syntax = df[custom_index_start:custom_index_stop:step]
new_df['row_2':'row_4'] #start(inclusive) stop(inclusive)
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>tripduration</th>
      <th>starttime</th>
      <th>stoptime</th>
      <th>start station id</th>
      <th>start station name</th>
      <th>end station id</th>
      <th>end station name</th>
      <th>bikeid</th>
      <th>name_localizedValue</th>
      <th>usertype</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>row_2</th>
      <td>1482</td>
      <td>2018-05-01 01:31:10</td>
      <td>2018-05-01 01:55:53</td>
      <td>3681</td>
      <td>Grand St</td>
      <td>3185</td>
      <td>City Hall</td>
      <td>33593</td>
      <td>24 Hour</td>
      <td>Customer</td>
    </tr>
    <tr>
      <th>row_3</th>
      <td>232</td>
      <td>2018-05-01 01:31:29</td>
      <td>2018-05-01 01:35:22</td>
      <td>3194</td>
      <td>McGinley Square</td>
      <td>3193</td>
      <td>Lincoln Park</td>
      <td>29217</td>
      <td>FREE Bonus Month with Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>row_4</th>
      <td>190</td>
      <td>2018-05-01 02:03:29</td>
      <td>2018-05-01 02:06:40</td>
      <td>3185</td>
      <td>City Hall</td>
      <td>3186</td>
      <td>Grove St PATH</td>
      <td>29662</td>
      <td>24 Hour</td>
      <td>Customer</td>
    </tr>
  </tbody>
</table>
</div>




```python
new_df_1 = df[0:6]

idx = [6,3,5,7,2,1]

new_df_1.index = idx
```


```python
new_df_1
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>tripduration</th>
      <th>starttime</th>
      <th>stoptime</th>
      <th>start station id</th>
      <th>start station name</th>
      <th>end station id</th>
      <th>end station name</th>
      <th>bikeid</th>
      <th>name_localizedValue</th>
      <th>usertype</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>6</th>
      <td>338</td>
      <td>2018-05-01 00:04:47</td>
      <td>2018-05-01 00:10:25</td>
      <td>3639</td>
      <td>Harborside</td>
      <td>3199</td>
      <td>Newport Pkwy</td>
      <td>33558</td>
      <td>Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1482</td>
      <td>2018-05-01 01:31:10</td>
      <td>2018-05-01 01:55:53</td>
      <td>3681</td>
      <td>Grand St</td>
      <td>3185</td>
      <td>City Hall</td>
      <td>33593</td>
      <td>24 Hour</td>
      <td>Customer</td>
    </tr>
    <tr>
      <th>5</th>
      <td>232</td>
      <td>2018-05-01 01:31:29</td>
      <td>2018-05-01 01:35:22</td>
      <td>3194</td>
      <td>McGinley Square</td>
      <td>3193</td>
      <td>Lincoln Park</td>
      <td>29217</td>
      <td>FREE Bonus Month with Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>7</th>
      <td>190</td>
      <td>2018-05-01 02:03:29</td>
      <td>2018-05-01 02:06:40</td>
      <td>3185</td>
      <td>City Hall</td>
      <td>3186</td>
      <td>Grove St PATH</td>
      <td>29662</td>
      <td>24 Hour</td>
      <td>Customer</td>
    </tr>
    <tr>
      <th>2</th>
      <td>303</td>
      <td>2018-05-01 04:27:12</td>
      <td>2018-05-01 04:32:16</td>
      <td>3207</td>
      <td>Oakland Ave</td>
      <td>3195</td>
      <td>Sip Ave</td>
      <td>15271</td>
      <td>Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>1</th>
      <td>176</td>
      <td>2018-05-01 04:37:05</td>
      <td>2018-05-01 04:40:01</td>
      <td>3194</td>
      <td>McGinley Square</td>
      <td>3195</td>
      <td>Sip Ave</td>
      <td>29298</td>
      <td>Annual Membership</td>
      <td>Subscriber</td>
    </tr>
  </tbody>
</table>
</div>




```python
new_df_1[0:4]
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>tripduration</th>
      <th>starttime</th>
      <th>stoptime</th>
      <th>start station id</th>
      <th>start station name</th>
      <th>end station id</th>
      <th>end station name</th>
      <th>bikeid</th>
      <th>name_localizedValue</th>
      <th>usertype</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>6</th>
      <td>338</td>
      <td>2018-05-01 00:04:47</td>
      <td>2018-05-01 00:10:25</td>
      <td>3639</td>
      <td>Harborside</td>
      <td>3199</td>
      <td>Newport Pkwy</td>
      <td>33558</td>
      <td>Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1482</td>
      <td>2018-05-01 01:31:10</td>
      <td>2018-05-01 01:55:53</td>
      <td>3681</td>
      <td>Grand St</td>
      <td>3185</td>
      <td>City Hall</td>
      <td>33593</td>
      <td>24 Hour</td>
      <td>Customer</td>
    </tr>
    <tr>
      <th>5</th>
      <td>232</td>
      <td>2018-05-01 01:31:29</td>
      <td>2018-05-01 01:35:22</td>
      <td>3194</td>
      <td>McGinley Square</td>
      <td>3193</td>
      <td>Lincoln Park</td>
      <td>29217</td>
      <td>FREE Bonus Month with Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>7</th>
      <td>190</td>
      <td>2018-05-01 02:03:29</td>
      <td>2018-05-01 02:06:40</td>
      <td>3185</td>
      <td>City Hall</td>
      <td>3186</td>
      <td>Grove St PATH</td>
      <td>29662</td>
      <td>24 Hour</td>
      <td>Customer</td>
    </tr>
  </tbody>
</table>
</div>




```python
new_df_1[6:7]
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>tripduration</th>
      <th>starttime</th>
      <th>stoptime</th>
      <th>start station id</th>
      <th>start station name</th>
      <th>end station id</th>
      <th>end station name</th>
      <th>bikeid</th>
      <th>name_localizedValue</th>
      <th>usertype</th>
    </tr>
  </thead>
  <tbody>
  </tbody>
</table>
</div>



2. loc method

- does the slicing based on the rows as wel as column also

syntax = df[custom_index_start:custom_index_stop:step , column_name_start:column_name_stop:step]


```python
new_df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>tripduration</th>
      <th>starttime</th>
      <th>stoptime</th>
      <th>start station id</th>
      <th>start station name</th>
      <th>end station id</th>
      <th>end station name</th>
      <th>bikeid</th>
      <th>name_localizedValue</th>
      <th>usertype</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>row_1</th>
      <td>338</td>
      <td>2018-05-01 00:04:47</td>
      <td>2018-05-01 00:10:25</td>
      <td>3639</td>
      <td>Harborside</td>
      <td>3199</td>
      <td>Newport Pkwy</td>
      <td>33558</td>
      <td>Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>row_2</th>
      <td>1482</td>
      <td>2018-05-01 01:31:10</td>
      <td>2018-05-01 01:55:53</td>
      <td>3681</td>
      <td>Grand St</td>
      <td>3185</td>
      <td>City Hall</td>
      <td>33593</td>
      <td>24 Hour</td>
      <td>Customer</td>
    </tr>
    <tr>
      <th>row_3</th>
      <td>232</td>
      <td>2018-05-01 01:31:29</td>
      <td>2018-05-01 01:35:22</td>
      <td>3194</td>
      <td>McGinley Square</td>
      <td>3193</td>
      <td>Lincoln Park</td>
      <td>29217</td>
      <td>FREE Bonus Month with Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>row_4</th>
      <td>190</td>
      <td>2018-05-01 02:03:29</td>
      <td>2018-05-01 02:06:40</td>
      <td>3185</td>
      <td>City Hall</td>
      <td>3186</td>
      <td>Grove St PATH</td>
      <td>29662</td>
      <td>24 Hour</td>
      <td>Customer</td>
    </tr>
    <tr>
      <th>row_5</th>
      <td>303</td>
      <td>2018-05-01 04:27:12</td>
      <td>2018-05-01 04:32:16</td>
      <td>3207</td>
      <td>Oakland Ave</td>
      <td>3195</td>
      <td>Sip Ave</td>
      <td>15271</td>
      <td>Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>row_6</th>
      <td>176</td>
      <td>2018-05-01 04:37:05</td>
      <td>2018-05-01 04:40:01</td>
      <td>3194</td>
      <td>McGinley Square</td>
      <td>3195</td>
      <td>Sip Ave</td>
      <td>29298</td>
      <td>Annual Membership</td>
      <td>Subscriber</td>
    </tr>
  </tbody>
</table>
</div>




```python
# extarct 1,3,5 of trip ,start and stop time
new_df.loc['row_1':'row_5':2 , 'tripduration':'stoptime']
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>tripduration</th>
      <th>starttime</th>
      <th>stoptime</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>row_1</th>
      <td>338</td>
      <td>2018-05-01 00:04:47</td>
      <td>2018-05-01 00:10:25</td>
    </tr>
    <tr>
      <th>row_3</th>
      <td>232</td>
      <td>2018-05-01 01:31:29</td>
      <td>2018-05-01 01:35:22</td>
    </tr>
    <tr>
      <th>row_5</th>
      <td>303</td>
      <td>2018-05-01 04:27:12</td>
      <td>2018-05-01 04:32:16</td>
    </tr>
  </tbody>
</table>
</div>




```python
new_df.loc['row_1':'row_5':3 , ::-1]
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>usertype</th>
      <th>name_localizedValue</th>
      <th>bikeid</th>
      <th>end station name</th>
      <th>end station id</th>
      <th>start station name</th>
      <th>start station id</th>
      <th>stoptime</th>
      <th>starttime</th>
      <th>tripduration</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>row_1</th>
      <td>Subscriber</td>
      <td>Annual Membership</td>
      <td>33558</td>
      <td>Newport Pkwy</td>
      <td>3199</td>
      <td>Harborside</td>
      <td>3639</td>
      <td>2018-05-01 00:10:25</td>
      <td>2018-05-01 00:04:47</td>
      <td>338</td>
    </tr>
    <tr>
      <th>row_4</th>
      <td>Customer</td>
      <td>24 Hour</td>
      <td>29662</td>
      <td>Grove St PATH</td>
      <td>3186</td>
      <td>City Hall</td>
      <td>3185</td>
      <td>2018-05-01 02:06:40</td>
      <td>2018-05-01 02:03:29</td>
      <td>190</td>
    </tr>
  </tbody>
</table>
</div>




```python
new_df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>tripduration</th>
      <th>starttime</th>
      <th>stoptime</th>
      <th>start station id</th>
      <th>start station name</th>
      <th>end station id</th>
      <th>end station name</th>
      <th>bikeid</th>
      <th>name_localizedValue</th>
      <th>usertype</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>row_1</th>
      <td>338</td>
      <td>2018-05-01 00:04:47</td>
      <td>2018-05-01 00:10:25</td>
      <td>3639</td>
      <td>Harborside</td>
      <td>3199</td>
      <td>Newport Pkwy</td>
      <td>33558</td>
      <td>Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>row_2</th>
      <td>1482</td>
      <td>2018-05-01 01:31:10</td>
      <td>2018-05-01 01:55:53</td>
      <td>3681</td>
      <td>Grand St</td>
      <td>3185</td>
      <td>City Hall</td>
      <td>33593</td>
      <td>24 Hour</td>
      <td>Customer</td>
    </tr>
    <tr>
      <th>row_3</th>
      <td>232</td>
      <td>2018-05-01 01:31:29</td>
      <td>2018-05-01 01:35:22</td>
      <td>3194</td>
      <td>McGinley Square</td>
      <td>3193</td>
      <td>Lincoln Park</td>
      <td>29217</td>
      <td>FREE Bonus Month with Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>row_4</th>
      <td>190</td>
      <td>2018-05-01 02:03:29</td>
      <td>2018-05-01 02:06:40</td>
      <td>3185</td>
      <td>City Hall</td>
      <td>3186</td>
      <td>Grove St PATH</td>
      <td>29662</td>
      <td>24 Hour</td>
      <td>Customer</td>
    </tr>
    <tr>
      <th>row_5</th>
      <td>303</td>
      <td>2018-05-01 04:27:12</td>
      <td>2018-05-01 04:32:16</td>
      <td>3207</td>
      <td>Oakland Ave</td>
      <td>3195</td>
      <td>Sip Ave</td>
      <td>15271</td>
      <td>Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>row_6</th>
      <td>176</td>
      <td>2018-05-01 04:37:05</td>
      <td>2018-05-01 04:40:01</td>
      <td>3194</td>
      <td>McGinley Square</td>
      <td>3195</td>
      <td>Sip Ave</td>
      <td>29298</td>
      <td>Annual Membership</td>
      <td>Subscriber</td>
    </tr>
  </tbody>
</table>
</div>




```python
new_df.loc[['row_1','row_5','row_6'] , ['starttime' , 'name_localizedValue' , 'tripduration']]
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>starttime</th>
      <th>name_localizedValue</th>
      <th>tripduration</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>row_1</th>
      <td>2018-05-01 00:04:47</td>
      <td>Annual Membership</td>
      <td>338</td>
    </tr>
    <tr>
      <th>row_5</th>
      <td>2018-05-01 04:27:12</td>
      <td>Annual Membership</td>
      <td>303</td>
    </tr>
    <tr>
      <th>row_6</th>
      <td>2018-05-01 04:37:05</td>
      <td>Annual Membership</td>
      <td>176</td>
    </tr>
  </tbody>
</table>
</div>




```python
# slicing based on some conditions

new_df.loc[new_df['tripduration']>200]
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>tripduration</th>
      <th>starttime</th>
      <th>stoptime</th>
      <th>start station id</th>
      <th>start station name</th>
      <th>end station id</th>
      <th>end station name</th>
      <th>bikeid</th>
      <th>name_localizedValue</th>
      <th>usertype</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>row_1</th>
      <td>338</td>
      <td>2018-05-01 00:04:47</td>
      <td>2018-05-01 00:10:25</td>
      <td>3639</td>
      <td>Harborside</td>
      <td>3199</td>
      <td>Newport Pkwy</td>
      <td>33558</td>
      <td>Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>row_2</th>
      <td>1482</td>
      <td>2018-05-01 01:31:10</td>
      <td>2018-05-01 01:55:53</td>
      <td>3681</td>
      <td>Grand St</td>
      <td>3185</td>
      <td>City Hall</td>
      <td>33593</td>
      <td>24 Hour</td>
      <td>Customer</td>
    </tr>
    <tr>
      <th>row_3</th>
      <td>232</td>
      <td>2018-05-01 01:31:29</td>
      <td>2018-05-01 01:35:22</td>
      <td>3194</td>
      <td>McGinley Square</td>
      <td>3193</td>
      <td>Lincoln Park</td>
      <td>29217</td>
      <td>FREE Bonus Month with Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>row_5</th>
      <td>303</td>
      <td>2018-05-01 04:27:12</td>
      <td>2018-05-01 04:32:16</td>
      <td>3207</td>
      <td>Oakland Ave</td>
      <td>3195</td>
      <td>Sip Ave</td>
      <td>15271</td>
      <td>Annual Membership</td>
      <td>Subscriber</td>
    </tr>
  </tbody>
</table>
</div>




```python
## slicing based on some conditions

new_df.loc[new_df['tripduration']>200 , 'tripduration': 'start station id']
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>tripduration</th>
      <th>starttime</th>
      <th>stoptime</th>
      <th>start station id</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>row_1</th>
      <td>338</td>
      <td>2018-05-01 00:04:47</td>
      <td>2018-05-01 00:10:25</td>
      <td>3639</td>
    </tr>
    <tr>
      <th>row_2</th>
      <td>1482</td>
      <td>2018-05-01 01:31:10</td>
      <td>2018-05-01 01:55:53</td>
      <td>3681</td>
    </tr>
    <tr>
      <th>row_3</th>
      <td>232</td>
      <td>2018-05-01 01:31:29</td>
      <td>2018-05-01 01:35:22</td>
      <td>3194</td>
    </tr>
    <tr>
      <th>row_5</th>
      <td>303</td>
      <td>2018-05-01 04:27:12</td>
      <td>2018-05-01 04:32:16</td>
      <td>3207</td>
    </tr>
  </tbody>
</table>
</div>




```python
new_df.loc[new_df['usertype']=='Customer'] 
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>tripduration</th>
      <th>starttime</th>
      <th>stoptime</th>
      <th>start station id</th>
      <th>start station name</th>
      <th>end station id</th>
      <th>end station name</th>
      <th>bikeid</th>
      <th>name_localizedValue</th>
      <th>usertype</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>row_2</th>
      <td>1482</td>
      <td>2018-05-01 01:31:10</td>
      <td>2018-05-01 01:55:53</td>
      <td>3681</td>
      <td>Grand St</td>
      <td>3185</td>
      <td>City Hall</td>
      <td>33593</td>
      <td>24 Hour</td>
      <td>Customer</td>
    </tr>
    <tr>
      <th>row_4</th>
      <td>190</td>
      <td>2018-05-01 02:03:29</td>
      <td>2018-05-01 02:06:40</td>
      <td>3185</td>
      <td>City Hall</td>
      <td>3186</td>
      <td>Grove St PATH</td>
      <td>29662</td>
      <td>24 Hour</td>
      <td>Customer</td>
    </tr>
  </tbody>
</table>
</div>




```python
3 . iloc

- use to do slicing based on the rows and column only using index

syntax = df[zero_index_start:zero_index_stop:step, zero_index_column_start:zero_index_columnstop:step]
```


```python
new_df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>tripduration</th>
      <th>starttime</th>
      <th>stoptime</th>
      <th>start station id</th>
      <th>start station name</th>
      <th>end station id</th>
      <th>end station name</th>
      <th>bikeid</th>
      <th>name_localizedValue</th>
      <th>usertype</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>row_1</th>
      <td>338</td>
      <td>2018-05-01 00:04:47</td>
      <td>2018-05-01 00:10:25</td>
      <td>3639</td>
      <td>Harborside</td>
      <td>3199</td>
      <td>Newport Pkwy</td>
      <td>33558</td>
      <td>Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>row_2</th>
      <td>1482</td>
      <td>2018-05-01 01:31:10</td>
      <td>2018-05-01 01:55:53</td>
      <td>3681</td>
      <td>Grand St</td>
      <td>3185</td>
      <td>City Hall</td>
      <td>33593</td>
      <td>24 Hour</td>
      <td>Customer</td>
    </tr>
    <tr>
      <th>row_3</th>
      <td>232</td>
      <td>2018-05-01 01:31:29</td>
      <td>2018-05-01 01:35:22</td>
      <td>3194</td>
      <td>McGinley Square</td>
      <td>3193</td>
      <td>Lincoln Park</td>
      <td>29217</td>
      <td>FREE Bonus Month with Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>row_4</th>
      <td>190</td>
      <td>2018-05-01 02:03:29</td>
      <td>2018-05-01 02:06:40</td>
      <td>3185</td>
      <td>City Hall</td>
      <td>3186</td>
      <td>Grove St PATH</td>
      <td>29662</td>
      <td>24 Hour</td>
      <td>Customer</td>
    </tr>
    <tr>
      <th>row_5</th>
      <td>303</td>
      <td>2018-05-01 04:27:12</td>
      <td>2018-05-01 04:32:16</td>
      <td>3207</td>
      <td>Oakland Ave</td>
      <td>3195</td>
      <td>Sip Ave</td>
      <td>15271</td>
      <td>Annual Membership</td>
      <td>Subscriber</td>
    </tr>
    <tr>
      <th>row_6</th>
      <td>176</td>
      <td>2018-05-01 04:37:05</td>
      <td>2018-05-01 04:40:01</td>
      <td>3194</td>
      <td>McGinley Square</td>
      <td>3195</td>
      <td>Sip Ave</td>
      <td>29298</td>
      <td>Annual Membership</td>
      <td>Subscriber</td>
    </tr>
  </tbody>
</table>
</div>




```python
new_df.iloc[1:4:2 , 1:5]
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>starttime</th>
      <th>stoptime</th>
      <th>start station id</th>
      <th>start station name</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>row_2</th>
      <td>2018-05-01 01:31:10</td>
      <td>2018-05-01 01:55:53</td>
      <td>3681</td>
      <td>Grand St</td>
    </tr>
    <tr>
      <th>row_4</th>
      <td>2018-05-01 02:03:29</td>
      <td>2018-05-01 02:06:40</td>
      <td>3185</td>
      <td>City Hall</td>
    </tr>
  </tbody>
</table>
</div>




```python
# normal slicing
- only on rows
- both custom and zero is allowed

# loc
- both rows and columns
- only custom is allowed
- random slicing
- conditional possible

#.iloc
- both rows and columns
- only zero_indexing is allowed
```


```python
# select all the data where user type is Subscriber and bikeid is more than 30000
new_df.loc[(new_df['usertype']=='Subscriber') & (new_df['bikeid']>30000) & (new_df['tripduration']>100)]
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>tripduration</th>
      <th>starttime</th>
      <th>stoptime</th>
      <th>start station id</th>
      <th>start station name</th>
      <th>end station id</th>
      <th>end station name</th>
      <th>bikeid</th>
      <th>name_localizedValue</th>
      <th>usertype</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>row_1</th>
      <td>338</td>
      <td>2018-05-01 00:04:47</td>
      <td>2018-05-01 00:10:25</td>
      <td>3639</td>
      <td>Harborside</td>
      <td>3199</td>
      <td>Newport Pkwy</td>
      <td>33558</td>
      <td>Annual Membership</td>
      <td>Subscriber</td>
    </tr>
  </tbody>
</table>
</div>




```python
sat - pandas_mat
sunday - seaborn

sat
sund - 8 to 10am
```
